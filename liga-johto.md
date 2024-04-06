---
title: LIGA JOTHO
permalink: /liga-jotho/
layout: page
---


<div class="content">
<div class="card_res">
 <p class="title">NORTE</p>
   {%- for post in site.categories.nortejohto042024 -%}
   <a href="{{ post.url }}">
    <div class="user">
      <div class="image"></div>
       <div class="user__content">
        <div class="text">
          <span class="name">{{post.team}}</span>
          <p class="username">{{post.abr}}</p>
        </div>
        <button class="follow">{{post.puntosLJ202404}} pts</button>
      </div>
    </div>
    </a>
    {%- endfor -%}
    </div>
  


<div class="card_res">
 <p class="title">SUR</p>
{%- for post in site.categories.surjohto042024  -%}
  <a href="{{ post.url }}">
    <div class="user">
      <div class="image"></div>
       <div class="user__content">
        <div class="text">
          <span class="name">{{post.team}}</span>
          <p class="username">{{post.abr}}</p>
        </div>
        <button class="follow">{{post.puntosLJ202404}} pts</button>
      </div>
    </div>
    </a>
{%- endfor -%}
</div>

   
</div>








