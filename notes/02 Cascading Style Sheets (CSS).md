## Concepts
Early HTML - Override defaults with attributes
```
	<table border="2" bordercolor="black">
```
Style sheets were added to address this: 
	Specify style to use rather than browser default 
	Not have to code styling on every element

Key concept: **Separate style from content**
Content (what to display) is in HTML files
Formatting information (how to display it) is in separate style sheets (.css files).

Use an element attribute named class to link (e.g. ``<span class="test">``)
Result: define style information once, use in many places

CSS Selector:
1. Tag name  h1 {    color: red;  }                           ``<h1>Today’s Specials</h1>``
2. Class attribute   .large {font-size: 16pt;}         ``<p class="large">...``							
3. Tag and Class  p.large {...}    ``<p class="large">...``
4.  Element id  #p20 {font-weight: bold; }       ``<p id="p20">...``

CSS Pseudo Selectors:
hover - Apply rule when mouse is over element (e.g. tooltip) 
	p:hover, a:hover { background-color: yellow; }
	
a:link, a:visited - Apply rule when link has been visited or not visited (link)
	a:visited {color: green;}    a:link {color: blue;}

root element : typically`<html>`

[About position property](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

[cursor - Set the cursor when over element (e.g. help)](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)