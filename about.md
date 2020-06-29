---
layout: default
title: About us
---

# About your adventurers

We come from far and wide, but we've all found our way to Saltmarsh. Now we travel together in search of answers... and gold!

{% for character in site.data.characters %}

### {{ character.name }}

**Race:** {{ character.race }}
**Class:** {{ character.class }}

{{ character.story}}

{% endfor %}
