---
title: Cascading Stylesheets
module: topic-07
permalink: /topic-07/css-intro/
categories: css
tags: style
---

<div class="divider-heading"></div>

“<span style="font-weight: bolder; text-decoration: underline; color: #E95420;">C</span>ascading <span style="font-weight: bolder; text-decoration: underline; color: #E95420;">S</span>tyle<span style="font-weight: bolder; text-decoration: underline; color: #E95420;">s</span>heets (CSS) is a stylesheet language used for describing the presentation of a document written in a markup language like HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content.”


## Where to Style
There are three general ways to specify CSS style rules:

1. Within the **style element** in an HTML document.
2. As a **style attribute** within a element.
3. In a separate **style document**, or “stylesheet.”

You are familiar with the first option, and we will discuss the other two during this topic.


## Two Ways to Style
CSS is not whitespace dependent. In other words, you do not need to include extra lines between rules. However, this shown style increases readability of your code. _It's polite._


**TL;DR?** The two following examples will produce the same results, whether written horizontally or vertically.


<div id="code-heading">CSS</div>
```css
/* Written horizontally, this means the same as... */
h1 {color: black; text-align: center;}

/* ...written vertically. */
h1 {
  color: black;
  text-align: center;
}
```
