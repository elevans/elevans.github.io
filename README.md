ImageJ.net (Experimental)
===

Welcome to ImageJ.net.

## Sidebar with section anchors

A navigation sidebar can be added by including the `sidebar` element and providing the anchor names as the content. 

_Note_: There are a couple things to note about the `sidebar` element:

1. Separate multiple entries with a comma.
2. To include a break/seperator line use `|`.
3. The title will be rendered as bold text and will not be a link.
4. The sidebar links and anchor links must be the same, otherwise they will not link properly. 
5. The sidebar is always rendered on the **right** side of the page.
6. You should always place the sidebar at the top of the page, before your content.

To setup the sidebar use the following syntax:

```
{% include sidebar title="Demo" content="Introduction, |, Left image, Right image, Center image, Fit image" %}
```

To setup the anchors use the following syntax:

```
{% include anchor content="Introduction" %}
```

<p align="center">
	<img src="/images/readme/sidebar.png">
</p>


## Info-box

To add an info-box to your page, specifiy the icon you wish to use and include the info-box content:

```
{% include info-box icon_path="/images/icons/40px-Information-sign.png" content="Hey this is the info box! 

- item 1
- item 2

If you want to learn more about how to create an info box, view the source of this page!" %}
```

<p align="center">
	<img src="/images/readme/info-box.png">
</p>

## TODO (pre-live):

- [X] Math support via Mathjax.
- [X] UX bread crumbs (top of page)
- [X] Code syntax highlighting
- [X] Add infobox elements
- [X] Add brief description to front matter.
- [X] Add Lazy loading to images
- [X] Seperate info-box into (author should not specifiy icon path):
	- [X] Information
	- [X] Tech
	- [X] Warning
- [ ] Add userbox (https://imagej.net/Template:Userbox)
- [ ] Add component box (https://imagej.net/Template:Component)
- [ ] Table of contents heirachy
- [X] Remove "category indexes" from search
- [ ] Create wide table style
- [X] Add link support for the info-box
- [X] Fix footer -- does not stick to bottom
- [ ] Fix h2 header --> normal/bold should be #585858
- [X] Fix tables (too wide) -- set to `width: 50%;`
- [X] Fix infob0x (add bullet points support and better icon centering)
- [ ] Change table style -- needs lines
- [ ] Fix Figure center - width issues
- [X] Convert all links to use relative_url (safely prepend links to the domain root and allows for moving to different `baseurl` if necessary)
- [X] Add Sidebox element
- [X] Add Edit and view source links to page template
- [X] Add page/post type to categories
- [ ] Add supporting pages
	- [x] Getting started (/learn.md)
	- [X] Architecture (/learn/architecture.md)

## TODO (post-live):

- [ ] Change base url for "View source" page info from jekyll-protoype branch

Credit:
------------------

Photon by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A simple (gradient-heavy) single pager that revisits a style I messed with on two
previous designs (Tessellate and Telephasic). Fully responsive, built on Sass,
and, as usual, loaded with an assortment of pre-styled elements. Have fun! :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = Not included)

Feedback, bug reports, and comments are not only welcome, but strongly encouraged :)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Responsive Tools (github.com/ajlkn/responsive-tools)
