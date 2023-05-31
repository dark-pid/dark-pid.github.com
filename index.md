---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
permalink: /
---

![](/assets/img/dark-logo.png)


<ul class="post-item-list">
  {% for post in site.posts %}
    <li class="post-item">
      <a class="post-item-title" href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }} <a class="post-item-excerpt" href="{{ post.url }}">read more</a>
    </li>
  {% endfor %}
</ul>
