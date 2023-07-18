# Class 08 Summary
## Code 201 - Foundations of Software Development

> These topics relates because CSS Layout will dictate how our web applications look and it will affect their responsiveness.

### Learn CSS - Flexbox
1. Flexbox is designed for one-dimensional content. Explain what this means.
  > It refers to te content that is organized along a single axis - either the horizontal (x) axis or the vertical (y) axis.
2. Explain the difference between the main axis and cross axis.
  > Main axis is set by `flex-direction` property. If is set as `row` then main axis would be along this row. If it is set as `column` then main axis is long this column.
3. How can using certain properties of flexbox negatively impact accessibility?
  > Properties like `flex-direction: row-reverse` and `flex-direction: column-reverse` can reorder the visual display from how things are in the HTML document. This reordering only happens visually not logical order. Thus, it can negatively impact accessibility.


### CSS Layout - Flexbox
1. What are some advantages of using flexbox over float?
  > * Alignment control - You can vertical align things within a container using `align-items` and `align-self`
  > * Reordering elements - You can easily change the order of elements visually without modifying the HTML. This can be done using `order` property.
  > * Nesting  flexibility - You can easily nest flex containers .
2. How does this topic connect with your long term goals?
  > * These layout can make my web applications responsive on all screen types and can help with accessibility.


### Things I want to know more about
> * The differences between grid and flexbox

### What I used for this reading
> * Google
> * ChatGPT