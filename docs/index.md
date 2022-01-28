---
layout: default
title: Home
nav_order: 1
description: "Alembik documentation"
permalink: /
---

# Alembik
{: .fs-9 }

Automated social network manager
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Alembik website](https://www.alembik.io){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

Alembik can be used to create an automated blog or website, with integrated social networks sharing

### Social networks integrations

- [examples]({{ site.baseurl }}examples)

## About the project

Discover more option on alembik.io

#### Contributors:

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
