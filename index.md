---
layout: page
title: Hi there, I am Georgia :)
tagline: Connect with me
---
{% include JB/setup %}

My name is Georgia Tsiamanta and I am Mathematician, Computer Scientist and Open Data enthusiast. 


I work in IT and I spend my time among my job, my Master's studies and some tech meetups all around Thessaloniki. 

[SKGTech](http://www.skgtech.io) is a great place to get informed about lots of great tech events in the town, and I am happy to contribute to that project. 

I am also a coordinator in our team [OpenThessaloniki](http://www.openthessaloniki.org), which aims to spread the usage of Open Data in every aspect of public life. 
    
### My posts 

Here can be found lists of greek sites, that are related to Open Data  

<ul class="posts">
  {% for post in site.posts %}
    <li><h4><span>Category: {{ post.categories }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h4></li>
  {% endfor %}
</ul>

