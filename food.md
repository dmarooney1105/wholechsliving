---
layout: page
hero-title: Food
permalink: /food/
hero_image_path: /images/food.jpg
lead-in: Thoughts on Nutrition, Recipes, Program Reviews, Diets
bg-position: center
---

<div class="container default">
  <h2 class="editable trafalgar text-center editable">Title Goes Here or Delete if You don't Think You Need one</h2>
  <center>
  </center>
  <div blog-gallery="many">
    <!-- <h2 class="editable double-pica text-center editable" style="margin: 30px;">All Posts</h2> -->
    <ul>  
      {% for post in site.categories.food %}
        <a href="{{ post.url }}" class="hvr-grow"><li class="food invert">
        <div class="preview" style="background-position: center {{ post.image-position }}; background-image: url('{{ post.main_image_path }}')">
        </div>
          <h4 class="pica">{{ post.title }}</h4>
          <i class="fa fa-chevron-right" aria-hidden="true"></i>
        </li>
        </a>
      {% endfor %}
    </ul>

  </div>
</div>

<!-- <nav class="filters food">
  <h3 class="great-primer editable" style="display: inline;">Filter by Category:</h3><a href="/food/#allposts">All Posts</a>
  {% for category in site.categories %}
      <a href="#{{ category | first | remove:' ' }}">{{ category | first }}</a> {% if forloop.last %} {% else %} {% endif %}
  {% endfor %}
</nav> -->
