---
layout: default
title: Past Editions
permalink: /past/
feature-img: "assets/img/pexels/laptop.jpg"
tags: [Archive]
---


<div class="home">

  <div id="main" class="call-out"
       style="background-image: url('{{ page.feature-img | relative_url }}')">
    <h1> Past Editions </h1>
  </div>

  {% include blog.html filterBy="edition" %}

</div>
