# Learn intermediate CSS by building a Picasso painting

In this course, you'll learn how to use some intermediate CSS techniques by coding your own Picasso painting webpage. You'll learn about SVG icons, CSS positioning, and review other CSS skills you've learned.<br><br>

## Notes

### FontAwesome
FontAwesome is a library of SVG-powered icons, many of which are freely available to use. Some of them are used in this project. To use them you need to add a link in the head of your html file : https://use.fontawesome.com/releases/v5.8.2/css/all.css
<br><br>

### Manual positionning
HTML is rendered in a top-down manner. Elements at the top of the code are positioned at the top of the page. However, many times you may want to move the elements to different positions. You can do this with the position property.

__Example:__
`body {
  position: absolute;
  top: 0;
  left: 0;
}`
<br><br>

### Layers

The z-index property is used to create "layers" for your HTML elements. Elements with a higher z-index value will appear to be layered on top of elements with a lower z-index value.

__Example:__ 
`#back-wall {
  z-index: -1;
}`
<br><br>

### Borders properties

border-radius : to smooth angles

border-width : to adjust border width
<br><br>

### Idiomatic text

The i element is used for idiomatic text, or text that is separate from the "normal" text content. This could be for italic text, such as scientific terms, or for icons like those provided by FontAwesome. By using a specific class name, Font Awesome can determine which icon to use.

__Example:__ 
`<i class="fas fa-music"></i>`

We can modify the properties of idiomatic content, like the position, the size, etc.

__Example:__
`.fas {
  font-size: 15px; 
  }`
