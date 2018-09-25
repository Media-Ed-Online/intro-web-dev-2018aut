---
title: Internal Linking
module: topic-02
permalink: /topic-02/link-internal/
---

<div class="divider-heading"></div>

## Relative Linking Within Your Repository
As you now know, the internet is built foundationally on links and inter-connected files and systems. We'll get into **hypertext** and **hyperlinks** later on in the course, but for right now, let's continue the [discussion on absolute URLs](../urls-absolute/) and [discussion on relative URLs](../urls-relative/), looking at linking the files within our directory together.

You've done some linking in **markdown** already, using outside sources and _absolute_ URLs:


<div id="code-heading">Markdown</div>
```markdown
[discussion on absolute URLs](https://media-ed-online.github.io/intro-web-dev/topic-02/urls-absolute/)
```


<br />

But I can also link to pages in this website using _relative_ URLs, as long as I stay within my  `/intro-web-dev` repository. As the administrator of this site, I can link to the same page like so:


<div id="code-heading">Markdown</div>
```markdown
[discussion on relative URLs](/topic-02/urls-relative/)
```


<br />

If within our _Intro-Web-Dev_ repo, I can use either of these methods to link back to the same page. But one is much more efficient for me to type, and doesn't require me to have pushed all of (or anything) to GitHub's servers yet.
