---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}


 My researches are mainly around developing <b> adaptive and scalable </b> algorithms for the control and optimization of large-scale dynamic networked systems arising from smart buildings, smart grids and cyber physical systems. 
My researches have stretched various theories and techniques, in particular,  
  <p><ul>
    <li> <p>Decentralize convex or nonconvex optimization, decentralized decision-making </p></li>
    <li> <p> Event-based optimization </p></li>
    <li> <p> Stochastic optimization, Markov decision process, reinforcement learning </p></li>
    <li> <p> Data-driven analysis and control. </p></li>
    </ul>
</p>
 I also have strong interest in <b>game theory (noncooperative game, coalition game), transactive energy or transactive control and market design mechanisms </b>with their application to build a flexible, adaptive, reliable and sustainable energy system.
 
 I am also interested in developing or enhancing basic theories from research topics and exploring their extensions to other areas. 

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

