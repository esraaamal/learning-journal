# how and why CSS
**it's make your web pages more attractive 
and  allows you to create rules that specify how the content of
an element should appear**
![dd](https://i.ytimg.com/vi/1Rs2ND1ryYc/maxresdefault.jpg)

## HTML page can use more than one CSS style sheet..
and to _link CSS with Html_ we can do it in three ways:

1-Inline - by using the style attribute in HTML elements
2-Internal - by using a <style> element in the <head> section
3-External - by using an external CSS file
 
<link>command  used
in an HTML document to tell the
browser where to find the CSS
file used to style the page.

<link href="css/styles.css" type="text/css"
 rel="stylesheet" />
 
### while href attribute determine the path to the CSS file type:
**This attribute specifies the type
of document being linked to. The
value should be text/css.
rel
This specifies the relationship
between the HTML page and
the file it is linked to**

....................
CSS works by associating rules with HTML elements:
the  CSS rule contains two parts:
1- selector : indicate which
element the rule applies to

## ex:Universal Selector : * { }
Targets all elements on the page.
....................
## Type Selector:  h1, h2, h3 {}
....................
## Class Selector:( .note {})
ID Selector:#introduction {}  Targets the element whose
id attribute has a value of introduction
....................
## Child Selector
li>a {}
Targets any <a> elements that
are children of an <li> element
( but not other <a> elements in
the page)
....................
## Descendant Selector: p a {}
Targets any <a> elements that
sit inside a <p> element, even if
there are other elements nested
between them
......................................
General Sibling Selector :h1~p {}
If you had two <p> elements that
are siblings of an <h1> element,
this rule would apply to both



and a declaration: indicate how
the elements referred to in
the selector should be styled.




Declarations are split into two
parts 
1- property 
2-a value
You can specify
several properties in one declaration
each separated by a semi-colon.
example:
nav ,h1 {color:red;}

Properties indicate the aspects
of the element you want to
change. For example, color, font,
width, height and border.


Introduce you to how CSS works
h1 to outlines to each of
the elements its indicate to "importantance"
the difference between block level
and inline elements and how
how browsers display them
Block level elements look
like they start on a new line.
but the
Inline elements flow within the
text and do not start on a new
line>>>>
we can control Boxes:
Width and height
Borders (color, width, and style)
Background color and images
Position in the browser window.
Typeface
Size
Color
Italics, bold, uppercase,
lowercase, small-caps
There are also specific ways
in which you can style certain
elements such as lists, tables,
and forms.
When building a site with more
than one page, you should use
an external CSS style sheet. This:
- Allows all pages to use the
same style rules (rather than
repeating them in each page).
- Keeps the content separate
from how the page looks.
- Means you can change the
styles used across all pages
by altering just one file
(rather than each individual page).
..........................................
for text we can edit the:
Typeface
Size
Color
Italics, bold, uppercase,
lowercase, small-caps
 

