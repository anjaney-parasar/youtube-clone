* When we change the width of an image it's height also changes to adjust the dimensions of the image.
* The 'Search' text in the searchbox which tells the user the function of the input is called the placeholder.

### In HTML there are 3 types of elements
1. block element = takes up the entire line
2. Inline-block = only takes up as much space as needed
3. Inline element = appear within a line of text

### <div> element

1. <div> simply means division or just a box.
2. It is also a block element.
3. This can easily be changed using the display property.
4. By default divs have a width of 100%.

**UPDATE** Block element actually take up the entire line **in their container**.


* NOTE: Spacing outside the element is called **margin**, while spacing inside the element is called **padding**.

* Setting up fonts like this- font-family:Roboto, Arial; is called a **font stack**, this basically allows you to provide a backup font if the primary font isn't available.


### The problem with inline block
1. if we leave some space between two divs in the html code, it'll consider it as a single space and there would be some visible space on the page between two divs
2. the divs are not perfectly vertically aligned.
  
_to deal with this we have something known as CSS grid_

**Bonus point** You can also provide style within an element tag this is called **inline style**.

**Grid layout** A grid is a layout that has rows and columns
1. Grid makes the children divs to have inline block property
2. columns in grid don't have any space in between.
3. If one col is taller than the other one, the other one also gets **vertically aligned**.


Flexbox is like CSS grid but it's more flexible.
1. It is not rigid like CSS  grid.
2. elements take their width with them even if they don't move around.
3. So it has a flexbile layout


* Position: fixed , positions the element in the browser window which doesn't move when we scroll.
* Position: absolute , positions the element in the page which does move when we scroll.


* Generally, an element which is written below in the code will render in front of the element written above it.
* To change this property we can use **z-index** which determines the order of elements on z-axis i.e. which elements will appear in front and which elements will appear behind.


* Usually position:absolute isn't used that much while building websites but there's a special usecase.
* If you put a position:absolute element inside a position:fixed element the position:absolute element changes it's position w.r.t (relative) to the parent element

* To achieve this same thing with an element which is not position:fixed, we can simply put position:relative in the parent element.
* Position:relative still treats the parent element normally, just that all the child elements are positioned relative to the parent element.
* Position:static will always appear at the back.


### Responsive Design
You can make the design responsive by writing media queries (@media) which dictates page layout at cetain conditions of page sizes


### Inheritence :
Certain properties, mostly text properties will get passed down from the outer element to the inner elements.


### CSS Specificity
Generally, if we set the same style on the same elements, the style that is more specific has higher priority and they'll a general style

### Semantic elements
They are just as divs just that they special meaning and structure to our page for seach engine and screen readers.

