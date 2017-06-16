---
layout: page
hero-title: FITNESS
permalink: /fitness/
hero_image_path: /images/fitness.jpg
lead-in: 'Thoughts on Workouts, Fitness Misconceptions, and Exercise Programs'
bg-position: center
---

<div class="container default">
  <h2 class="editable trafalgar text-center editable">Studio Reviews</h2>
  <div blog-gallery="many">
    <ul>  
    {% for post in site.categories.fitness %}
      <a href="{{ post.url }}" class="hvr-grow"><li class="fitness invert">
      <div class="preview" style="background-position: center {{ post.image-position }}; background-image: url('{{ post.main_image_path }}')">
      </div>
        <h4 class="pica">{{ post.title }}</h4>
        <i class="fa fa-chevron-right" aria-hidden="true"></i>
      </li>
      </a>
    {% endfor %}
    </ul>
  <div class="container default">
  <h2 class="editable trafalgar text-center editable">At Home / Gym Workouts</h2>
  <div blog-gallery="many">
  </div>
</div>
