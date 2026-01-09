---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<section id="about" style="scroll-margin-top: 100px;">
  <p>
    Vasco Ramos is a PhD Researcher in Multimodal AI at NOVA Lisbon and a Scientific Researcher in partnership with Google, where he investigates video generation models for visualizing complex manual tasks. Recognized for his academic excellence as a top graduate, he achieved 1st Place in the Amazon Alexa Prize TaskBot Challenge 2 for developing a multimodal conversational agent. Beyond his research, Vasco actively teaches Deep Learning, NLP, and Computer Vision modules for the CMU Portugal Academy and the Samsung Innovation Campus.
  </p>
</section>

<hr>

<section id="publications" style="scroll-margin-top: 100px;">
  <h2>Publications</h2>
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
</section>

<hr>

<section id="teaching" style="scroll-margin-top: 100px;">
  <h2>Teaching</h2>
  <ul>
    <li>Natural Language Processing, 2025, CMU Portugal Advanced Training Program </li>
    <li>Multimodal Generative AI, 2025, CMU Portugal Advanced Training Program </li>
    <li>Deep Learning, 2024, Samsung Innovation Campus Artificial Intelligence Course </li>
  </ul>
</section>