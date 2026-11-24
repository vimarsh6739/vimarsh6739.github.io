---
layout: archive
author_profile: true
title: Publications
permalink: /publications/
---

See also [Google Scholar](https://scholar.google.com/citations?user=Aryo7Y4AAAAJ) and my [CV](/assets/files/academic_cv.pdf).

## Conference Papers

{% for p in site.data.publications.conference %}{% include publication.html pub=p %}{% endfor %}

## Workshop Papers

{% for p in site.data.publications.workshop %}{% include publication.html pub=p %}{% endfor %}

<!-- ## Under Review -->

{% for p in site.data.publications.under_review %}{% include publication.html pub=p %}{% endfor %}

## Preprints

{% for p in site.data.publications.preprints %}{% include publication.html pub=p %}{% endfor %}
