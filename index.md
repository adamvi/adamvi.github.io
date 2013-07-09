---
layout: default
title: Adam VanIwaarden
---
{% include JB/setup %}


## Latest 10 posts

<ul class="posts">
  {% for post in site.posts limit:10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  <li><a href="archive.html">Read More...</a></li>
</ul>

## How to contribute

You can [fork the repository](https://github.com/supstat/vistat) on Github, add your article to the `_source` directory and submit a pull request to us. We will run your code and upload images. For more details, see [about](about.html).

## Copyright

All the content in this website is licensed under [CC BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). This site is hosted on [GitHub](https://github.com) Pages using the [Dinky theme](https://github.com/sodabrew/theme-dinky) for [Jekyll Bootstrap](http://jekyllbootstrap.com).
