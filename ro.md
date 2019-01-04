---
layout: search
title: RO Collections
author_profile: false
---

{% for ro in site.ro %}


<a href="{{ ro.url | prepend: site.baseurl }}">
        {{ ro.title }}
</a>

<p class="post-excerpt">{{ ro.description | truncate: 160 }}</p>

{% endfor %} 
 
