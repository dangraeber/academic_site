---
layout: default          # any layout that does NOT loop through site.posts
title: "Welcome"
permalink: /
---

<style>
  .container {
    display: flex;
    flex-direction: column;   /* Stack image then text */
    align-items: center;
    gap: 1.5rem;
    max-width: 60rem;
    margin: 0 auto;
  }

  .container img {
    max-width: 100%;
    height: auto;
  }

  .text-content {
    text-align: justify;
    width: 100%;
  }
</style>

<div class="container">
  <div>
    <img src="{{ site.baseurl }}/assets/profile_edited.png"
         alt="Daniel Graeber profile picture">
  </div>

  <div class="text-content">
    <h2>Welcome!</h2>

<p>I am:</p>
<ul>
  <li>Postdoctoral Researcher in the 
    <a href="https://www.diw.de/en/diw_01.c.615551.en/research_infrastructure__socio-economic_panel__soep.html">SOEP</a> 
    department at <a href="https://www.diw.de/en">DIW Berlin</a>
  </li>
  <li>Research Affiliate at <a href="https://www.iza.org/de">IZA Bonn</a></li>
  <li>Senior Member at the 
    <a href="https://uni-potsdam.de/en/cepa/welcome-to-cepa">Center for Economic Policy Analysis (CEPA)</a>
  </li>
</ul>


    <p>
      My research focuses on well-being, health economics, and risk preferences.
    </p>

    <p>
      You can reach me at <code>dgraeber&nbsp;[at]&nbsp;diw&nbsp;[dot]&nbsp;de</code>.
    </p>

    <p><strong>Google Scholar (September&nbsp;2025):</strong></p>
    <ul>
      <li>Citations: 9961</li>
      <li>h-index: 14</li>
      <li>i10-index: 16</li>
    </ul>
  </div>
</div>
