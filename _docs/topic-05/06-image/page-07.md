---
title: 4. Title
module: topic-05
permalink: /topic-05/img-title/
tags: attribute, image, title
---

<div class="divider-heading"></div>


<div id="code-heading">Element Breakdown <i class="fas fa-battery-three-quarters"></i></div>
<pre id="breakdown-block">
<img src="#" alt="" <span class="pulsate">title=""</span> width="" height="" />
</pre>


As with the alt text attribute, you should also get in the habit of always including a **title attribute**, which is `title=""`. Most browsers will display this text as a tooltip when a user hovers their mouse over am image with the included attribute.

<span class="label label-success">Neat-O</span> The alt and/or title attributes will also be used by some browsers in the case where the image itself cannot load.

<img src="" alt="You are seeing the alternative text of this image. Hover your cursor over this broken image to see its title popup." title="I am the title!" style="width: 300px; height: 150px; border: 1px solid #AEA79F"/>
