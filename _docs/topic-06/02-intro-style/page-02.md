---
title: The Style Element
module: topic-06
permalink: /topic-06/basic-style-element/
categories: html
tags: elements, style
---

<div class="divider-heading"></div>

To continue our review, let's revisit the **style element**, located in the `<head>` of an HTML document.

_Remember?_ The style element allows for simple style definitions to be established in a single HTML page without having to link to external documents.

<span class="label label-info">NOTE:</span> The **benefit** of styling this way is it can all be done in a single document. The **problem** with styling this way is you will have to manually add or copy any branded styling you want to each individual page of the site.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Way-Cool Awesome Site</title>
    <style>
      body {background-color: snow}
      h1 {color: purple}
    </style>
  </head>

</html>
```
