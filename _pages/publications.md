---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## Preprints

{% assign publications_count = site.publications | size %}
{% assign preprints_count = site.preprints | size %}
{% assign preprints_start = publications_count | plus: preprints_count %}
<ol start="{{ preprints_start }}" reversed class="archive__item-publications">
{% for post in site.preprints reversed %}
  {% include archive-publication.html %}
{% endfor %}
</ol>

## Published

<ol reversed class="archive__item-publications">
{% for post in site.publications reversed %}
  {% include archive-publication.html %}
{% endfor %}
</ol>
<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
