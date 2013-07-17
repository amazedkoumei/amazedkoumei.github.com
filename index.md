---
layout: page
title: Home
tagline: 
group: navigation
---
{% include JB/setup %}

<div>
  {% for post in site.posts %}
  <div class='post hentry uncustomized-post-template'>
    <div class="post-list-hedaer">
      {{ post.date | date: "%Y/%m/%d %H:%M" }} &raquo;
      {% assign tags_list = post.tags %}
      {% include JB/tags_list %}
    </div>
    <div class="post-list-title">
      <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    </div>
  </div>
  <hr />
  {% endfor %}
</div>

