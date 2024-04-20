---
layout: default
---
# Schemas voor Verantwoorde Inzet van Technologie (VIT)

{% for schemaFile in site.pages %}
{% if schemaFile.path contains 'schema.json' %}
[{{ schemaFile.title }}](reader.html?url={{ schemaFile.path | absolute_url }})
{% endif %}
{% endfor %}

## Samenwerken op Github

Samenwerken aan herbruikbare schema's voor vastgestelde standaarden en standaarden in ontwikkeling? Check [https://github.com/Algoritmeregister/schemas](https://github.com/Algoritmeregister/schemas)
