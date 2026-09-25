---
layout: default
title: 首页
---

## [ 正在访问 ]

> 系统就绪。欢迎来到luling的博客。

<pre style="color: #00ff00; background: #000; padding: 15px; border: 1px solid #00ff00; border-radius: 5px; line-height: 1.5;">
{% for post in site.posts %}
{{ post.date | date: "%Y-%m-%d" }}  <a href=" " style="color: #00ff00; text-decoration: underline;">{{ post.title }}</a >
{% endfor %}
</pre>
