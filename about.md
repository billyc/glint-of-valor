---
layout: default
title: About us
---

# About your adventurers

We come from far and wide, but we've all found our way to SALTMARSH. Now we travel together in search of answers... and gold!

<br/>

<table>
{% for character in site.data.characters %}

<tr class="character-row">
   <td> <h3 class="character-name">{{ character.name }}</h3></td>
    <td><div style="display: flex; flex-direction: column">
        <p class="character-details"><b>Race:</b> {{ character.race }}</p>
        <p class="character-details"><b>Class:</b> {{ character.class }}</p>
        <p class="character-details"><i>{{ character.story}}</i></p>
    </div>
    </td>
</tr>
{% endfor %}
</table>
