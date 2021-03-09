// FLEXBOX

* Flexbox is a new module in CSS3 that makes it easy to align elements to one
another, in different directions and orders.

* The main idea behind flexbox is to give the container the ability to expand and
to shrink elements to best use all the available space.

* Flexbox replaces floats layout, using less, more readable and logical code.

* Flexbox completely changes the way that we build one-dimensional layouts.

* Flexbox is a true revolution in CSS!


// FLEXBOX TERMS
1. flex container = is any container that its display property is set to flex or
flex-inline. Most of the time we use display flex because flex-inline is rarely use
and it behaves like an inline element. Flex container sets the property on how flex
items are aligned in it.

2. flex items = are the items that sit directly in a flex container.

3. Main and Cross axis = it is the main direction in which the flex items are aligned. 
By default the items are aligned side by side which is in the main axis. We also have
the cross axis, which aligned items one on top of another.




// FLEX CONTAINER PROPERTIES

1. flex-direction: row | row-reverse | column | column-reverse
// description: Specifes how the flex items are aligned in the container, the
default is row which means items are aligned side by side from left to right.
If set to column, the flex items will be aligned from top to bottom. row-reverse
will reverse the arrangement of the flex items that means from right to left and
also the same with column-reverse, it will go from bottom to top.

2. flex-wrap: wrap | nowrap
// description: Simple defines if the flex items should wrap into a new line if
there is no more space in the flex container or not.

3. justify-content: flex-start | flex-end | center | space-between | space-around |
space-evenly
// description: This defines how the flex-items will be aligned along the main axis

4. align-items: flex-start | flex-end | center | baseline
// description: This defines how the flex-items will be aligned along the cross axis

5. align-content: flex-start | flex-end | center | space-between | space-around
// description: This only applies when there is more than one row of flex items, in
that case align-content control how the rows are aligned along the cross-axis if there
is some empty space.

6. flex-wrap: nowwrap | wrap | wrap-reverse
// Description: The default is nowrap which do not wrap the flex items to a new row when
there is no more space available in the flex container. When set to wrap some of the items
that do not fit in the current row are placed on a new one.



// FLEX ITEM PROPERTIES

1. align-self: auto | stretch | flex-start | flex-end | center | baseline
// desc: Similar to align-items but this apply to a single flex item

2. order: 0 | <integer>
// desc: Defines the order in which a flex item should appear in the container

3. flex-grow: 0 | <integer>
// desc: Defines how a flex item should grow based on the width of the container.
The initial value of the flex items is zero.

4. flex-shrink: 1 | <integer>, flex-basis: auto 
// desc: Defines how a flex item should shrink based on the width of the container

5. flex-basis: auto | <length>
// desc: Defines how the base width of a flex item. Auto means occupy only the space
its needed.

6. flex: 0 1 auto;
// desc: Shorthand for flex-grow, flex-shrink and flex-basis respectively.


// Justify-content values
1. center: centers the flex items;

2. space-between: Add equal space between the flex items but not at the beginning or end.

3. space-around: Add spaces around every flex item, this will include the beginning an end.
In between the flex items there will be 2 times the space that there is in the beginning and
in the end of the items.

4. space-evenly: distribute the same amout of space to both the start and end of the flex items
and also in between the items.

5. Flex-end: aligned the items to the end of the container

6. flex-start: aligned the items to the beginning of the container, this is the default if no
value is set.



// Align-items values
This works when the size of the flex items varies from one another

1. stretch => The items will strech themselves to march the biggest flex item height amd
this is the default behaviour,

2. center => It will center the smallest flex items relative to the largest item in the 
cross axis.

3. flex-start => will align the items at the beginning of the cross axis, that is the top
of each flex item will be aligned at the top of the cross axis

4. flex-end => will align the items at the end of the cross axis, meaning the bottom
of each item will be placed at the end of the cross axis

5. baseline => It will aligned the content of the flex-items along a line.


