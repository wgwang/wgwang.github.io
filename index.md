---
layout: page
title: 停停走走・点点滴滴
tagline: 记录・人生
---
{% include JB/setup %}

## 认识我

昨岁今时临北地， <br/> 孤身闯荡品京华。 <br/> 南风北韵添新梦， <br/> 碎舞残歌葬落花。 <br/> 芳草流萤依醉影， <br/> 银蛇蜡像掩黄沙。 <br/> 天涯路远知音杳， <br/> 立地男儿处处家。 

## 博客列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



