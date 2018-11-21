responsive-website
==================

This project contains a collection of files that may be used to implement a small, hand-built, HTML/CSS responsive-design website.

For anyone with a modicum of HTML/CSS experience, this easily-modified code should provide a template for creating one's own responsive code that provides an optimal viewing experience on both mobile- and desktop-based browsers.

Getting Started
---------------

Download the project and unzip it in a convenient directory. The material may be used privately as a reference by an instructor or as a public reference with students in a course.

Files include:

* A single `index.html` webpages that can be used as a template.
* A commented stylesheet, `responsive_styles.css`, that is referenced by `index.html`.
* A sample `image1.jpg` image
* The Javascript file `showHide.js`, which is used by the mobile menu button to reveal/hide the menu items in the mobile form of the site.

The webpages have been written using a "mobile-first" strategy: the development of this page assumes that the user is browsing the documents on a mobile device--a common context--and the styling contained in the CSS document follows this assumption. In this form, the menu items are hidden from the user in favor of a burger-style link that is displayed below the header. Activating the burger causes a styled vertical menu list to appear.

An `@media` description beneath the other styles indicates what should happen in a wider browser: the vertical menu option is hidden and a horizontal menu is made available for navigation. Some components that may have been hidden before are now visible, divs `content1` and `content2` are now placed side-by-side, and horizontal margins are created to maintain a readable page width.

Author
------

**Richard White** - *Updated*, 2018, November  
**Richard White** - *Initial work*, 2015


License
-------

The MIT License (MIT)

Copyright (c)2018 Richard White

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


