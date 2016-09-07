# workshop-caurosel
Objective
=========
Make a working carousel demo, like this one :
https://spencerkekauoha.github.io/lesson-carousel/

Like the example we will be using slick.
http://kenwheeler.github.io/slick/
I'm confident that there are other resources that we could use to accomplish the same thing. For now, we'll practice

We will need images to use in our carousel. I really like this resource:
https://unsplash.com/

step one
========
Fork and clone this repo.

step two
========
Familiarize yourself with the code. Get familiar particularly the index.html. You don't need to worry about the css for now. Open index.html in your browser or use live-server. See where the current picture of a horse is? That is where we are going to setup our carousel.

step three
==========
You can choose to install slick to use it, but we're going to use one of the CDN options. Let's follow the steps on https://github.com/kenwheeler/slick/. First lets link up their css in our html like so:

```html
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.css"/>
<!-- Add the slick-theme.css if you want default styling -->
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick-theme.css"/>
```

Then let's bring in the JavaScript. Before your closing ```<body>``` tag add:

```html
<script type="text/javascript" src="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.min.js"></script>
```


step four
==========
