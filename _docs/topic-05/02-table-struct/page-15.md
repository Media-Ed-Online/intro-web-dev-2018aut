---
title: 2. Rows
module: topic-05
permalink: /topic-05/table-rows/
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


<div id="code-heading">Element Breakdown <i class="fas fa-battery-quarter"></i></div>
<pre id="breakdown-block">
&lt;table&gt;
  <span class="pulsate">&lt;tr&gt;</span>
    &lt;th&gt;&lt;/th&gt;
    &lt;th scope="col"&gt;Column A&lt;/th&gt;
  <span class="pulsate">&lt;/tr&gt;</span>
  <span class="pulsate">&lt;tr&gt;</span>
    &lt;th scope="row"&gt;Row 1&lt;/th&gt;
    &lt;td&gt;Cell A1&lt;/td&gt;
  <span class="pulsate">&lt;/tr&gt;</span>
&lt;/table&gt;
</pre>


**Table rows** are created using the `<tr>...</tr>` element. Inside of a `<tr>` lives the individual cells (equal to the number of columns), each referenced using a set of `<td>` tags.
