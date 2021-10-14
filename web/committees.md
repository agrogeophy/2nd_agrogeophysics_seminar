---
title: Committee
template: base.html
---

{%- import "macros.html" as macros %}

{{ macros.make_people_list(page.current) }}

<hr class="mb-5">

## Collaborators

{{ macros.make_people_list(page.collaborators) }}

