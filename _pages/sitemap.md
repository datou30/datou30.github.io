---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

* [Home]({{ '/' | relative_url }})
* [CV]({{ '/cv/' | relative_url }})
* [Publications]({{ '/publications/' | relative_url }})
* [Talks and presentations]({{ '/talks/' | relative_url }})
* [Teaching]({{ '/teaching/' | relative_url }})

## Research

{% assign papers = site.publications | sort: 'cv_order' %}
{% for paper in papers %}
* [{{ paper.title }}]({{ paper.url | relative_url }})
{% endfor %}

## Talks and presentations

{% for talk in site.talks reversed %}
* [{{ talk.title }}]({{ talk.url | relative_url }})
{% endfor %}

## Teaching

{% for course in site.teaching reversed %}
* [{{ course.title }}]({{ course.url | relative_url }})
{% endfor %}

## CV downloads

* [English CV (PDF)]({{ '/assets/CV_ZhengyangHu.pdf' | relative_url }})
* [中文简历 (PDF)]({{ '/assets/CV_ZhengyangHu_zh.pdf' | relative_url }})
