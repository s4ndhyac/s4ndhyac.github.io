---
layout: page
title: Projects
permalink: /projects/
---

### Projects

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
