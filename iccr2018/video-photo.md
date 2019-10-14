---
layout: iccr2018
title: ICCR2018 Videos and photos
---

### Invited talks and best paper award


<div class="row">
  <div class="col-lg-6 col-md-8 col-xs-10 thumb">
    <iframe
      width="400"
      height="250"
      src="https://www.youtube.com/embed/RIM1gIqajzM"
      frameborder="0"
      allowfullscreen
    ></iframe>
  </div>
  <div class="col-lg-6 col-md-8 col-xs-10 thumb">
    <iframe
      width="400"
      height="250"
      src="https://www.youtube.com/embed/uT6ZyAbKGR8"
      frameborder="0"
      allowfullscreen
    ></iframe>
  </div>
  <div class="col-lg-6 col-md-8 col-xs-10 thumb">
    <iframe
      width="400"
      height="250"
      src="https://www.youtube.com/embed/_uKLLDTwmsY"
      frameborder="0"
      allowfullscreen
    ></iframe>
  </div>
  <div class="col-lg-6 col-md-8 col-xs-10 thumb">
    <iframe
      width="400"
      height="250"
      src="https://www.youtube.com/embed/RSbtd2R16Ig"
      frameborder="0"
      allowfullscreen
    ></iframe>
  </div>
</div>

<hr class="featurette-divider" />

### Photos

<div class="row">
  {% for image in site.static_files %} {% if image.path contains
  'images/2018/photos' %}
  <div class="col-lg-6 col-md-8 col-xs-10 thumb">
    <a class="thumbnail" href="#">
      <img
        class="img-fluid"
        src="{{ site.baseurl }}{{ image.path }}"
        alt="image"
    /></a>
  </div>
  {% endif %} {% endfor %}
</div>
