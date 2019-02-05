---
layout: default
title: Blog
---
<h1>Recent Projects</h1>

<ul>
  {% for repository in site.github.public_repositories %}
  <li>
  * [{{ repository.name }}]({{ repository.html_url }})
  </li>
  {% endfor %}
</ul>
