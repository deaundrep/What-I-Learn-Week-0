# What-I-Learn-Week-0
* Markdown
* JavaScript in HTML

## **Markdown**
Markdown is a lightweight markup language with plain-text-formatting syntax. Its design allows it to be converted to many output formats.

**ex.**
# h1
## h2
### h3
h(number up to 6) is a heading that comes up with bigger font and the lesser the number the bigger is the font

* unordered list a
* unordered list b
asterisk at the beginning of a line creates unordered list item

1. ordered list number one
2. ordered list number two
3. ordered list number three
numbers with dot at the end create ordered list

_italics_
    or
*italics*
underscores or asterisks at the beginning and the end of text make text italics (a bit slanted to side)

**bold**
    or
__bold__
double underscores or asterisks at the beginning and the end of tet make text bold (slightly thicker character lines to make it stand out)

!(image description)[image-file.jpg]
this posts an image on translated markdown page. first part (image description) describes image for accessibility and second part [imag-file] links the actual image to a page

## ** JS HTML**
HTML tags create objects; JavaScript lets you manipulate those objects. JavaScript makes HTML pages more dynamic and interactive.

**ex.**
<html>
 <head>
  <script type="text/javascript">
function functionOne() { alert('You clicked the top text'); }
function functionTwo() { alert('You clicked the bottom text'); }
  </script>
 </head>
<body>
 <p><a href="#" onClick="functionOne();">Top Text</a></p>
 <p><a href="javascript:functionTwo();">Bottom Text</a></p>
 </body>
</html>
