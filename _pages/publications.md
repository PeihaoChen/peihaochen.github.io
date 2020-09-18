---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<table>
{% for post in site.publications reversed %}
  <tr>{% include publication.html %}</tr>
{% endfor %}
</table>
