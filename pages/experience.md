---
layout: page
show_meta: false
title: "Experience"
subheadline: "Non-research related work experience"
header: no
 #  image_fullwidth: "header_unsplash_5.jpg"
 #  title: "Rebecca Shannon"
permalink: "/experience/"
---
<ul>
    {% for page in site.categories.experience %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endfor %}
</ul>