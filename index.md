---
layout: default
title: 首页
---

## [ 访问终端 ]

> 系统就绪。欢迎来到luling的博客。
> 当前目录：/home/hacker/posts

<pre style="color: #00ff00; background: #000; padding: 15px; border: 1px solid #00ff00; border-radius: 5px; line-height: 1.5;">
> ls ./posts
{% for post in site.posts %}
  <a href=" " style="color: #00ff00; text-decoration: none;">{{ post.title }}</a >
{% endfor %}
</pre>

> 输入 `cat [文件名]` 可阅读文章。
