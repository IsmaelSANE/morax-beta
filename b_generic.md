---
layout: post
title: Gallery
description: HEADSHOT CREATIVE CORPORATE WEDDINGS LONDON SHOOT
image: /assets/images/gallery.png
nav-menu: true
active: gallery
header-img: "assets/images/etienne.jpg"
images:
 - image_path: /gallery/albums/alb01.png
   gallery-folder: /gallery/gallery01/
   gallery-name: Corporate
   gallery-date: July 2015
 - image_path: /gallery/albums/alb02.png
   gallery-folder: /gallery/gallery02/
   gallery-name: Portrait Life-style
   gallery-date: June 2015
 - image_path: /gallery/albums/alb03.png
   gallery-folder: /gallery/gallery03/
   gallery-name: Women fashion
   gallery-date: May 2015
 - image_path: /gallery/albums/alb04.png
   gallery-folder: /gallery/gallery04/
   gallery-name: Weddings
   gallery-date: April 2015
 - image_path: /gallery/albums/alb05.png
   gallery-folder: /gallery/gallery05/
   gallery-name: Men fashion
   gallery-date: March 2015
 - image_path: /gallery/albums/alb06.png
   gallery-folder: /gallery/gallery06/
   gallery-name: Studio creatif
   gallery-date: February 2015
 - image_path: /gallery/albums/alb07.png
   gallery-folder: /gallery/gallery07/
   gallery-name: Family
   gallery-date: January 2015
 - image_path: /gallery/albums/alb08.png
   gallery-folder: /gallery/gallery08/
   gallery-name: Headshoots
   gallery-date: December 2014
 - image_path: /gallery/albums/alb09.png
   gallery-folder: /gallery/gallery09/
   gallery-name: Food
   gallery-date: November 2014
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
<script src="{{ site.baseurl }}assets/js/jquery.magnific-popup.js"></script>

<script src="{{ site.baseurl }}assets/js/retina.min.js"></script>
<!-- include Masonry -->
<script src="{{ site.baseurl }}assets/js/isotope.pkgd.min.js"></script>
<!-- include mousewheel plugins -->
<script src="{{ site.baseurl }}assets/js/jquery.mousewheel.min.js"></script>
<!-- include carousel plugins -->
<script src="{{ site.baseurl}}assets/js/jquery.tinycarousel.min.js"></script>
<!-- include svg line drawing plugin -->
<script src="{{ site.baseurl }}assets/js/jquery.lazylinepainter.min.js"></script>
<!-- include custom script -->
<script src="{{ site.baseurl }}assets/js/scripts.js"></script>
<!-- Modernizr -->
<script src="{{ site.baseurl }}assets/js/modernizr.js"></script>

</body></html>
