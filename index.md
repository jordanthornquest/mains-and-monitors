---
title: Home
layout: full-page
---

# Kalani

Coming Thanksgiving Day 2018.

<a class="button" href="https://www.youtube.com/watch?v=OFwCMxfd7kk">Hear our new single "Auckland"</a>

<nav>
  <ul>
    {% for link in site.data.nav.nav_items %}
      <li><a href="{{ link.url }}">{{ link.title }}</a></li>
    {% endfor %}
  </ul>
</nav>
