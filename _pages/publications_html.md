---
layout: archive
title: "Publications"
permalink: /publications_html/
author_profile: true
---

See a full list on [Google Scholar](https://scholar.google.com/citations?user=2OyjqLoAAAAJ&hl=en)

## Patents

{% assign patents = site.publications | where: "type", "patent" | sort: 'name' | reverse %}
{% for publication in patents %}
  {% include publication-card_authors.html title=publication.title link=publication.link authors=publication.authors venue=publication.venue %}
{% endfor %}

## Journals

{% assign journals = site.publications | where: "type", "journal" | sort: 'name' | reverse %}
{% for publication in journals %}
  {% include publication-card_authors.html title=publication.title link=publication.link authors=publication.authors venue=publication.venue %}
{% endfor %}

## Conferences

{% assign conferences = site.publications | where: "type", "conference" | sort: 'name' | reverse %}
{% for publication in conferences %}
  {% include publication-card_authors.html title=publication.title link=publication.link authors=publication.authors venue=publication.venue %}
{% endfor %}


