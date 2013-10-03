---
layout: page
title: Dissertation
---
{% include JB/setup %}

This page serves as a unified repository to help organize references and track progress.

## References
[References Page]({% page_url ref%})
    
## Blog style posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

