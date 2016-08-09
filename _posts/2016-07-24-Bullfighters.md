---
published: true
layout: post
type: photograph
origin: American
year: 1995
artists:
  - url: /artists/Herzog_Lena.md
images:
  - url: /images/LH_Bullfight3.jpg
---

<div class ="main-image">
{% for image in page.images %}
<img src="{{ site.baseurl }}{{ image.url }}" class="">
<br>
<hr>
<br>
{% endfor %}
</div>

This photo, shot using a Hasselblad x-pan engages us through it's classical composition and dramatic use of light. The matadors, as they prepare for entering the arena, display a contradiction of brutality and refinement...courage and fear... elegance and cruelty. The gaze of the third figure engages the viewer, arresting our attention away from the beauty of the photo and clueing us in on the interior emotion of the moment.

In this interview by Robert Harris from <a href= "http://french-italian.stanford.edu/opinions/shows/eo10156.mp3">"Entitled Opinions"</a> Herzog talks about her process, why she shoots on film, and about her other projects and her career in general.

<hr>

<div class="artist-info">
{% for artist in site.artists %}
<a href="{{ site.baseurl }}{{ site.artists.url }}"><h2>{{ artist.name }}</h2></a>
<p>{{ artist.dates }}</p>
<p><span>MOVEMENT:</span>{{ artist.movement }}</p>
<p><span>WEBSITE:</span>{{ artist.website }}</p>
<p><span>BIO:</span>{{ artist.bio }}</p>
<hr>
{% endfor %}

  </div>