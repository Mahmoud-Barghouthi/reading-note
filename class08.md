### Layout

### Building Blocks


#### CSS treats each HTML element as if it is in its own box. This box will either be a block-levelbox or an inline box

### Containing Elements

#### If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

### Controlling the Position of Elements

#### CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

#### To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. (You will meet these when we introduce the positioning schemes on the following pages.

### Normal FLow 
#### Position:Static

#### In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be:position: static; 

### Relative Positioning 
#### Position:relative

##### Relative positioning moves an element in relation to where it would have been in normal flow

### Absolute Positioning 
#### Position:absolute

#### When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)

### Fixed Positioning
#### Position:fixed
##### Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.

### Overlapping Elements
#### Z-Index

#### When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. 

### Floating Elements
#### Float

#### The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

### Using Float to place elements side-by-side
#### A lot of layouts place boxes next to each other. The floatproperty is commonly used to achieve this.

### Clearing Floats
#### Clear

#### The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box.

### Parent of floated elements: Problem
#### If a containing element onlycontains floated elements, some browsers will treat it as if it is

-------------------
### Screen Sizes

#### Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

