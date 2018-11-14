---
title: CSS Syntax and Selectors
module: topic-07
permalink: /topic-07/style-syntax/
categories: css
tags:
---

<div class="divider-heading"></div>

To style content in your HTML document you write “style rules” that apply to elements. These rules will always follow the same patterns.


## Selectors and Declarations
The first part of every rule is a **selector** which tells the browser what element(s) the rule applies to. This is followed by a space, then a block, delineated with curly brackets.

<div id="code-heading">Directory Tree</div>
<pre id="bash">
h1 { }
<i class="fas fa-long-arrow-alt-up bounce-y"></i>
</pre>


The portion of the rule delineated by the curly brackets is known as the **declaration**. This tells the browser what to do to the selected element(s).


<div id="code-heading">CSS</div>
<pre id="breakdown-block">
h1 {<img class="fas bounce" src="../img/dots-horizontal-left.png" style="width: 2em; margin: 0 0 0 1em;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /> <span class="fas text-bounce">Selector</span>
  color: black; <img class="fas bounce" src="../img/dots-horizontal-left.png" style="width: 2em; margin: 0 0 0 1em;" /> <span class="fas text-bounce">Declaration</span>
}
</pre>


<div class="divider-pg"></div>


## Elements and Rules
**Rules** can be applied singularly or en masse to one or more selectors:


### Multiple Selectors with Different Rules
When applying different rules to elements, you simply need to write another selector/declaration set. The closing **curly bracket** (`}`) tells the browser the rule is finished.

<div id="code-heading">CSS</div>
<pre id="breakdown-block">
<span style="color: #090080;font-weight: normal;">h1</span> {<img class="fas bounce" src="../img/dots-horizontal-left.png" style="width: 2em; margin: 0 0 0 1em;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /> <span class="fas text-bounce">Rule 1: Applied to all h1 elements</span>

}

p { <img class="fas bounce" src="../img/dots-horizontal-left.png" style="width: 2em; margin: 0 0 0 1em;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 -1px;" /> <span class="fas text-bounce">Rule 2: Applied to all paragraphs</span>

}
</pre>


### Multiple Selectors with the Same Rules

If you need to apply the same rules to more than one element, you can select multiple elements in a single style rule. To do so, separate each selector element with a comma (`,`).

You can then still go on to apply additional, unique style rules to an already styled element. These rules will simply be cumulative.

<div id="code-heading">CSS</div>
```css
h1, h2, p {
    /* Style rules applied to all h1, h2, and paragraph elements. */
}

p {
    /* Additional style rules applied only to paragraph elements. */
}
```
