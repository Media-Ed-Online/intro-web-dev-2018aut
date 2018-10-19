---
title: Links to Other Sites
module: topic-04
permalink: /topic-04/links-to-others/
tags: absolute, html, elements, link, url
---

<div class="divider-heading"></div>


<div class="container-row">
  <div class="lightbulb">
     <svg viewBox='0 0 64 64'>
       <g>
         <line x1='32' y1='16' x2='32' y2='0' />
         <line x1='41.40' y1='19.05' x2='50.80' y2='6.11' />
         <line x1='47.21' y1='27.05' x2='62.43' y2='22.11' />
         <line x1='47.21' y1='36.94' x2='62.43' y2='41.88' />
         <line x1='16.78' y1='36.94' x2='1.56' y2='41.88' />
         <line x1='16.78' y1='27.05' x2='1.56' y2='22.11' />
         <line x1='22.59' y1='19.05' x2='13.19' y2='6.11' />
       </g>
     </svg>

     <i class="far fa-lightbulb"></i>
     <i class="fas fa-lightbulb blink"></i>
  </div>
  <p><span class="remember-text">Remember?</span><br/>
  Links that include the “<code>http/https</code>” as part of the entire URL are known as <b>absolute URLs</b>.</p>
</div>


<div id="code-heading">HTML</div>
```html
<a href="https://example.com" target="_blank">Link to Example.com</a>
```


Notice in the above link that it includes “`https`”. The “`https`” is required to signify to the browser that this is an ‘external’ link outside of the current document’s directory/server. **You must include either “`http`” or “`https`”.**

<span class="label label-success">Neat-O</span> The former is a older, established, version of the “hypertext transfer protocol”, which specified how data was sent between clients. The latter, is a “secure” version of this protocol. Whenever possible, you should provide “`https`” links (just check that they work first), as it provides a safer browsing experience.


<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="zEwMLb" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="External HTML Links" class="codepen"></p>
</div>
