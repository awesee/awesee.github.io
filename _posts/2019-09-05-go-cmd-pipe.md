---
layout: single
title:  "Go系统命令管道操作"
date:   2019-09-05 12:30:00 +0800
categories: [Go]
tags: [Go, Guide]
permalink:  /go-cmd-pipe/
---

go 执行系统命令时不能直接使用管道操作

### 方法一

```go
func async() {
	cmd1 := exec.Command("ls", ".")
	cmd2 := exec.Command("grep", "go")
	out, _ := cmd1.StdoutPipe()
	in, _ := cmd2.StdinPipe()
	cmd2.Stdout = os.Stdout
	go func() {
		defer func() {
			out.Close()
			in.Close()
		}()
		io.Copy(in, out)
	}()
	cmd1.Run()
	cmd2.Run()
}
```

### 方法二

```go
func sync() {
	cmd1 := exec.Command("ls", ".")
	cmd2 := exec.Command("grep", "go")
	in, _ := cmd2.StdinPipe()
	cmd1.Stdout = in
	cmd2.Stdout = os.Stdout
	cmd2.Start()
	cmd1.Run()
	in.Close()
	cmd2.Wait()
}
```

### 方法三

```go
func main() {
	cmd1 := exec.Command("ls", ".")
	cmd2 := exec.Command("grep", "go")
	cmd3 := exec.Command("grep", "main")
	cmd3.Stdout = os.Stdout
	pipe(cmd1, cmd2, cmd3)
	cmd1.Run()
	cmd2.Run()
	cmd3.Run()
}

func pipe(cmds ...*exec.Cmd) {
	for i, cmd := range cmds {
		if i > 0 {
			out, _ := cmds[i-1].StdoutPipe()
			in, _ := cmd.StdinPipe()
			go func() {
				defer func() {
					out.Close()
					in.Close()
				}()
				io.Copy(in, out)
			}()
		}
	}
}
```
