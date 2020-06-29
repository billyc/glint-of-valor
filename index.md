---
layout: default
---

Good day! Here are a few ramblings from our merry band of explorers! Follow along while we discover the secrets of Saltmarsh!

# Latest entries

---

<div class="posts">

{% for post in site.posts %}

  <div class="post">

    <div class="teaser">
      <h2 class="post-title">
        <a href="{{ site.baseurl }}{{ post.url }}"> {{ post.title }} </a>
      </h2>
    </div>

    <div class="index-thumbnail">
      {% if post.thumbnail %}
      <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ post.url }}">
          <img class="post-thumbnail" src="{{ post.thumbnail }}" />
        </a>
      </div>
      {% endif %}
    </div>

    <div class="index-blurb">
      <div class="entry">
        <a class="excerpt" href="{{ site.baseurl }}{{ post.url }}">
          {{ post.excerpt }}
        </a>
      </div>
      <div>
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more"
          >More&hellip;</a
        >
      </div>
    </div>

  </div>
  {% endfor %}
</div>
