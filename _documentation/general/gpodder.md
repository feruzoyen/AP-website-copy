---
title: documentation.categories.general.gpodder
layout: doc
level: "2"
group: "general"
icon: "fas fa-sync"
---

# {% t {{ page.title }} %}

{% capture content %}{% tf documentation/{{ page.group }}/{{ page.slug }}.md %}{% endcapture %}{{content | remove: "<!-- mdpo-disable -->" | remove: "<!-- mdpo-enable -->" | remove: "<!-- mdpo-disable-next-line -->" | remove: "<!-- mdpo-enable-next-line -->" }}
