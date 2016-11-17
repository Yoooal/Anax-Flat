---
views:
    aboutPic:
        region: main
        template: default/image
        data:
            src: "img/about.png"
    byline:
        region: after-main
        template: default/content
        sort: 1
        data:
            meta:
                type: content
                route: block/byline
    bylinePic:
        region: after-main
        template: default/image
        data:
            src: "img/byline.jpg"
...

<h2>Joels Om-sida</h2>

The primary focus of this site is to:

* To be used in teaching the [dbwebb course design](http://dbwebb.se/design).

The source for this site is available on GitHub in [Yoooal/anax-flat-theme](https://github.com/Yoooal/anax-flat-theme).

This site is produced by Joel Pettersson
