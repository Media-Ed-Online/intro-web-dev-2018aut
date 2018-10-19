---
title: 3. Alternative Text
module: topic-05
permalink: /topic-05/img-alt/
tags: alt, attribute, best&nbsp;practice, image, required, text
---

<div class="divider-heading"></div>


<div id="code-heading">Element Breakdown <i class="fas fa-battery-half"></i></div>
<pre id="breakdown-block">
<img src="#" <span class="pulsate">alt=""</span> title="" width="" height="" />
</pre>


<span class="label label-danger">Important</span> This attribute is <b>required</b> in the element.

Proper style and accessibility standards dictate that you must always include the **alternative text attribute**. The key for this is simply `alt=""`. The value in the double quotes should describe the image. This description is used by screen readers for those who are visually impaired.

Therefore it is critical that you provide a detailed description, especially in the case where the image is necessary to understand the content of the page.

<ul style="list-style-type: none">
  <li class="icon-con"> Poor: &nbsp;&nbsp;&nbsp;<code>alt="Me getting help"</code></li>
  <li class="icon-pro"> Better: &nbsp;<code>alt="Justine receiving help from an instructor while at a computer"</code></li>
</ul>
