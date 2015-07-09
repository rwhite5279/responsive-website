README.md for Responsive Styles
@author Richard White
@version 2015-07-08

This project contains a collection of files that may be used to implement a small, hand-built, HTML/CSS responsive-design website. The files include:

* Two .html webpages, an index.html and a page2.html.
* A commented stylesheet, `responsive_styles.css`, that is referenced by the HTML documents.
* A .jpg image
* A copy of jquery-1.11.0-min.js, released under the MIT license.

The webpages have been written using a "mobile-first" strategy: the write-up assumes that the user is browsing the documents on a mobile device, and the styling contained in the CSS document follows this assumption. In this form, a horizontal menu is hidden from the user, while a burger-style menu link is available in the header. Activating the burger causes a styled vertical menu list to appear.

An @media description beneath the other styles indicates what should happen in a wider browser: the vertical menu option is hidden and a horizontal menu is made available for navigation. Some components that may have been hidden before are now visible, divs `content1` and `content2` are now placed side-by-side, and horizontal margins are created to maintain a readable page width.

For anyone with a modicum of HTML/CSS experience, this easily-modified code should provide a template for creating one's own responsive code that provides an optimal viewing experience on both mobile- and desktop-based browsers.

