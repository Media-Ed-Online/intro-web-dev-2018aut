---
title: Extra Markup
module: topic-05
permalink: /topic-05/extra-markup/
categories: html
tags: elements, markup, page, structure, naming
---

<div class="divider-heading"></div>

Up to this point, we've added HTML elements to pages singularly, in that they really had no defined groupings. But most pages are built on “blocks” of content placed in relation to each other.

Consider the file “**gallery.html**,” found on your website:

<img src="../img/gallery-page.png" alt="simple gallery page" style="width: 200px;" />

This page has 4 defined areas that display different content based on their type:
1. image
2. video
3. audio
4. social media sharing button for visitors to use

Within each of these ares there is a section for files, a slider (or scrollable gallery) to present those files interactively, and a decorative illustration.

These sections, or _divisions_, help us control how content looks en masse, rather than element-by-element. This will become more apparent as we go on.


<div class="divider-pg"></div>


To describe the examples you've been seeing, elements on these pages work much like building “blocks” - separate bricks that come together to create the structure of the page.

<img src="../img/gallery-page-to-blocks.gif" alt="page breaking into blocks" style="width: 300px;" />

These elements are primarily given two distinctions; **block-level elements** take up the full-width of the page, while **inline elements** do not cause line breaks and can neighbor each other naturally.


## Block-Level Elements

Block elements appear on their own block on a new line. Each of these (unless told otherwise through styling) appears on a new line in HTML pages. Some block elements are:

- Headings `<h1>`-`<h6>`
- Paragraphs `<p>`
- Lists `<ol>`, `<ul>`
- Horizontal rules `<hr>`

In the example above, a new type of block-level element was used (the `<div>`) to section-off a row for each media gallery, which altogether fills the page edge-to-edge.


## Inline Elements

Inline elements are not automatically given additional area on the page outside of their contents. Essentially, these means inline elements can be adjacent, rather than atop or below each other. Some inline elements are:

- Images `<img>`
- Semantic elements `<em>`, `<b>`, etc.
- Links `<a>`

In the example above, a new type of inline element was used (the `<span>`) to create the slider. Since `<img>` is also an inline element, the illustration can sit on the same block.
