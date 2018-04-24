---
title: "Release 0.2"
header:
  overlay_image: "/assets/images/lab5spoiler.png"
  teaser: "/assets/images/lab5spoiler.png"
categories:
  - bugs
tags:
  - release02
  - open source
gallery:
  - url: /assets/images/notepad++-issue.png
    image_path: /assets/images/notepad++-issue.png
  - url: /assets/images/notepad++-pull.png
    image_path: /assets/images/notepad++-pull.png

gallery2:
  - url: /assets/images/rr-issue.png
    image_path: /assets/images/rr-issue.png
  - url: /assets/images/rr-pull.png
    image_path: /assets/images/rr-pull.png
---

For my release 2 (which I actually did in reverse) I decided to work on two other projects that would interest me that were more focused in the industry besides gaming starting out with Notepad++

# Bugs:

## Notepad++

{% include gallery caption="" %}

There was a small issue with the grammar involved in the xml file, resulting in the production version containing a wrong french translation. Oddly, after fixing the issue the original user actually did a pull request over mine, then someone else even corrected his!

## Mozilla:

{% include gallery id="gallery2" caption="" %}

The mozilla bug was more of interesting bug, meaning, it actually evolved a bit of engagement in my part(partially). The mozilla issue was that of manual memory management the fact the devs would like to remove the use of malloc and xmalloc in there code, and instead, replace it with new and delete. After much back and forth between me and devs I was able to come to conclusion of not formating and complete deletion instead of deprecation of the functions involved.
