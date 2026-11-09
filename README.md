# ProcessWriteup
## Name: Steven Tian
## Course: SEP10
## Period: 2
## Concept: CSS

### Context
CSS, also standing for Cascading Style Sheets allows you to edit and customize appearances for stuff made and written with HTML or Markup.

### Lesson Summary for Markdown
Notes to remmeber

**__Classes__**
* To create a class, we first need to add a "." at the start of the line follwed by the name of the class. Afterwards, add "{}" where in between those will be the set of code to decorate/customize certain texts or images. An example will be...
```
.CLASS {
font-size: 15px;
}
```
This will cause all elements with the "CLASS" Class to have a font size of 15px.

**__Divs and Spans__**
* Divs can be used to group up multiple elements to edit them together, while span can be used to take a select few inside a element and only edit those instead of the entire element.
```
<div>
<h1> Good Morning! </h1>
<p> today is such a <span>good morning!</span> I'm so happy to be outside today. </p>
</div>
```
Now, whatever class I put inside the div will edit both the h1 and paragraph, and the class I put inside the span will only edit the "good morning" text.

**__Padding and Margin__**
* Padding is the space inside an element's border.
* Margin is the space outside an element's border.
* Can be edited like this.
`Padding: 20px, 20px, 20px, 20px;`
* Order goes like (Top, Right, Bottom, Left)

 ### Challenge 1:
 The first challenge I encountered was why my class wouldn't work, even though I added the class to the elemnt. For the CSS code, I would do this.
```
CLASS {
font-size: 15;
}
```
Seeing this, I thought I did everything perfectly, but if you look closer, I have two mistakes. Firstly, for making a class, you need a "." at the start. Second, I didn't ass "px" at the end of the number for font size. These cause the class to not work as 15 isn't a valid size and without the ".", it isn't a class. I fixed it all at the end and it looked more like this.
```
.CLASS {
font-size: 15px;
}
```

 ### Takeaway
One takeaway I learned was how much divs and spans can help out your code. Without divs and spans, elements will be harder to edit together and mostly will not work well or work at all. Another one is how organizing your code helps out a lot. Indenting for your code and using divs and spans all help you organize your code, making you feel less loss when doing work and cause you to create less errors and know where everything is and does.
