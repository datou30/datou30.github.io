---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

* [Home]({{ '/' | relative_url }})
* [CV]({{ '/cv/' | relative_url }})
* [Publications]({{ '/publications/' | relative_url }})

## Research

{% assign papers = site.publications | sort: 'cv_order' %}
{% for paper in papers %}
* [{{ paper.title }}]({{ paper.url | relative_url }})
{% endfor %}

## CV downloads

* [English CV (PDF)]({{ '/assets/CV_ZhengyangHu.pdf' | relative_url }})
* [中文简历 (PDF)]({{ '/assets/CV_ZhengyangHu_zh.pdf' | relative_url }})
