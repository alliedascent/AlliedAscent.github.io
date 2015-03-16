---
layout: home
excerpt: "A minimal Jekyll theme for your blog by designer Michael Rose."
tags: [Jekyll, theme, responsive, blog, template]
author: AlliedAscent
image:
  feature: sample-image-1.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---


Welcome to Allied Ascent. 


<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

