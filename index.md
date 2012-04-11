---
layout: page
title: Peter To
---

## Welcome to my github page

Check out my projects on my [github](http://github.com/peterto) account. I'm primarily a gamer geek
and like to experiment with various video game mechanics.


## Posts
<ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a
      href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
