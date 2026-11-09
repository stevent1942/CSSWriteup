# ProcessWriteup
## Name: Steven Tian
## Course: SEP10
## Period: 2
## Concept: CSS

### Context
In HTML coding, we learned how to create links, headers, paragraphs, lists, images, blackquotes, and stylizing such as bolding and italicizing.

### Lesson Summary for Markdown
Notes to remmeber

**__Links__**
* To create a Regular link, we first put this in, `[NAME](LINK)`. The name will show up and clicking it will send you to the link you put in
* To create Reference link, we put in `[NAME]:LINK`. If we put this down, we can put the Reference Link name in place of the regular link in the first code I showed.
* Same thing goes for images, you put a source link where the normal link should be

**_Headers_**
* There are up to 6 headers, each smaller than the previous
  * Header 1: `# HEADER`
  * Header 2: `## HEADER`
  * Header 3: `### HEADER`
  * Header 4: `#### HEADER`
  * Header 5: `##### HEADER`
  * Header 6: `###### HEADER`

**_Stylizing_**
* `**TEXT**` will bold something
* `_TEXT_` will italicize something

**_Lists_**
* `* TEXT` will create a dotted list
* `1. TEXT` will created a numbered lsit
* You can indent a point by adding a space before adding the `* TEXT`

### Lesson Summary for HTML
Notes to Remember

**_Text_**
* You must put down `<x>` at the start of a line to start that line, and `</x>` to end that line.
* `<p>TEXX</p>` will create a paragraph

**_Heading_**
* Headings come in 6 different sizes, from Largest to Smallest
 * `<h1> </h1>`
 * `<h2> </h2>`
 * repeat this code, replacing the numeral value with another number up to 6

 **_List_**
 * To create a Numbered list, you put `<ol> </ol>`
 * To create a Dotted list, you put `<ul> </ul>`
 * To add actual points or to use the list, you put `<li> </li>` In between `<ol>` and `</ol>` or `<ul>` and `</ul>`

 **_Links and Images_**
 * To create a placeholder link, you will place a `#` in the place of a link. Example: `<a href="#">Click me</a>`
 * To create a link, you use `<a></a>`.
  * Inside of the starting point, place `href=` or `src=`
  * In between the starting and end point can you write down a name for the link
  * `src` can be used for the location of the image file itself

 ### Challenge 1:
 The first challenge I encountered was why my lists wasn't working in HTML. Whenver I made code for a list I would do this:
1. `<ol> HEADER `
2.  `<li> something`
3.  `<li> something`
4.  `</ol>`
###### I couldn't understand why it wasn't working, until I realized that even the `<li>` for the list needs an ending `</li>` as well. So I fixed it by doing this.
1. `<ol> HEADER `
2.  `<li> something </li>`
3.  `<li> something </li>`
4.  `</ol>`

 ### Takeaway
 One takeaway I learned was even the slightest and most minor mistake in coding can cause errors and cause it not to work properly. For example, forgetting to add a closing tag can cause a list to not work as coded to. Also learned how Markdown and HTML have completely seperate ways of making text and lines of code, but both have the same use.
