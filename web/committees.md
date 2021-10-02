---
title: Committees
template: base.html
---

{%- import "macros.html" as macros %}


<div class="callout">
We are still recruiting our to complete the committee board. Join us!
</div>

{{ macros.make_people_list(page.current) }}

<hr class="mb-5">

## Collaborators

{{ macros.make_people_list(page.collaborators) }}

