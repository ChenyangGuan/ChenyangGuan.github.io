---
layout: page
title: The Dream World
tagline: Computer Science Knowledge Pool
---
{% include JB/setup %}


## Sample Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




