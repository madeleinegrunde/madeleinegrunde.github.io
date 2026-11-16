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

Publications
======
{% include publication-list.html section="main" %}

Preprints and workshop papers
======
{% include publication-list.html section="preprint" %}
