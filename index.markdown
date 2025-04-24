---
layout: default          # use any layout that does NOT loop through site.posts
title: "Welcome"
permalink: /              # keep the page at the site root
---

<style>
  .container {
    display: flex;
    flex-direction: column;         /* stack image over text on narrow screens   */
    align-items: center;
    gap: 1.5rem;
    max-width: 60rem;               /* avoid very wide lines                     */
    margin: 0 auto;                 /* center the whole block                    */
  }

  .container img {
    max-width: 100%;
    height: auto;
  }

  .text-content {
    text-align: justify;
    width: 100%;
  }

  @media (min-width: 700px) {
    .container {
      flex-direction: row;          /* put image and text side-by-side on wide   */
    }
    .text-content { width: 60%; }
  }
</style>

<div class="container">
  <div>
    <img src="{{ site.baseurl }}/assets/dgraeber_assa_2025.jpg"
         alt="Daniel Graeber profile picture">
  </div>

  <div class="text-content">
    <h2>Welcome to my webpage 👋</h2>

    <p><strong>Google&nbsp;Scholar (September&nbsp;2024)</strong></p>
    <ul>
      <li>Citations: 803</li>
      <li>h-index: 13</li>
      <li>i10-index: 15</li>
    </ul>

    <p>
      I am a post-doctoral researcher in the
      <a href="https://www.diw.de/en/diw_01.c.615551.en/research_infrastructure__socio-economic_panel__soep.html">SOEP</a>
      department at <a href="https://www.diw.de/en">DIW Berlin</a>, a Research Affiliate at
      <a href="https://www.iza.org/de">IZA Bonn</a>, and a Senior Member of the
      <a href="https://uni-potsdam.de/en/cepa/welcome-to-cepa">Center for Economic Policy Analysis&nbsp;(CEPA)</a>.
      My research spans well-being, health economics, and the development of risk preferences, with a growing
      interest in the economics of entrepreneurship. It has appeared in
      <em>Entrepreneurship Theory & Practice</em>,
      <em>Journal of Population Economics</em>, and <em>PLOS ONE</em>.
      In 2022 I received DIW Berlin’s award for one of the best publications.
      Feel free to reach me at <code>dgraeber&nbsp;[at]&nbsp;diw&nbsp;[dot]&nbsp;de</code>.
    </p>
  </div>
</div>

