---
title: 3. The Head Element
module: topic-03
permalink: /topic-03/head-element/
tags: document, head, html, title
---

<div class="divider-heading"></div>

The **head element** is a container for processing information and document metadata. This will include elements that may link to other files, hold the author information, and pass the name of the page to the processor. The `<head>` contains high-level information about the site, and always comes first within the root element.

In many aspects, the contents are not visible to site visitors. Rather, the `<head>` contains information for indexing the site, like for search results. Certain elements in the `<head>` can also help dictate how the page will visibly look. In this sense, we can consider the `<head>` to contain the thoughts of the page.

The **title element** lives within the head, and states the title of the page. This is the wording that appears on the browser tab for that page.

<span class="label label-danger">Important</span> The `<title>` tag is the only **required** element within the `<head>`, and aptly contains your site's or page's title.


<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Way-Cool Awesome Site</title>
    <!-- Meta data and information about your site, not visible to visitors. -->
  </head>

</html>
```
