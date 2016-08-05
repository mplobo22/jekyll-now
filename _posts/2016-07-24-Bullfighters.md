---
published: true
layout: post
type: photograph
origin: American
year: 1995
artist:
  - url: /artists/Herzog_Lena.md
images:
  - url: /images/herzog/LH_Bullfight2.jpg
---
{% for image in page.images %}
<img src="{{ site.baseurl }}{{ image.url }}" class="">
{% endfor %}

## Lena Herzog
Lena Herzog's iconic images of bullfighters display bla bla bla bla bla

:-)


<div class="artist-info">
{% for artist in site.artists %}
<a href="{{ site.baseurl }}{{ artist.url }}"><h2>{{ artist.name }}</h2></a>
<p>{{ artist.medium }}</p>
<hr>
{% endfor %}

  </div>
