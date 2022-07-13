---
layout: page
title: News
permalink: /news/
---

# News

<div class="post-listing-container">
  {% for post in site.posts %}
  <div class="post-listing">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <div class="post-info post-listing-info">
      <span class="post-date">{{ post.date | date: "%-d %B %Y" }}</span>
    </div>
    {% if post.thumbnail %}
    <img class="post-thumbnail" src="{{ post.thumbnail }}"/>
    {% endif %}
    <p>{{ post.content | strip_html | truncatewords: 80 }}</p>
    {% assign nwords = post.content | number_of_words %}
    {% if nwords > 80 %}
    <a class="post-read-more" href="{{ post.url }}">CONTINUE READING...</a>
    {% endif %}
    <hr>
  </div>
  {% endfor %}
</div>