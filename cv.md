---
layout: page
title: CV
permalink: /cv/
---

{%for cv in site.data.cv%}

  {{site.baseurl}}{{cv | markdownify}}

{%endfor%}