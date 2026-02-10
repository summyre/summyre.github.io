---
layout: page
title: Projects
---

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})

**Tech:** {{ project.tech }}
[GitHub Repo]({{ project.github }})

---
{% endfor %}
