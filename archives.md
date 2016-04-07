---
layout: page
title: archives
icon: <i class="fa fa-suitcase"></i>
permalink: /archives/
---

|[]()| | |
|-------------------------------------:|:--------:|:----------------| {% for my_post in site.posts %} {% if my_post.title %}
|  {{ my_post.date | date_to_string }} |  &nbsp; • &nbsp; |  [{{ my_post.title }}]({{ my_post.url | prepend:site.baseurl }})  |{% endif %} {% endfor %}


