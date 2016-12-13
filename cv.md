---
layout: page
title: CV
permalink: /cv/
---

{%for cv in site.data.cv%}

  {{cv | markdownify}}

{%endfor%}
