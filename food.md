---
permalink: /food/
layout: page
hero-title: Food
hero_image_path: /images/fran3.jpg
lead-in: 'My health, trending nutrition topics, and Recipes!'
bg-position: center
---

<div class="container default"><h2 class="editable trafalgar text-center editable">Wellness Thoughts</h2><div blog-gallery="many"><ul><li>{% for post in site.categories.wellness %}</li><li class="fitness invert"><div class="preview" style="background-position: center {{ post.image-position }}; background-image: url('{{ post.main_image_path }}')">&nbsp;</div><h4 class="pica"><a class="hvr-grow" href="{{ post.url }}">{{ post.title }}</a></h4></li><li>{% endfor %}</li></ul></div><h2 class="editable trafalgar text-center editable">My First Whole 30</h2><center>&nbsp;</center><div blog-gallery="many"><!-- <h2 class="editable double-pica text-center editable" style="margin: 30px;">All Posts</h2> --><ul><li>{% for post in site.categories.food %}</li><li class="food invert"><div class="preview" style="background-position: center {{ post.image-position }}; background-image: url('{{ post.main_image_path }}')">&nbsp;</div><h4 class="pica"><a class="hvr-grow" href="{{ post.url }}">{{ post.title }}</a></h4></li><li>{% endfor %}</li></ul><h2 class="editable trafalgar text-center editable">Recipes</h2><center>&nbsp;</center></div></div><!-- <nav class="filters food">
  <h3 class="great-primer editable" style="display: inline;">Filter by Category:</h3><a href="/food/#allposts">All Posts</a>
  {% for category in site.categories %} [{{ category | first }}](#{{ category | first | remove:' ' }}) {% if forloop.last %} {% else %} {% endif %} {% endfor %}  -->