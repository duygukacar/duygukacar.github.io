---
layout: default
---

<article class="pa3 pb5 pa5-ns">
  <h1 class="f2 f-subheadline-ns mt0 mb4">{{ site.description }}</h1>
  <p class="gray f6 mb4 ttu tracked">By Robert Bringhurst</p>
  <p class="f4 f3-ns measure lh-copy mt0 mb4">
    {{ site.intro }}
  </p>
  <p class="f4 f3-ns measure lh-copy ma0">
    {{ site.bio }}
  </p>
</article>

<article class="cf">
  {% for post in site.posts reversed %}
    <a href="{{ site.baseurl }}{{ post.url }}" class="fl w-50 w-25-l link overflow-hidden">
      <div class="grow aspect-ratio--4x6 pv" style="background: url({{ post.cover }}) no-repeat center center; background-size: cover;"></div>
    </a>
  {% endfor %}
</article>
