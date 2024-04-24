---
layout: default
---
# Schemas voor Verantwoorde Inzet van Technologie (VIT)

{% assign sortedPages = site.pages | sort: 'url' %}
{% for schemaFile in sortedPages %}
{% if schemaFile.path contains 'schema.json' %}
[{{ schemaFile.title }}](reader.html?url={{ schemaFile.path | absolute_url }})
{% endif %}
{% endfor %}

## Samenwerken op Github

Samenwerken aan herbruikbare schema's voor vastgestelde standaarden en standaarden in ontwikkeling? Check [https://github.com/Algoritmeregister/schemas](https://github.com/Algoritmeregister/schemas)
