---
layout: project-documentation
title: Project Doc Collections
author_profile: false
permalink: /project_doc/
link: https://houghtrans.github.io/ppprojects/
--- 

<nav id='sidebar'>
	{% include project_doc_nav.html %}
</nav>

<section id='content'>
{% for post in site.posts %}
  <article class='{{ post.type }}'>
    <a name='{{ post.url }}' href='#{{ post.url }}'><h2>{% if post.type %}<code><b>{{ post.type }}</b> {{ post.path }}</code> {% endif %}{{ post.title }}</h2></a>
    <section class='body'>
      {{ post.content }}
    </section>
  </article>
{% endfor %}
</section>



