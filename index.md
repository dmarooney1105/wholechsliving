---
layout: page
hero_image_path: "/images/backgrounds/franimage.jpg"
hero-title: Whole Charleston Living
lead-in: Finding a wholesome & healthy life in Charleston, SC.
bg-position: center
---

<div class="container default">
<h2 class="editable trafalgar text-center">Latest Posts</h2>
  <div post-gallery>
    <ul style="padding: 0px;">
      <center>
      <!-- {% assign sorted_posts = (site.posts | sort: 'date') | reverse %} -->
      {% for post in sorted_posts limit:2 %}
        <li class="post-card">
          <div class="headline">
            <span class="listed_category">{{ post.category }}</span><br>
            <span class="great-primer">{{ post.title }}</span>
            <hr>
            <span class="long-primer">{{ post.excerpt }}</span>
            <a href="{{ post.url }}" class="generic">Read More</a>
          </div>
          <div class="preview" style="background-position: center {{ post.image-position }}; background-image: url('{{ post.main_image_path }}');">
          </div>
        </li>
      {% endfor %}
      </center>
    </ul>
  </div>
</div>
<div class="container default differentiate">
  <h2 class="editable trafalgar text-center">#WholeCHSLiving</h2>
  <!-- LightWidget WIDGET --><script src="//lightwidget.com/widgets/lightwidget.js"></script><iframe src="//lightwidget.com/widgets/6cddb77c85a8500a999353a922c58b59.html" scrolling="no" allowtransparency="true" class="lightwidget-widget" style="width: 100%; border: 0; overflow: hidden;"></iframe>
</div>
