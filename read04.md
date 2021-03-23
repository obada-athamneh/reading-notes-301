# A Complete Guide to Grid

## grid-template-columns
## grid-template-rows

* Defines the columns and rows of the grid with a space-separated list of values. The values represent the track size, and the space between them represents the grid line.


### grid-template-areas

**Defines a grid template by referencing the names of the grid areas which are specified with the grid-area property. Repeating the name of a grid area causes the content to span those cells. A period signifies an empty cell. The syntax itself provides a visualization of the structure of the grid.**

## justify-content

* Sometimes the total size of your grid might be less than the size of its grid container. This could happen if all of your grid items are sized with non-flexible units like px. In this case you can set the alignment of the grid within the grid container. This property aligns the grid along the inline (row) axis (as opposed to align-content which aligns the grid along the block (column) axis).


## Values:

1. start – aligns the grid to be flush with the   start edge of the grid container
2. end – aligns the grid to be flush with the end edge of the grid container
3. center – aligns the grid in the center of the grid container
4. stretch – resizes the grid items to allow the grid to fill the full width of the grid container
5. space-around - places an even amount of space between each grid item, with half-sized spaces on the far ends
6. space-between – places an even amount of space between each grid item, with no space at the far ends
7. space-evenly – places an even amount of space between each grid item, including the far ends


## align-content

* Sometimes the total size of your grid might be less than the size of its grid container. This could happen if all of your grid items are sized with non-flexible units like px. In this case you can set the alignment of the grid within the grid container. This property aligns the grid along the block (column) axis (as opposed to justify-content which aligns the grid along the inline (row) axis).


# Common Responsive Layouts with CSS Grid (and some without!)

* CSS grid is now supported in Samsung internet v6.2 and many other modern browsers and has been the answer to many a prayer of web developers everywhere. In the same way that flexbox gave us a way to layout block elements next to each other, CSS grid lets us not only arrange elements in a row or a column, but in multiple rows and columns. Finally two dimensional layouts are becoming simpler!

* When I was learning CSS and HTML the way that I learnt best was by copying layouts written by others and then changing bits, deleting bits and playing around with them until I understood what was going on. With that in mind, I’ve composed a few common responsive website layouts for you to copy, edit, mess around with. I’ll go over my thinking with each layout and will outline a few tricks from each one. (NB, you may have noticed that I’m not a designer, so I hope you like cats!). I’ve moved the CSS in each demo that is relevant to the layout up to the top of the CSS file in comment blocks so that you can see the important parts easily, don’t write your CSS like this.

