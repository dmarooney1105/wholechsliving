---
permalink: /Wellness/
layout: page
hero-title: Wellness
hero_image_path: /images/backgrounds/IMG_1852.jpg
lead-in: My Experiences and Opinions on Trending Health Topics
bg-position: center
---

<div class="container default"><h2 class="editable trafalgar text-center editable">Wellness Thoughts</h2><div blog-gallery="many"><ul><li>{% for post in site.categories.wellness %}</li><li class="fitness invert"><div class="preview" style="background-position: center {{ post.image-position }}; background-image: url('{{ post.main_image_path }}')">&nbsp;</div><h4 class="pica"><a class="hvr-grow" href="{{ post.url }}">{{ post.title }}</a></h4></li><li>{% endfor %}</li></ul><div class="container default"><div blog-gallery="many"><div blog-gallery="many"><h2 class="editable trafalgar text-center editable" style="padding-top: 50px;">Thyroid / Hormone / ED Stories</h2></div></div></div></div></div>