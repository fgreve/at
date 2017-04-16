---
layout: default
title: Fernando Greve
subtitle: Economist and engineer
---

# Fernando Greve

I am an **Economist** at the [Chile Productivity Commission (CNP)](http://www.comisiondeproductividad.cl/); and Co-Editor of [Revista Estudios Públicos (CEP)](https://www.cepchile.cl/).

### My work at the Productivity Comission

• My work at the CNP has three main focus. First, I am responsable of the supervision and development of the **Anual Productivity Report** (See the 2016 Report [Here](http://www.comisiondeproductividad.cl/wp-content/uploads/2017/01/CNP-ANUAL-2016-FINAL-.pdf)).  

• Second, I carry out research, studies and technical notes related to the development of evidence-based (and theoretical) policy aiming to achieve long-term productivity growth for Chile. 

• Third, I am responsable of representing CNP in projects and research studies mandated by the CNP. These projects and research studies are mainly accomplished by faculties and universities, research centers, think tanks, public and private corporations, consultants and private companies.

# Recent Posts

<ul class="well">
  {% for post in site.categories.blog limit:1 %}

      <h2>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>

      <span class="text-warning">{{ post.date | date: "%b %-d, %Y" }}</span>

      <p>{{ post.content | strip_html | truncatewords:75}}</p>
      
      <a href="{{ post.url | prepend: site.baseurl }}">Read more...</a><br>

  {% endfor %}
</ul>


