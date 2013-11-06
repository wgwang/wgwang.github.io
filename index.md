---
layout: page
title: 停停走走・点点滴滴
tagline: 记录・人生
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li>
        <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
        <p>{{ post.excerpt }}</p>    
    </li>
  {% endfor %}

</ul>



