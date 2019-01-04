---
layout: search
title: CV Collections
author_profile: false
---

{% for cv in site.cv %}


<a href="{{ cv.url | prepend: site.baseurl }}">
        {{ cv.title }} 
</a>

<p class="post-excerpt">{{ cv.description | truncate: 160 }}</p>

{% endfor %} 
