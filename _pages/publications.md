---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

A complete and continuously updated record is available on [HAL]({{ site.author.hal }}){% if site.author.orcid %}, [ORCID]({{ site.author.orcid }}){% endif %}{% if site.author.googlescholar %} and [Google Scholar]({{ site.author.googlescholar }}){% endif %}.

Published and accepted
======

{% assign published = site.publications | where_exp: "post", "post.status == nil" | sort: "date" | reverse %}
{% for post in published %}
  {% include archive-single.html %}
{% endfor %}

Under review
======

{% assign under_review = site.publications | where: "status", "Under review" | sort: "date" | reverse %}
{% for post in under_review %}
  {% include archive-single.html %}
{% endfor %}

In preparation
======

{% assign in_prep = site.publications | where: "status", "In preparation" | sort: "date" | reverse %}
{% for post in in_prep %}
  {% include archive-single.html %}
{% endfor %}
