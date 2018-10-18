---
title: Tables in HTML
module: topic-05
permalink: /topic-05/table-about/
tags: elements, html, table
---

<style>
  table, th, td {
    border: 1px solid #ddd;
  }
</style>


<div class="divider-heading"></div>

**Tables** are used to represent relationships and complex data, such as scores and stats, money markets, databases, etc.

The example on the following pages will show this situation, using a simple 2x2 set-up ("2 rows by 2 columns"):


<table style="width: 200px; margin: 40px auto;">
   <tr>
      <th></th>
      <th scope="col">Column A</th>
   </tr>
   <tr>
      <th scope="row">Row 1</th>
      <td>Cell A1</td>
   </tr>
</table>
