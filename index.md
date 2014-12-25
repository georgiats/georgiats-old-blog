---
layout: page
title: Hi there, I am Georgia :)
tagline: Welcome to my page
---
{% include JB/setup %}

My name is Georgia and I am Mathematicial, Computer Scientist and Open Data enthusiast. 


I work in IT and I spend my time among my job, my Masters studies and some tech-meetups all around Thessaloniki. 

[SKGTech](www.skgtech.io) is a great place to get informed about lots of great tech events in the town, and I am happy to contribute to that project. 

I am also a coordinator in our team [OpenThessaloniki](http://www.openthessaloniki.org), which aims to spread the usage of Open Data in every aspect of public life. 
    
### My posts (both in Greek and English)

<ul class="posts">
  {% for post in site.posts %}
    <li><h4><span>Category: {{ post.categories }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h4></li>
  {% endfor %}
</ul>

