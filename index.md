---
layout: index
title: Sākums
---
<ul>
  {% for post in site.posts %}
        <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
        {{ post.excerpt }}
        {% if post.full_content != true %}
        <a href="{{ site.baseurl }}{{ post.url }}">Lasīt vairāk</a>
        {% endif %}
  {% endfor %}
</ul>
