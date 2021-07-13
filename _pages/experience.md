---
title: "Experience and work that I have done"
layout: category
permalink: /experience/
taxonomy: Experience
author_profile: true
---

<h3 class="archive__subtitle">Drafts</h3>
<div >
  {% for post in posts %}
    {% if post.categories contains "Drafts" %}
      {% include archive-single.html type=entries_layout %}
    {% endif %}
  {% endfor %}
</div>