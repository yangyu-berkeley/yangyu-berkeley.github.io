---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}


During my Ph.D. study and my first career as a research fellow, I have mainly focused on developing adaptive and scalable control methods for large-scale dynamic networked systems, such as smart buildings, smart grids and cyber physical systems. 
My research topics have stretched the following areas:

  <p><ul>
    <li> <p>Decentralize or distributed convex or nonconvex optimization, decentralized decision-making </p></li>
    <li> <p> Event-based optimization </p></li>
    <li> <p> Stochastic optimization, Markov decision process, reinforcement learning </p></li>
    <li> <p> Data-driven analysis and control of complex dynamic systems. </p></li>
    </ul>
</p>
      I also have strong interest in game theory (noncooperative game, coalition game), transactive energy or transactive control, and market design for future deregulated energy market. I'm also open to new theories and always looking for exciting research problems.

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

