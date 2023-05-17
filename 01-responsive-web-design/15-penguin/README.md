# Learn CSS transform by building a penguin

You can transform HTML elements to create appealing designs that draw your reader's eye. You can use transforms to rotate elements, scale them, and more.

In this course, you'll build a penguin. You'll use CSS transforms to position and resize the parts of your penguin, create a background, and animate your work.

## Notes

### Removing scoll bars

We can use `body { overflow: hidden }` to remove horizontal and vertical scroll bars. 

### Skew function

To make the mountain look more like a mountain, you can use the skew transform function, which takes two arguments. The first being an angle to shear the x-axis by, and the second being an angle to shear the y-axis by.

### Selection of desendants

To select all the descendants of an element, for example the .penguin element, use this syntax : `.penguin * { property: value }`

### Selection of the first child of an element

Use the "before" pseudo-element `.penguin-body::before { }`
