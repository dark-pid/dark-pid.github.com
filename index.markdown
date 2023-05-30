---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
permalink: /
---

![](/dark-logo.png)


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}"><b>{{ post.title }}</b></a>
      {{ post.excerpt }} <a href="{{ post.url }}">more</a>
    </li>
    <br/>

  {% endfor %}
</ul>
