---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Welcome to my blog"

---
Welcome to my blog! Here are my latest posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ posts.url }}">{{ post.title }}</a> ({{ post.date | date: "%Y-%m-%d" }})
    </li>
  {% endfor %}
</ul>
