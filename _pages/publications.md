---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<p>You can also find my articles on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.</p>
{% endif %}

{% assign papers = site.publications | sort: 'cv_order' %}

## Published papers

{% for post in papers %}
  {% if post.status == 'published' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Manuscripts under review

{% for post in papers %}
  {% if post.status == 'under-review' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
