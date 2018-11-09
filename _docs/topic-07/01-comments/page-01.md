---
title: Select and Declare
module: topic-07
permalink: /topic-07/select-declare/
categories: css
tags:
---

<div class="divider-heading"></div>


To style content in your HTML document you write “style rules” that apply to elements. These rules will always follow the same patterns.


## Selector
The first part of every rule is a **selector** which tells the browser what element(s) the rule applies to. This is followed by a space, then a block, delineated with curly brackets.

<div id="code-heading">CSS</div>
```css
/* ⬇ SELECTOR - selects all h1 elements */
   h1 {

   }
```

### Declaration

The portion of the rule delineated by the curly brackets is known as the **declaration**. This tells the browser what to do to the selected element(s).

<div id="code-heading">CSS</div>
```css
/* ⬇ /* SELECTOR - selects all h1 elements */
   h1 {
     /* ⬇ DECLARATION goes inside curly brackets. */
       color: white;
   }
```
