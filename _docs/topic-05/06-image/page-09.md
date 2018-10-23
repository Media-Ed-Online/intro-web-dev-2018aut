---
title: Formats and Browser Support
module: topic-05
permalink: /topic-05/img-support/
categories: html
tags: alt, best-practice, browser, image, support, title
---

<div class="divider-heading"></div>

Most image filetypes can be loaded by all browsers without error, but it's always a good idea to have a fallback should images not load, or not load correctly.


## Set the Width and Height
An important reason for including the `width=""` and `height=""` attributes to your image elements is that the web browser uses these to reserve the correct amount of space for the image on the page when rendering, even in the case where the page is rendered before the image file is delivered to the browser.

This means that the page will not have to ‘re-render’ to accommodate an image that loads after the rest of the page.


## Include Well-Written Alts and Titles

While it is important to be descriptive in these attributes for accessibilty reasons, the `alt=""` and `title=""` attributes will also be used by some browsers in the case where the image itself cannot load.

This helps your visitors understand what they may have missed, or cannot load on the page.

<img src="" alt="You are seeing the alternative text of this image. Hover your cursor over this broken image to see its title popup." title="I am the title!" style="width: 300px; height: 150px; border: 1px solid #AEA79F"/>
