---
layout: default
---

<ul class="Posts">
  <h1>Posts</h1>
  {% for post in site.posts %}
    <li class="PostItem">
      <!-- <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}: </span> -->
      <!-- <a class="post-link" href="{{ post.url }}">{{ post.title }}</a> -->
      <a class="PostItem__Title" href="{{ post.url }}">{{ post.title }}</a>
      <span class="PostItem__Date">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

  <!-- <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p> -->

