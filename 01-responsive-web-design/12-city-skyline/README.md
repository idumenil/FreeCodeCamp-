# Learn CSS variables by building a city skyline 

CSS variables help you organize your styles and reuse them.

In this course, you'll build a city skyline. You'll learn how to configure CSS variables so you can reuse them whenever you want.

## Notes

### Explanation of some lines

`body { height: 100vh; }` to be sure the height of the body fulfill of the viewport

`body { overflow: hidden; }` to hide any scroll bars that appear when something extends past the viewport

`.background-buildings {
  width: 100%;
  height: 100%;
}` to make the buildings background the full width and height of its parent, the body


### Variable usage

`bb1 { --building-color1 : #999; }` declaration of a variable --building-color1

`.bb1a { background-color: var(--building-color1); }` use of the variable declared in another selector

Sometimes there is a problem with the first value. A fallback value need to be add in this case : `background-color: var(--building-color2, green);`

It is recommanded to declare variable in the :root selector so they can be cascaded to the children element. root is the highest range of CSS selector. 

### Color transition

Gradients in CSS are a way to transition between colors across the distance of an element. They are applied to the background property and the syntax looks like this:

`gradient-type(
  color1,
  color2, 
  color2,
  ...
);` 

Example for a linear gradient using variable: 

`background: gradient-linear-gradient(var(--building-color1), var(--window-color1));`

