---
permalink: /
title: "👋About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br />
　　I am a Ph.D. candidate in the School of Software Engineering at South China University of Technology, advised by Associate Prof. [Mingkui Tan](https://tanmingkui.github.io/) and Prof. [Chuang Gan](https://people.csail.mit.edu/ganchuang/).
   
    My primary research interests are in <b>Visual Understanding</b> and mainly focus on:
    * <b>Video Understanding<\b>: self-supervised video representation learning, temporal action localization;
    * <b>Embodied AI<\b>: vision-and-language navigation;



# 🗞️News
<div style="overflow-y: scroll; height: 295px;">
  <ul>
    <li>2023.02: Our paper is accepted by <b>CVPR 2023</b>.</li>
    <li>2022.11: Two NeurIPS 2022 papers are selected as <b>Spotlight</b>.</li>
    <li>2022.10: Two papers are accepted by <b>NeurIPS 2022</b>.</li>
  </ul>
</div>
<br>


Conferences
----------
<div>
  <table>
  {% for post in site.conferences_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
  <a href="/conferences/">
    <!-- <button class="btn btn--readmore">Read more <font size="1">>></font></button> -->
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


Journals
----------
<div>
  <table>
  {% for post in site.journals_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
   <a href="/journals/">
    <!-- <button class="btn btn--readmore">Read more <font size="1">>></font></button> -->
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


<!-- Preprint Paper
----------
<div>
  <table>
  {% for post in site.preprints reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div> -->

