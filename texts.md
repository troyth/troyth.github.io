---
layout: default
title: Texts
---

{% for texts in site.texts %}


<a href="{{ texts.url | prepend: site.baseurl }}">
        <h2>{{ texts.title }}</h2>
</a>

<p class="post-excerpt">{{ texts.description | truncate: 160 }}</p>

{% endfor %}   
