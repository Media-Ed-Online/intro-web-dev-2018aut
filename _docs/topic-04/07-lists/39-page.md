---
title: Unordered
module: topic-04
permalink: /topic-04/unordered-lists/
tags: html, list, unordered
---

<div class="divider-heading"></div>

**Unordered lists** are those that which begin with dots, bullets, dashes, or other visual signifiers. These lists are great for things like ingredients in a recipe. Unordered lists, by default, get a dot in most browsers.

<table style="width: 75%; margin: auto;">
<tbody>
  <tr>
    <td style="border: none;">
      <ul style="list-style-type:disc">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ul>
    </td>
    <td style="border: none;">
      <ul style="list-style-type:square">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ul>
    </td>
    <td style="border: none;">
      <ul style="list-style-type:circle">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ul>
    </td>
  </tr>
</tbody>
</table>


To identify an unordered list, the content is contained within the unordered list tags ( `<ul>...</ul>` ).

As with the ordered list, each list item is contained within a list item element ( `<li>...</li>` ).


<div id="code-heading">HTML</div>
```html
<ul>
  <li>List Item</li>
  <li>List Item</li>
  <li>Etc...</li>
<ul>
```


<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="rJzvWg" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Unordered Lists" class="codepen"></p>
</div>
