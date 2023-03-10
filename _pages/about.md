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
　　I am a Ph.D. candidate with the School of Software Engineering at South China University of Technology. I also received my bachelor degree in the School of Automation Science and Engineering from the same university in 2018. My research interests include multimedia understanding and embodied AI. 
<!-- I served as the reviewer for several top-tier journals and conferences, such as TIP, TNNLS, NeurIPS, AAAI, UAI, MICCAI. -->


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

