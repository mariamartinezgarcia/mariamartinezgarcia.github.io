---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Peer-reviewed conferences and workshops
------
{% include base_path %}

{% for post in site.conferences reversed %}
  {% include archive-single.html %}
{% endfor %}

Preprints
------
{% include base_path %}

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}



