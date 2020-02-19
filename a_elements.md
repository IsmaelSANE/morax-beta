---
layout: post
title: Events
description: CORPORATE CONFERENCES - COMMERCIAL PHOTOGRAPHY
nav-menu: true
active: gallery
header-img: "assets/images/event-5.png"
images:
 - image_path: /gallery/albums/alb10.jpg
   gallery-folder: /gallery/gallery10/
   gallery-name: Event 1
   gallery-date: July 2015
 - image_path: /gallery/albums/alb11.jpg
   gallery-folder: /gallery/gallery11/
   gallery-name: Event 2
   gallery-date: June 2015
 - image_path: /gallery/albums/alb12.jpg
   gallery-folder: /gallery/gallery12/
   gallery-name: Event 3
   gallery-date: May 2015
 - image_path: /gallery/albums/alb13.jpg
   gallery-folder: /gallery/gallery13/
   gallery-name: Event 4
   gallery-date: April 2015
 - image_path: /gallery/albums/alb14.jpg
   gallery-folder: /gallery/gallery14/
   gallery-name: Event 5
   gallery-date: March 2015
show_tile: true
---

<html class="no-js" lang="en">
<head>
  <meta content="charset=utf-8">
</head>
    <body class="gallery">

  <section id="content" role="main">
    <div class="wrapper">
      <!-- Gallery __-->
      <div class="gallery masonry-gallery">
{% for image in page.images %}
        <figure class="gallery-item"><figure class="effect-selena">
          <header class='gallery-icon'>
<a href="{{ site.url }}{{ site.baseurl }}{{ image.gallery-folder }}">
<img src="{{ site.url }}{{ site.baseurl }}{{ image.image_path }}"></a>
          </header>
          <figcaption class='gallery-caption'>
            <div class="entry-summary">
              <h3>{{image.gallery-name}}</h3>
              <p>{{image.gallery-date}}</p>
            </div>
          </figcaption>
                       </figure>
        </figure>
{% endfor %}
      </div>
    </div><!-- END .wrapper -->
  </section>

<br>


<!-- jQuery -->

<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="//maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<!-- include image popups -->
<script src="{{ site.baseurl }}/assets/js/jquery.magnific-popup.js"></script>

<script src="{{ site.baseurl }}/assets/js/retina.min.js"></script>
<!-- include Masonry -->
<script src="{{ site.baseurl }}/assets/js/isotope.pkgd.min.js"></script>
<!-- include mousewheel plugins -->
<script src="{{ site.baseurl }}/assets/js/jquery.mousewheel.min.js"></script>
<!-- include carousel plugins -->
<script src="{{ site.baseurl}}/assets/js/jquery.tinycarousel.min.js"></script>
<!-- include svg line drawing plugin -->
<script src="{{ site.baseurl }}/assets/js/jquery.lazylinepainter.min.js"></script>
<!-- include custom script -->
<script src="{{ site.baseurl }}/assets/js/scripts.js"></script>
<!-- Modernizr -->
<script src="{{ site.baseurl }}/assets/js/modernizr.js"></script>

</body></html>
