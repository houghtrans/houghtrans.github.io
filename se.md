---
layout: search
title: SE Collections
author_profile: false
---

{% for se in site.se %}


<a href="{{ se.url | prepend: site.baseurl }}">
        {{ se.title }}
</a>

<p class="post-excerpt">{{ se.description | truncate: 160 }}</p>

{% endfor %} 
 
