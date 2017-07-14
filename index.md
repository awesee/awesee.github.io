---
layout: default
---

{% for post in paginator.posts %}
    ## [{{ post.title }}]({{ site.url }}{{ post.url }})
    {{ post.date | date: "%Y/%m/%d" }}

    {{ post.excerpt | strip_html | strip }}
    ---
{% endfor %}

{% if paginator.previous_page %}
    {% if paginator.previous_page == 1 %}
      [首页]({{ site.url }})
    {% else %}
        [上一页]({{ site.url }}{{paginator.previous_page}})
    {% endif %}
{% else %}
    [<<](#)
{% endif %}

