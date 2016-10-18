---
layout: default
title: Articles
subtitle: Much Read! So Wow!
---

<div class="posts">
  {% for post in site.posts %}
      {% assign category = site.my_categories | where: "slug", post.category %}
      {% assign category = category[0] %}
  
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>
      
      {% if category %}
      {% capture category_content %}<a class="label" href="{{ category.url }}">{{ category.name }}</a>{% endcapture %}
      {% endif %}

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
    
    
  {% endfor %}
</div>