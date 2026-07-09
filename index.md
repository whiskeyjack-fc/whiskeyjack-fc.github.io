---
layout: default
title: Home
---

# Current Drafts

A working library of in-progress stories — updated as drafts change. Comments and reactions are welcome on each story page.

<ul class="story-list">
{% for story in site.stories %}
  <li>
    <h2><a href="{{ story.url | relative_url }}">{{ story.title }}</a></h2>
    <p><em>{{ story.blurb }}</em></p>
  </li>
{% endfor %}
</ul>

