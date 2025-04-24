---
layout: default          # any layout that does NOT loop through site.posts
title: "Welcome"
permalink: /
---

<style>
  .container {
    display: flex;
    flex-direction: column;   /* ALWAYS stack image then text */
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
    <img src="{{ site.baseurl }}/assets/dgraeber_assa_2025.jpg"
         alt="Daniel Graeber profile picture">
  </div>

  <div class="text-content">
    <h2>Welcome to my webpage!</h2>

    <p><strong>Google&nbsp;Scholar (September&nbsp;2024):</strong></p>
    <ul>
      <li>Citations: 803</li>
      <li>h-index: 13</li>
      <li>i10-index: 15</li>
    </ul>

    <p>
      I am a postdoctoral researcher in the
      <a href="https://www.diw.de/en/diw_01.c.615551.en/research_infrastructure__socio-economic_panel__soep.html">SOEP</a>
      department at <a href="https://www.diw.de/en">DIW Berlin</a>, as well as a Research Affiliate at
      <a href="https://www.iza.org/de">IZA Bonn</a> and a Senior Member at the
      <a href="https://uni-potsdam.de/en/cepa/welcome-to-cepa">Center for Economic Policy Analysis (CEPA)</a>.
      At the SOEP, my research focuses on well-being. As a behavioral economist, my work primarily explores
      health economics, well-being, and the development of risk preferences. I also have a keen interest in the
      economics of entrepreneurship. My research has been featured in esteemed journals such as
      <em>Entrepreneurship Theory and Practice&nbsp;(IF = 10.5)</em>,
      <em>Journal of Population Economics&nbsp;(IF = 6.5)</em>, and
      <em>PLOS&nbsp;ONE&nbsp;(IF = 3.7)</em>. In 2022, I was honored with an award for one of the best
      publications at DIW Berlin. You can reach me at <code>dgraeber&nbsp;[at]&nbsp;diw&nbsp;[dot]&nbsp;de</code>.
    </p>

    <!-- If you intentionally want the section repeated, keep this copy too;
         otherwise feel free to delete the duplicate block below. -->
    <p><strong>Google&nbsp;Scholar (September&nbsp;2024):</strong></p>
    <ul>
      <li>Citations: 803</li>
      <li>h-index: 13</li>
      <li>i10-index: 15</li>
    </ul>
  </div>
</div>

