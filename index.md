---
layout: default
---
# Schemas voor Verantwoorde Inzet van Technologie (VIT)

{% for json in site.static_files %}
{% if json.path contains 'schema.json' %}
[{{ json.path }}]({{ "/reader.html" | relative_url | append: "?url=" | append: json.path | absolute_url }})
{% endif %}
{% endfor %}
