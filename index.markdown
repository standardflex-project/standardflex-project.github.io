---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: ""
---

## Accompanying material for the STANDARDFLEX project proposal.

The list of references and relevant projects below corresponds to the STANDARDFLEX
project proposal coordinated by ICCS (EL) under HORIZON EUROPE call
HORIZON-CL5-2022-D3-01-12: Replicable solutions for a cross sector compliant energy ecosystem.

1. [List of references](#list-of-references)
2. [List of relevant projects](#list-of-relevant-projects)
3. [Letters of Intention](#letters-of-intention)

### List of references

{% for ref in site.data.references %}

- **{{ ref.ref_id }}** {{ref.content}}

{% endfor %}

[Back to top](#)

### List of relevant projects

{% for proj in site.data.relevant_projects %}

- **{{ proj.acronym }}** [{{proj.link}}]({{proj.link}})

{% endfor %}

### Letters of intention

{% for letter in site.data.letters %}

- **{{ letter.acronym }}** [{{letter.filename}}]({{letter.filename | prepend: '/assets/letters/' | prepend: site.baseurl}})

{% endfor %}

[Back to top](#)
