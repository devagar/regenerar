---
layout: cdefault
title: Curso de Chi Kung no IMP
---
<div class='post'>
    <div class='body'>
   {% for post in site.posts limit:1 %}
      	<h2>{{post.title}}</h2>
      	{{ post.content }}
    {% endfor %}
    </div>
</div>


