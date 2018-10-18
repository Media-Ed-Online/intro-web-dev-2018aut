---
title: 3. Method
module: topic-05
permalink: /topic-05/form-method/
tags: attribute, form, get, method, post
---

<div class="divider-heading"></div>


<div id="code-heading">Element Breakdown <i class="fas fa-battery-three-quarters"></i></div>
<pre id="breakdown-block">
<form action="#" <span class="pulsate">method=""</span> id="" class="">
   <i>&lt;!-- Form elements... --&gt;</i>
</form>
</pre>


Forms can be sent using one of two methods; '`get`' or '`post`'.

## method="get"
With the **“get” method**, values are added to the end of the specified action URL.

This methods is ideal for searches, or for _retrieving_ data from a server (as opposed to sending data that will be stored in a database).


## method="post"
With the **“post” method**, values are sent in what are known as 'HTTP headers.' As a rule of thumb, use the '`post`' method when;

- users are uploading a file
- the data will be very long
- the data is sensitive (ie. contains passwords)
- The data is intended to alter or access a database on the server
