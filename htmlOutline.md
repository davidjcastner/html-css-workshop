### Setup

You can view the slides at:

In this workshop, you will be using chrome & codepen

Other browsers may work, but to make it easy use chrome

[Google Chrome](https://www.google.com/chrome/browser/desktop/)

[CodePen](https://codepen.io/)

Useful to keep open: [W3Schools HTML Reference](http://www.w3schools.com/tags/default.asp)

## HTML Workshop

Meant to be an introduction

Recommended to take a full HTML tutorial

### What is HTML

**H**yper**T**ext **M**arkup **L**anguage ****

A way of displaying data in a tree format

Browsers define how to display the data

Three major components in HTML:
* Elements
* Data (innerHTML)
* Attributes

### HTML Elements

An **Element** is a node of data in the tree

An **Element** is defined by opening and closing tags

The data inside the element is referred to as **innerHTML**

Some elements cannot have data (innerHTML) and they are officially called **void elements** but are also called **singletons**

**Elements** except the doctype element are case insensitive, but always use lowercase

Example: `<element></element>`

### HTML Attributes

An **Attribute** provides an element with extra information

An **Attribute** is defined inside of the opening tag

**Attributes** are case insensitive, but always use lowercase

The value of an **Attribute** should be surrounded by quotes

Example: `<element attribute="somevalue"></element>`

### HTML Data

**Data** or innerHTML is the information inside of an element

One or more elements can be data inside of another element

Example:
```html
<element class="outer">
  somedata
  <element class="inner"></element>
  <element class="inner"></element>
</element>
```

### Don't cross Tags

Example of what **not** to do
```html
<h1>
  <p>
  </h1>
</p>
```

### HTML Structure

![tree view](http://www.w3schools.com/js/pic_htmltree.gif)

### Core Tags

Doctype: Used to tell that the data is html `<!DOCTYPE html>` included at the top of all html files

HTML: Data of this tag is considered html `<html></html>`

Head: Data inside head is not displayed but used to tell how to render data

Title: Used inside the head tag to give your webpage a title

Body: Data inside the body tag is content that will be displayed in the browser

Example: [HTML Structure](https://gist.github.com/davidjcastner/c9dacf0aa2a50401e56d12b061080b48)

Codepen defines all of these tags for you and anything to type will be inserted into the body element

### MOAR TAGS

Basic tags:
* comments
* headers & paragraph
* lists
* anchors (links)
* image
* hr & br

View these in action: [HTML Tutorial Basic](http://codepen.io/davidjcastner/pen/vKBWjd)

### HTML Lab

Create a website for your facts on your favorite animal on [CodePen](https://codepen.io/)

Include the following:
* a comment
* at least two headers
* a list of three facts about the animal
* an image of the animal
* a link to the wikipedia of the animal (or other factual site)

Example: [Sea Otter Page](http://codepen.io/davidjcastner/pen/PzYaYZ)

### Blocks vs Inline

For displaying html, the elements are defined as blocks or inline (or both, but we'll cover that later)

The most basic block element for displaying data is div `<div></div>`

The most basic inline element for displaying data is span `<span></span>`

div and span are used mainly for the purpose of styling

Example: [HTML Tutorial Blocks](http://codepen.io/davidjcastner/pen/ZOzaMb)

### Scripts

Script tag is used for inserting javascript (not covered in this workshop)

But here is a quick example: [JS Basic Demo](http://codepen.io/davidjcastner/pen/WxeJKx)

### HTML vs HTML5

HTML5 is still HTML

HTML5 added defined new elements

Support for HTML5 is browser dependant, don't need to write html differently

Behavior of HTML5 on browser without support usually causes the elements to not display, but the it is considered to be undefined behavior

### Best Practices

* keep it simple (avoid redundancy in elements)
* practice good code styling (helps prevent missing closing tags)
* consider browser support

### Transistion to CSS

Style attribute

Style tag

Link tag

CodePen automatically links the stylesheet for you
