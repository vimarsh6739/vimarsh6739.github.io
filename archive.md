---
layout: page
title: Archive
---
<!-- Non paginated list of all posts -->

{% for post in site.posts %}
* {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}