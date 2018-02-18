---
title: "VsCode: my first time working with bugs"
header:
  overlay_image: http://prntscr.com/ig9b03
  teaser: http://prntscr.com/ig9b03
categories:
  - bugs
tags:
  - lab3
  - open source
---

I worked on the color picker issue. Issued invloved the inability to view any color beside the hex or even see the color wheel when selected

The steps to recreate this involved going into a file  like the usersettings.json and inputing a usually editable color value. To this it isn't, and the color beside the hex that should be there is not present in addition you can't use the color wheel. 

I tracked down the issue and narrowed it dow nto one single commit. Unfortunatly that commit being a merge. After this discovery I knew this would be a very long problem for me so solve in a relativity new environment to me. I found it would be something to do with the differences In the color.ts located in src\vs\editor\contrib\colorPicker. 

check out the bug i tried to fix plus my comment I left
[here](https://github.com/Microsoft/vscode/issues/42720)

I learned alot like how to use the break on method in vscode, bisect in git and few other definitions about git.