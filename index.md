---
layout: page
title:  Greek Open Data Index
tagline: Greek Open Data
tags : 
---
{% include JB/setup %}
[OpenThessaloniki](http://www.openthessaloniki.org) aims to spread the usage of Open Data in every aspect of public life. 
    
### Our available lists 

Here can be found lists of greek sites, that are related to Open Data

<table class="table-striped table-bordered">
  		{% for post in site.posts %}
    		<tr>
    			<th><h4><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h4></th>
				<td> {{ post.description }}</a></td>
			</tr>
   		{% endfor %}
</table>