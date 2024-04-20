---
layout: default
---
# Schemas voor Verantwoorde Inzet van Technologie (VIT)

{% for schemaFile in site.static_files %}
{% if schemaFile.path contains 'schema.json' %}
[{{ schemaFile.path | relative_url }}](reader.html?url={{ schemaFile.path | relative_url }})
{% endif %}
{% endfor %}

{% for schemaFile in site.pages %}
{% if schemaFile.path contains 'schema.json' %}
[{{ schemaFile.title }}](reader.html?url={{ schemaFile.path | relative_url }})
{% endif %}
{% endfor %}

## Samenwerken op Github

Samenwerken aan herbruikbare schema's voor vastgestelde standaarden en standaarden in ontwikkeling? Check [https://github.com/Algoritmeregister/schemas](https://github.com/Algoritmeregister/schemas)
