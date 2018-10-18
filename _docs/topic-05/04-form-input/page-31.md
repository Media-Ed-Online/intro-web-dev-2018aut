---
title: 3. Name
module: topic-05
permalink: /topic-05/input-name/
tags: attribute, form, input, name
---

<div class="divider-heading"></div>


<div id="code-heading">Element Breakdown <i class="fas fa-battery-three-quarter"></i></div>
<pre id="breakdown-block">
<input type="" <span class="pulsate">name=""</span> id="" />
</pre>


Each form control requires a `name=""` attribute. This information is sent as part of a "name:value" pair to the server.

For example, an input element with the **name** attribute set to "username" (i.e. `name="username"`) might collect the data “Justine,” which would then be sent to the server as `username:Justine`.
