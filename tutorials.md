---
layout: page
title: Hi, I'm Emmanuel
subtitle: Machine Learning Research Scientist 
css: "/css/index.css"
use-site-title: true
bigimg:
  - "/img/big-imgs/china-great-wall.jpeg" : "Beijing, China (2011)"
  - "/img/big-imgs/china-mountain.jpeg" : "China (2011)"
  - "/img/big-imgs/china-mountain1.jpeg" : "China (2011)"
  - "/img/big-imgs/china-mountain2.jpeg" : "China (2011)"
  - "/img/big-imgs/china-ancient-house.jpeg" : "China (2011)"
  - "/img/big-imgs/china-lake.jpeg" : "China (2011)"
  - "/img/big-imgs/china-river.jpeg" : "China (2011)"
  - "/img/big-imgs/sweden-bridge.jpeg" : "Sweden (2018)"
  - "/img/big-imgs/sweden-skyview.jpeg" : "Sweden (2018)"
  - "/img/big-imgs/sweden-skyview1.jpeg" : "Sweden (2018)"
  - "/img/big-imgs/sweden-water.jpeg" : "Sweden (2018)"
---

<div class="list-filters">
  <a href="/" class="list-filter filter-selected">All posts</a>
  <a href="/popular" class="list-filter">Most Popular</a>
  <a href="/tutorials" class="list-filter">Tutorials</a>
  <a href="/tags" class="list-filter">Index</a>
</div>


<div class="posts-list">
  {% for post in site.tags.tutorial %}
  <article>
    <a class="post-preview" href="{{ post.url | prepend: site.baseurl }}">
      <h2 class="post-title">{{ post.title }}</h2>
  
      {% if post.subtitle %}
      <h3 class="post-subtitle">
        {{ post.subtitle }}
      </h3>
      {% endif %}
      <p class="post-meta">
        Posted on {{ post.date | date: "%B %-d, %Y" }}
      </p>

      <div class="post-entry">
        {{ post.content | truncatewords: 50 | strip_html | xml_escape}}
        <span href="{{ post.url | prepend: site.baseurl }}" class="post-read-more">[Read&nbsp;More]</span>
      </div>
    </a>  
   </article>
  {% endfor %}
</div>