---
layout: default
---
# Schemas voor Verantwoorde Inzet van Technologie (VIT)

{% for json in site.static_files %}
{% if json.path contains 'schema.json' %}
[{{ json.path }}](reader.html?url={{ json.basename }}{{ json.extname }})
{% endif %}
{% endfor %}

## Samenwerken op Github

Samenwerken aan herbruikbare schema's voor vastgestelde standaarden en standaarden in ontwikkeling? Check [https://github.com/Algoritmeregister/schemas](https://github.com/Algoritmeregister/schemas)
