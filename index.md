---
---
# Hello World
site.url: {{site.url}}

{%if site.url == 'https://mkgask.github.io'%}{%assign site_url = site.url%}{% else %}{%assign site_url = '//localhost'%}{% endif %}
<base href="{{ site_url }}">
