# Learn CSS Animation by building a Ferris Wheel 

You can use CSS animation to draw attention to specific sections of your webpage and make it more engaging.

In this course, you'll build a Ferris wheel. You'll learn how to use CSS to animate elements, transform them, and adjust their speed.

## Notes

### Drawing a circle

`.wheel { 
  border: 2px solid black;
  border-radius: 50%;
  margin-left: 50px;
  position: absolute;
  height: 55vw;
  width: 55vw;
  max-width: 500px;
  max-height: 500px;
}`

### transform-origin

The transform-origin property is used to set the point around which a CSS transformation is applied. For example, when performing a rotate, 
the transform-origin determines around which point the element is rotated.

### @key-frame

The @keyframes at-rule is used to define the flow of a CSS animation. Within the @keyframes rule, you can create selectors for specific points in the animation sequence, such as 0% or 25%, or use from and to to define the start and end of the sequence.

@keyframes rules require a name to be assigned to them, which you use in other rules to reference. For example, the @keyframes freeCodeCamp { } rule would be named freeCodeCamp.

The animation-name property is used to link a @keyframes rule to a CSS selector. 
