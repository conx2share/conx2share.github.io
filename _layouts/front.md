---
layout: default
---
{% include carousel.html %}
<h2 class="text-center">{{ site.data.front['vision'] }}</h2>
<div class="container">
  <div class="row">
    <div class="col-md-6"><h2>{{ site.data.front['mission'] }}</h2></div>
    <div class="col-md-6"><h2>{{ site.data.front['corporate_statement'] }}</h2></div>
  </div>
</div>
{{ content }}
{% include video.html %}
