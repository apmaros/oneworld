---
layout: default
comments: true
---

<div>
  {% for post in site.posts %}
    <div class="post">
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}
        <img src="https://raw.githubusercontent.com/apmaros/oneworld/master/assets/{{post.assets}}/{{post.hero}}" alt="image hero for {{ post.title }}">
      </a>
    <div>
  {% endfor %}
</div>