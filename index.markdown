---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: ""
---

## Accompanying material for the AUTOFLEX project proposal.

The list of references and relevant projects below corresponds to the AUTOFLEX
project proposal coordinated by ICCS (EL) under HORIZON EUROPE call
CL5-2021-D3-02-06: Increasing energy system flexibility based on
sector-integration services to consumers (that benefits system management by
DSOs and TSOs.

1. [List of references](#list-of-references)
2. [List of relevant projects](#list-of-relevant-projects)

### List of references

{% for ref in site.data.references %}

- **{{ ref.ref_id }}** {{ref.content}}

{% endfor %}

[Back to top](#)

### List of relevant projects

{% for proj in site.data.relevant_projects %}

- **{{ proj.acronym }}** [{{proj.link}}]({{proj.link}})

{% endfor %}

[Back to top](#)
