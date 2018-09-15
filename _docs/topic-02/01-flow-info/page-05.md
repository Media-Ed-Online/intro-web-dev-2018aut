---
title: Absolute and Relative URLs
module: topic-02
permalink: /topic-02/urls/
---

<div class="divider-rounded"></div>

Generally, we can think about “finding” a web location in one of two ways: via its _relative_ or _absolute_ address, or URL. Let's create a scenario to start.

<div style="width: 75%; margin: auto; text-align: center;">
  <img src="../img/url-profile.svg" alt="profile placeholder" style="width:150px; margin: auto;" />
  <p>Consider the file “profile.jpg” and its URL:<br/> <b>https://www.example.com/about/images/profile.jpg</b></p>
</div>

## Absolute URLs
<img src="../img/url-building.svg" alt="apartment building" style="width: 100px; float: right; margin: 1em 0em 1em 1em;" />

An **absolute URL** contains all of the protocols and information for the file's location. If I am the owner of **www.another-example.com** and I want to link to "profile.jpg" I will need it's absolute URL (https://www.example.com/about/images/profile.jpg) as it lives on a separate site than mine.

We can compare this to needing to know the city, street, building, and apartment number of "profile.jpg" because we live in a different part of town.


## Relative URLs
<img src="../img/url-door.svg" alt="apartment building" style="width: 75px; float: right; margin: 1em 0em 1em 1em;" />

**Relative URLs** contain no protocols or domain information. This is convenient because they are shorter, but can _only_ reference files in the same path. If I am the owner of **www.example.com** and am embedding "profile.jpg" on my About page, I can do so relatively with "./images/profile.jpg" as long as the images folder is in the same path as my page. I do not need an absolute URL.

The "." is a path component stating that we need to remain in the current level of our directory hierarchy. Effectively, it says _"to find this file, begin here and then head down inside the images folder, where you'll find profile.jpg."_

To continue our analogy, since I'm already inside the same building as "profile.jpg," I only need its apartment number to find it.

This will be handy for you as you start to link to your own images within your repo.
