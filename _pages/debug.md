---
layout: single
title: "Debug"
permalink: /debug/
author_profile: true
---

## Site settings
- `site.url` = `{{ site.url }}`
- `site.baseurl` = `{{ site.baseurl }}`
- `timezone` = `{{ site.timezone }}`

## Navigation (docs)
{% for item in site.data.navigation.docs %}
- {{ item.title }} → {{ item.url }}
{% endfor %}

## Assets check
- CSS: [/assets/main.css](/assets/main.css)
- Custom CSS: [/assets/css/custom-sticky.css](/assets/css/custom-sticky.css)

If any of the links above 404, the head/CSS isn’t loading as expected.
