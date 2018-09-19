---
title: Relative URLs
module: topic-02
permalink: /topic-02/urls-relative/
---

<div class="divider-heading"></div>

<img src="../img/url-door.gif" alt="apartment door" style="width: 75px; float: right; margin: 1em 0em 1em 1em;" />

**Relative URLs** contain no protocols or domain information. This is convenient because they are shorter, but can _only_ reference files in the same path. If I am the owner of **www.example.com** and am embedding "profile.jpg" on my About page, I can do so relatively with "./images/profile.jpg" as long as the images folder is in the same path as my page. I do not need an absolute URL.

The "." is a path component stating that we need to remain in the current level of our directory hierarchy. Effectively, it says _"to find this file, begin here and then head down inside the images folder, where you'll find profile.jpg."_

To continue our analogy, since I'm already inside the same building as "profile.jpg," I only need its apartment number to find it.

This will be handy for you as you start to link to your own images within your repo.
