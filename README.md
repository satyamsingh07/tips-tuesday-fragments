! What is a react fragment?

!!Fragments are syntax that allow us to add multiple elements to a React component without wrapping them in an extra DOM node.

image.png

!!! Above code snippet gives you a glimpse of a basic react component that doesn't need to be wrapped up in the main component.

!!However if we have let's say one more p element and try to execute the code:-

image.png

!!! The above code throws and error!
image.png

!! In order to render both the elements, we can wrap them inside a div tag 
image.png

!! This implementation is fine if we're using the parent div tag to style and position our components. However,using divs only as a wrapper increases code nesting and decreases performance.

!! This is where the use of fragments makes more sense.
The fragment tag acts only as a conatainer and does not interefere with the code structure at all.
image.png

!!!This helps in mantaining a clean code structure and improves performance

