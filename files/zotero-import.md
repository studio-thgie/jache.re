---
title: {{title}}
authors: {{authors}}
year: {{date | format("YYYY")}}
tags: {% for tag in tags %}{{tag.tag}}{% if not loop.last %}, {% endif %}{% endfor %}
---
## {{title}}
## Bibliography
{{bibliography}}
{% if abstractNote %}
## Notes
{% persist "notes" %}
{% endpersist %}
## Abstract
{{abstractNote}}
{% endif %}
{% if markdownNotes %}
## Reading Notes
{{markdownNotes}}
{% endif %}