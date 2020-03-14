---
layout: no_footer
title: 記事の一覧
pagename: 記事の一覧
showfooter: False
---
{% for post in site.posts %}
<div class="post_link">
<div class="post_title">
・<a href="Poteto143s_diary/{{ post.url }}">{{ post.title }}</a>
</div>
更新日:{{ post.date | date: "%Y/%m/%d"}} 
</div>
{% endfor %}
