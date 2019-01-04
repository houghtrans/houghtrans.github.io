---
layout: search
title: MLDL Collections
author_profile: false
---

{% for mldl in site.mldl %}


<a href="{{ mldl.url | prepend: site.baseurl }}">
        {{ mldl.title }}
</a>

<p class="post-excerpt">{{ mldl.description | truncate: 160 }}</p>

{% endfor %} 
 
