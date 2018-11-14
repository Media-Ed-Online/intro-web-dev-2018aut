---
title: CSS Syntax and Selectors
module: topic-07
permalink: /topic-07/style-syntax/
categories: css
tags: declare, property, rule, select, value
---

<div class="divider-heading"></div>

To style content in your HTML document you write “style rules” that apply to elements. These rules will always follow the same patterns.

Consider this **heading 1**, found on your website:

<img src="../img/home-page.png" alt="simple about page" style="width: 200px;" />

## Selectors and Declarations
The first part of every rule is a **selector** which tells the browser what element(s) the rule applies to. This is followed by a space, then a block, delineated with curly brackets.

The portion of the rule delineated by the curly brackets is known as the **declaration**. This tells the browser what to do to the selected element(s).


<div id="code-heading">CSS</div>
<pre id="indicator-block">
<div class="bounce-y-down" style="margin: 0 0 -20px -5px"><span class="label bounce-word">Selector</span>
<i class="fas fa-long-arrow-alt-down"></i></div>
  h1 { }
<div class="bounce-y-up" style="margin: 0px 0px -20px 8px"><i class="fas fa-long-arrow-alt-up"></i>
<span class="label bounce-word" style="vertical-align: text-top;">Declaration(s)</span></div>
</pre>


<div class="divider-pg"></div>


## Property and Value
Inside the declaration, you specify how to style the selected element with property-value pairs.

The **property** is the aspect about the element that you want to change, i.e. list items or paragraphs.

The **value** defines how to change a property; for example, color and placement.

The pair is separated with a colon (`:`). Additional declarations are separated with a semicolon (`;`), and are typically placed on new lines.

<div id="code-heading">CSS</div>
<pre id="indicator-block">
<div class="bounce-y-down" style="margin: 0 0 -20px 30px"><span class="label bounce-word">Property-One</span>
<i class="fas fa-long-arrow-alt-down"></i></div><div class="bounce-y-down" style="margin: 0 0 -20px 30px"><span class="label bounce-word">Property-Two</span>
<i class="fas fa-long-arrow-alt-down"></i></div>
  h1 {color:gray; font-size:22px;}
<div class="bounce-y-up" style="margin: 0px 0px -20px 105px"><i class="fas fa-long-arrow-alt-up"></i>
<span class="label bounce-word" style="vertical-align: text-top;">Value</span></div><div class="bounce-y-up" style="margin: 0px 0px -20px 105px"><i class="fas fa-long-arrow-alt-up"></i>
<span class="label bounce-word" style="vertical-align: text-top;">Value</span></div>
</pre>


<div class="divider-pg"></div>


## Elements and Rules
**Rules** can be applied singularly or en masse to one or more selectors:


### Multiple Selectors with Different Rules
When applying different rules to elements, you simply need to write another selector/declaration set. The closing **curly bracket** (`}`) tells the browser the rule is finished.


<div id="code-heading">CSS</div>
<pre id="indicator-block">
  h1 {color:gray; font-size:22px;} <div class="bounce-x"><i class="fas fa-long-arrow-alt-left"></i> <span class="label bounce-word" style="vertical-align: text-top;">Rule 1 (applied to <u>all</u> heading ones)</span></div>

  p {font-size:12px;} <div class="bounce-x"><i class="fas fa-long-arrow-alt-left"></i> <span class="label bounce-word" style="vertical-align: text-top;">Rule 2 (applied to <u>all</u> paragraphs)</span></div>
</pre>


### Multiple Selectors with the Same Rules
If you need to apply the same rules to more than one element, you can select multiple elements in a single style rule. To do so, separate each selector element with a comma (`,`).

You can then still go on to apply additional, unique style rules to an already styled element. These rules will simply be cumulative.


<div id="code-heading">CSS</div>
<pre id="indicator-block">
  h1, p {color:gray;} &nbsp;<div class="bounce-x"><i class="fas fa-long-arrow-alt-left"></i> <span class="label bounce-word" style="vertical-align: text-top;">Rule 1 (applied to <u>all</u> heading ones <u>and</u> paragraphs)</span></div>

  h1 {font-size:22px;} <div class="bounce-x"><i class="fas fa-long-arrow-alt-left"></i> <span class="label bounce-word" style="vertical-align: text-top;">Rule 2 (<u>additionally</u> applied to <u>all</u> heading ones)</span></div>

  p {font-size:12px;} &nbsp;<div class="bounce-x"><i class="fas fa-long-arrow-alt-left"></i> <span class="label bounce-word" style="vertical-align: text-top;">Rule 3 (<u>additionally</u> applied to <u>all</u> paragraphs)</span></div>
</pre>
