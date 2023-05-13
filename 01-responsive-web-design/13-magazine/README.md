# Learn CSS Grid by building a magazine

CSS Grid gives you control over the rows and columns of your webpage design.

In this course, you'll build a magazine article. You'll learn how to use CSS Grid, including concepts like grid rows and grid columns.

## Notes

### img loading attribute 

The loading attribute on an img element can be set to lazy to tell the browser not to fetch the image resource until it is needed (as in, when the user scrolls the image into view). As an additional benefit, 
lazy loaded elements will not load until the non-lazy elements are loaded - this means users with slow internet connections can view the content of your page without having to wait for the images to load.

### Referer HTTP

The Referer HTTP header contains information about the address or URL of a page that a user might be visiting from. This information can be used in analytics to track how many users from your page visit freecodecamp.org, 
for example. Setting the rel attribute to noreferrer omits this information from the HTTP request.

### Default navigator font-size

Creating an html selector and giving it a font-size property set to 62.5% will set the default font size for your web page to 10px (the browser default is 16px).

`html {
  font-size: 62.5%;
}`

This will make it easier for you to work with rem units later, as 2rem would be 20px.

### Grid

CSS Grid offers a two-dimensional grid-based layout, allowing you to center items horizontally and vertically while still retaining control to do things like overlap elements.

CSS Grid is similar to Flexbox in that it has a special property for both the parent and child elements.

`main {
  display: grid;
  grid-template-columns: 1fr 94rem 1fr;
}`

This will create three columns where the middle column is 94rem wide, and the first and last columns are both 1 fraction of the remaining space in the grid container.

grid-column property determines which columns an element starts and ends at. 

Example: 
`.text {
  grid-column: 2 / 3;
}`

