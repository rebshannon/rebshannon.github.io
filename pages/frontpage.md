---
layout: default
format: frontpage
show_meta: false
#title: "Research"
subheadline: "Layouts of Feeling Responsive"
header: 
   image_fullwidth: "header_unsplash_5.jpg"
   title: "Rebecca Shannon"

---
<ul>
    {% for page in site.categories.research %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endfor %}
</ul>