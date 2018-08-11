---
layout: default
---

<!-- This code loads all posts and displays them -->

<div class="row">
<div class="span1">
	<ul>
	  {% for post in site.posts %}
	    <li>
	      {% assign content = post.content %}
	      {% include post_detail.html %}
	    </li>
	  {% endfor %}
	</ul>
</div>	

<div class="span2">
	<ul>
	  {% for post in site.posts %}
	    <li>
	      <a href="{{ post.url }}">{{ post.title }}</a>
	    </li>
	  {% endfor %}
	</ul>
</div>	
</div>
