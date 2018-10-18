---
title: 2. Action
module: topic-05
permalink: /topic-05/form-action/
tags: action, attribute, form
---

<div class="divider-heading"></div>


<div id="code-heading">Element Breakdown <i class="fas fa-battery-quarter"></i></div>
<pre id="breakdown-block">
<form <span class="pulsate">action="#"</span> method="" id="" class="">
   <i>&lt;!-- Form elements... --&gt;</i>
</form>
</pre>


The **action attribute** is a link to a server-side script (i.e. a file on another computer, not the users computer). Typically this file is code file (php, javascript, python, java, etc) on a server that will do something with the user data before returning information back to the browser.

<span class="label label-info">Note</span> The value of the action attribute will always be an URL. For out purposes, you can use `#` as a URL placeholder.
