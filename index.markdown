---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

The list of references below corresponds to the AUTOFLEX project proposal
coordinated by ICCS (EL) under HORIZON EUROPE call CL5-2021-D3-02-06: Increasing
energy system flexibility based on sector-integration services to consumers
(that benefits system management by DSOs and TSOs

{% for ref in site.data.references %}

- **{{ ref.ref_id }}** {{ref.content}}

{% endfor %}
