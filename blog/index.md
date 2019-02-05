---
layout: default
title: Blog
---
<h1>Recent Projects</h1>

<ul>
  <li>
  {% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
  </li>
  {% endfor %}
</ul>
