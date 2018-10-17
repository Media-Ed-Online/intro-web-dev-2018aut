---
title: 4. Headings
module: topic-05
permalink: /topic-05/table-headings/
tags: elements, html, table
---

<style>
  .indent-sm {
    margin-left: 20px;
    display: block;
  }
  .indent-lg {
    margin-left: 40px;
    display: block;
  }
</style>

<div class="divider-heading"></div>


<div id="code-heading">Element Breakdown <i class="fas fa-battery-full"></i></div>
<pre id="breakdown-block">
&lt;table&gt;
  &lt;tr&gt;
    <span class="pulsate">&lt;th&gt;&lt;/th&gt;</span>
    <span class="pulsate">&lt;th scope="col"&gt;</span>Column A<span class="pulsate">&lt;/th&gt;</span>
  &lt;/tr&gt;
  &lt;tr&gt;
    <span class="pulsate">&lt;th scope="row"&gt;</span>Row 1<span class="pulsate">&lt;/th&gt;</span>
    &lt;td&gt;Cell A1&lt;/td&gt;
  &lt;/tr&gt;
&lt;/table&gt;
</pre>


You should use **table headings** or `<th>` elements to provide structure and style to head your columns and rows. This is incredibly helpful for people who use screen readers, and helps search engines to correctly index your page.

We delineate columns and rows using the `scope=""` attribute; a column is headed using `<th scope="col">...</th>` and a row is headed using `<th scope="row">...</th>`

<span class="label label-danger">Important</span> Empty cells are not forgotten cells -  they still need to be created using `<th>` or `<td>` elements. Not including these elements will cause your table to improperly render.
