---
layout: page
show_meta: false
title: "My works"
subheadline: "collection"
header:
   image_fullwidth: "01.jpg"
permalink: "/works/"
---
<ul>
    {% for post in site.categories.works %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>