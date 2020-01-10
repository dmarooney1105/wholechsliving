---
permalink: /Wellness
layout: page
hero-title: Wellness
hero_image_path: /images/IMG_3206.JPG
lead-in: My Health Journey
bg-position: center
---

<div class="container default"><h2 class="editable trafalgar text-center editable">Wellness Thoughts</h2><div blog-gallery="many"><ul><li>{% for post in site.categories.fitness %}</li><li class="fitness invert"><div class="preview" style="background-position: center {{ post.image-position }}; background-image: url('{{ post.main_image_path }}')">&nbsp;</div><h4 class="pica"><a class="hvr-grow" href="{{ post.url }}">{{ post.title }}</a></h4></li><li>{% endfor %}</li></ul><div class="container default"><h2 class="editable trafalgar text-center editable">&nbsp;</h2><div blog-gallery="many">&nbsp;</div></div></div></div>