---
title: "First bugs: fixing get requests"
excerpt: "Post displaying the various ways of highlighting code in Markdown."
last_modified_at: 2018-02-22T09:45:06-05:00
header:
  teaser: "assets/images/markup-syntax-highlighting-teaser.jpg"
categories:
  - bugs
tags: 
  - code
  - node
  - get-request
toc: true
gallery:
  - url: /assets/images/server.png
    image_path: /assets/images/server.png
    alt: "my large changes"

gallery2:
  - url: /assets/images/app.png
    image_path: /assets/images/app.png
    alt: "my small changes"
---

Fixing my first two bugs was a fun process, I really enjoyed delving into other people repositories. I think this process was needed and helped me understand open source even more.

### YuriyKartuzov's issue #3

#### Crashes when multiple phone numbers are in GET

##### My changes to the code

{% include gallery caption="This is a sample gallery with **Markdown support**." %}
I saw his current usage of is **findphonenumbers** could be more polymorhpic if the numbers were parsed before function call

On line 27 I decide to add a parser so the phonenumber could be evaluated by phonenumber.lib in smaller chunks

I removed line 60 because i was preprasing the in a try loop

```js
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
```

### MikeFainshtein's issue #2

#### You can add as many phone numbers in get request object

{% include gallery id="gallery2" caption="This is a second gallery example with images hosted externally." %}

My pull requests

#### YuriyKartuzov

<script src="https://github.com/YuriyKartuzov/Project/pull/5/files"></script>

#### mfainshtein2

<script src="https://github.com/mfainshtein2/phoneparser-js/pull/3/files"></script>
