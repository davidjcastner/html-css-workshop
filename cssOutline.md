### Setup

You can view the slides at:

In this workshop, you will be using chrome & codepen

Other browsers may work, but to make it easy use chrome

[Google Chrome](https://www.google.com/chrome/browser/desktop/)

[Codepen](https://codepen.io/)

Useful to keep open: [W3Schools CSS Reference](http://www.w3schools.com/cssref/default.asp)

## CSS Workshop

Meant to be an introduction

Recommended to take a full CSS tutorial

### What is CSS

**C**ascading **S**tyle **S**heet ****

[Cascading Example](http://codepen.io/davidjcastner/pen/vKBVxO?editors=1100)

Three major components in CSS
* Selector
* Property
* Property Value

Syntax: `selector { property: value; property: value; }`

### Selector

Adds the styling to elements that match the selector

Three common selectors:
* `element {}` matches all elements of `element`
* `.class {}` matches all elements with a matching class
* `#id {}` matches the with a matching id

### Colors (a property value)

Basic way to define a color is a 6 digit hexadecimal number

Example: `#ffffff` which is white

Other ways to define a color as well

Recommended to use a color palette [Example Palette](https://gist.github.com/davidjcastner/e4cfbabba7ecd16a5905d5edfd5c01ab)

### Units (a property value)

For font-sizes use px or em (em is a ratio to the default font size)

For non font-sizes use px or % (% is a percentage of the parent element)

### Fonts

[Google Fonts](https://www.google.com/fonts) is an easy way to add a font, but it's not the only option

Font related properties
* font-family
* font-size
* font-weight
* color
* text-align

### CSS Font Lab

Find a font that you enjoy and apply it to your animal site

Example: [Sea Otter Page](http://codepen.io/davidjcastner/pen/zBOmZM)

### Background

* background-color
* background-image

### CSS Background Lab

Wrap the different sections of your site with a div element

Add a background to different sections of your site and adjust the font color accordingly

Don't worry too much about the alignment and sizing of the backgrounds yet;

Example: [Sea Otter Page](http://codepen.io/davidjcastner/pen/xOKypN)

### Size properties

* width
* height
* min-width, max-width
* min-height, max-height

### Box Model

![Box Model](https://www.washington.edu/accesscomputing/webd2/student/unit3/images/boxmodel.gif)

* margin, border, padding, content
* box-style

margin, border, and padding can all be followed by:
* -top
* -right
* -down
* -left

### Browser Console

In chrome pressing f12 will open up the browser console

The console has many useful tools, so use it!

Styling Tools Demo

### CSS Box Lab

Edit the margins, borders, and padding to help with the appearance

Some tips:
* make the margin for the section elements 0 (makes the background fill the area)
* add a padding to each section
* you can center a block by setting the left & right margin to auto

Example: [Sea Otter Page](http://codepen.io/davidjcastner/pen/aZoRKg)

### Positioning

* display (block, inline, none)
* visibility (difference between hidden and display none)
* position
* top, right, bottom, left

### Best practices

* use normalize.css
* viewport tag
* when making a responsive site avoid the following:
    * avoid defining a static width or height
    * avoid using positions (top, right, bottom, left)
* use the box styling method
* use classes instead of id whenever possible
* pick a class naming convention
* consider browser support (autoprefixer)
* avoid using float, use flexbox instead
* if you have to create a site compatible with Internet Explorer, find a new job
* try to avoid redundancy and keep it simple

### Tips & Tricks

Tips & Tricks for better style:
* Adding a font & set of font sizes
* Uniform padding and margins
* Responsive blocks & centering blocks
* Use a slight gradient
* Use a premade color palette

### Advanced Selectors

If we have time
combining/descendants/direct relationship
