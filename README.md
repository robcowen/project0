# Project 0

<<<<<<< HEAD
<<<<<<< HEAD
** Web Programming with Python and JavaScript **
=======
Web Programming with Python and JavaScript
>>>>>>> 91b1f8fc998ccf354a2244b47edf9ce56e61dd71
=======
** Web Programming with Python and JavaScript **
>>>>>>> 66968b4af8a21f385507bf235dcd6b8d6265a7fe

I have created a website about my aquarium.

At the top of each page is a Bootstrap navbar that allows the user to select which fish to view. Below large screen sizes, the navbar collapses to be replaced with a dropdown menu.

The index page is split into two Bootstrap columns, with a photo of my fish on the left and text on the right. The text includes an unordered list and a table, formatted using Bootstrap. I have used the 'nth-of-type(n)' css rule to format the second column in tbody (i.e. the Latin fish names) in italics and to centre-align the third column. Both of these rules are SCSS nested within a #fishTable selector.

The photo is responsively formatted using Bootstrap, with custom CSS to add a border-radius. The border-radius is set using a SCSS variable to allow the same radius to be applied to the %fishCard divs on the fish pages.

Above the split columns is a full-width column containing a page title. This uses a @media query to resize the font for smaller viewports. Similarly, the split columns will collapse automatically through the use of Bootstrap's 'col-lg' class.

For the fish pages, I have used a %fishCard inheritance to standardise the properties for each fish card (although this could also have been done using a class). This is then extended by each of four ids for each fish. Each fish card differs only in the url of the background image. The standard properties include white text, occupying 90% of the viewport in each dimension, a border-radius derived from the $border-radius variable and various settings to fix the image in the centre of the div, no matter the size of the viewport.
