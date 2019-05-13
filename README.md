# tropicophoto
Creating frontend website using materialize css

* Creating basic index.html:
  * import fontawesome to make social media icons available
  * import material icons for use with form
  * import materialize css

* Adding background image:
  * Using custom css to create background image
  * adding media query to adapt image for smaller screens

* Adding header:
  * use materialize class nav-wrapper 
  * making the nav bar transparent adds a nice depth/shadow effect
  * added div with class of container to keep text centralize and not go to the edges
  * making header responsive by using class="right hide-on-med-and-down"
  * adding side nav for smaller screens using class="sidenav"
  * intialize side nav by using jquery to grab id and a method from materialize css called sidenav()

* Adding grid for photo:
  * create a section with class of container so that it targeted later with custom css if necessary (class of section added to give margin at top)
  * use class of responsive-img to make photos take up width of columns specified
  * using materialize pull and push to manipulate center text and image in grid 
  * use materialize method: materialbox() in javascript to make images pop
  * add padding to section using vw units to make padding relative to the screen size


Acknowledgements:

[Tropico Photo](http://www.tropicophoto.com/)

[Net Ninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg)