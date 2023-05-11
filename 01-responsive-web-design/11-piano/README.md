# Learn responsive web design by building a piano

Responsive Design tells your webpage how it should look on different-sized screens.

In this course, you'll use CSS and Responsive Design to code a piano. You'll also learn more about media queries and pseudo selectors.
<br><br>
## Notes

### Multiple class

A html element can have multiple class.

__Example:__

`<div class="key black--key"></div>`
<br><br>

### Default values
Browsers can apply default margin and padding values to specific elements. To make sure your piano looks correct, you need to reset the box model with box-sizing property.

__Example:__

`box-sizing: border-box;`

"border-box" tells the browser to account for any border and padding in the values you specify for an element's width and height. If you set an element's width to 100 pixels, that 100 pixels will include any border or padding you added, and the content box will shrink to absorb that extra width.
<br><br>

### ::before and ::after pseudo-elements

The ::before selector creates a pseudo-element which is the first child of the selected element, while the ::after selector creates a pseudo-element which is the last child of the selected element. These pseudo-elements are often used to create cosmetic content.
<br><br>

### float

The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).

__Example:__

`float: left;`
<br><br>

### Media query

The @media at-rule, also known as a media query, is used to conditionally apply CSS. Media queries are commonly used to apply CSS based on the viewport width using the max-width and min-width properties.

__Example:__

`@media (max-width: 768px) {
  #piano {
    width: 358px;
  }
  .keys {
    width: 318px;
  }
}`

We can use also logiciel operator to have more complex conditions : 

`@media (min-width: 500px) and (max-width: 1000px){
}`
<br><br>

### overflow

To prevent the keys from collapsing when the browser window is smaller than 768px, we set overflow to hidden in the first .keys selector. This property will hide any element that is pushed outside the set width value of .keys.

`overflow: hidden;`

