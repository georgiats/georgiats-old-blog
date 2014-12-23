---
layout: page
title: Hi there! I am Georgia :)
tagline: 
---
{% include JB/setup %}

My name is Georgia and I am Mathematicial, Computer Scientist and Open Data enthusiast. 

I work in IT and I spend my time among my job, my Masters studies and some tech-meetups all around Thessaloniki. 

[SKGTech](www.skgtech.io) is a great place to get informed about lots of great tech events in the town, and I am happy to contribute to that project. 

I am also a coordinator in our team [OpenThessaloniki](http://www.openthessaloniki.org), which aims to spread the usage of Open Data in every aspect of public life. 
    
## My posts (both in Greek and English)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


## Where to find me
<ul>
  <li class="github"><a href="http://github.com/{{ site.author.github }}/" rel="me">github</a></li>
  <li class="twitter"><a href="http://twitter.com/{{ site.author.twitter }}/" rel="me">twitter</a></li> 
  <li><a href="http://gr.linkedin.com/in/gtsiamanta">LinkedIn</a><span class="glyphicon social-18-linked-in" aria-hidden="true"></span>
</ul>