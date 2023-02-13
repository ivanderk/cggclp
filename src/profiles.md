---
layout: page.njk
title: profiles
---


{% for profile in collections.profiles %}
  <article>
    <h1>
      <a href="{{ profile.url | url }}">{{ profile.data.fullname }}</a>
    </h1>

  </article>
{% endfor %}