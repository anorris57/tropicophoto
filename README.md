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

* Adding simple parallax:
  * add a containing element for the parallax div
  * add div with class of parallax
  * add image tag
  * intialize parallax in javascript using materialize method: parallax()
  * add content after each parallax to make parallax stand out

* Adding tabs:
  * creating a section with class of section to get styling that matches rest of document.
  * set up grid for mobile responsiveness
  * create ul with class of tabs
  * create li that contains Link tags that href's that are set equal to the id of the content to be shown when clicked.
  * create divs containing content. Give each div the appropriate id to from link tabs
  * materialize method: tabs() using jquery to the tabs class.

* Adding forms:
  * use form tag
  * each input field in materialize should have its own containing div with a class of input field
  * labels should be placed below input fields
  * text area should be given a materialize class of "materialize-textarea"
  * use class of prefix to make icons come before input fields
  * use materialize class of datepicker with type text and use materialize method of datepicker() with jquery
  * use input type="checkbox" to get checkboxes that have animation

Acknowledgements:

[Tropico Photo](http://www.tropicophoto.com/)

[Net Ninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg)