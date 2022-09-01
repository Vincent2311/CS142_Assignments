## concepts
1. Web browsers display Documents described in HTML  (HyperText Markup Language)
2. Markup Language - Include directives with content. Directives can dictate presentation or describe content
	Approach 
	1. Start with content to be displayed 
	2. Annotate it with tags

## Need to handle markup characters in content
```html
&lt;           Displays <
&gt;           Displays >
&amp;          Displays &
&quot;         Displays "
&nbsp;         Nonbreaking space (won’t insert a line break at this space)
```


## Common usage XHTML tags
```html
<p> New paragraph
<br> Force a line break within the same paragraph
<h1>, <h2>, ... Headings
<b>, <i> Boldface and italic
<pre> Typically used for code: indented with a fixed-width font,
 spaces are significant (e.g., newlines are preserved)
<img> Images
<a href="..."> Hyperlink to another Web page
<!-- comments --> Comment tags

<table>, <tr>, <td> Tables
<ul>, <li> Unordered list (with bullets)
<ol>, <li> Ordered list (numbered)
<div> Used for grouping related elements, where the group
occupies entire lines (forces a line break before and after)
<span> Used for grouping related elements, where the group is
within a single line (no forced line breaks)
<form>, <input>, <textarea>, <select>, ... Used to create forms where
users can input data 
```
<a href = "https://web.qianguyihao.com/01-HTML/07-HTML%E6%A0%87%E7%AD%BE%E5%9B%BE%E6%96%87%E8%AF%A6%E8%A7%A3%EF%BC%88%E4%BA%8C%EF%BC%89.html#%E8%A1%A8%E5%8D%95%E6%A0%87%E7%AD%BE">关于最后一行的具体教程</a>
```html
<title> Specify a title for the page, which will appear in the title bar
 for the browser window.
<link> Include CSS stylesheets
<script> Used to add Javascript to a page (can be used in body as well)
```


## Another markup language: Markdown
```markdown
# Heading 
## Sub-heading 
### Another deeper heading 
Paragraphs are separated by a blank line. 

Two spaces at the end of a line leave a line break. 
ext attributes _italic_, *italic*, __bold__, **bold**, 
`monospace`. 
Horizontal rule: ---

Bullet list: 
* apples 
* oranges 
* pears 

Numbered list: 
1. apples 
2. oranges 
3. pears 

A [link](http://example.com).
```
# Heading 
## Sub-heading 
### Another deeper heading 
Paragraphs are separated by a blank line. 
Two spaces at the end of a line leave a line break.  
Text attributes _italic_, *italic*, __bold__, **bold**, `monospace`. 
Horizontal rule: 

---
Bullet list: 
* apples 
* oranges 
* pears 

Numbered list: 
1. apples 
2. oranges 
3. pears 

A [link](http://example.com).
