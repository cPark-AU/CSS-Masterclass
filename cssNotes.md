<h3><b>Flexbox</b></h3>

The container for flexbox is the parent and the content inside are the children. 

In flexbox, there are two axes, one is the main-axis (horizontal) and the other is the cross-axis (vertical).

The default flex-direction of flexbox is row (horizontal) and to change the location of the children, 
justify-content is used and for columns (vertical), align-items is used.

<b><i><u>flex-direction:</u></i></b>

<b>[ flex-directon: row; ]</b> - the main axis is horizontal and the cross axis is vertical 

<b>[ flex-direction: column; ]</b> - the main axis is vertical and the cross axis is horizontal

<b>[ flex-direction: row-reverse; ]</b> - reverses the direction of row

<b>[ flex-directon: column-reverse; ]</b> - reverses the direction of column

<b><i><u>align-items:</u></i></b>

When using <b>[ align-items: center; ]</b> make sure the height of the container is higher than the boxes inside.

Once the height is assigned to the container, we can observe that the boxes are aligned to the center of
the cross axis.

<b>[ align-items: flex-end; ]</b>- places items on the end of the cross axis

<b>[ align-items: flex-start; ]</b> - places items on the start of the cross axis (default)

<b>[ align-items: center; ]</b> - places items on the center of the cross axis

<b><i><u> align-content </b></i></u>

align-content modifies the lines. When the line breaks, the space between the lines is what can be modified.

<b><i><u>align-self</u></i></b>

align-self works exactly like align-items, this means cross axis, but only for one box which is given to a child class. 

<b><i><u>order</u></i></b>

order is use to change the order of boxes without changing the html itself. 

<b><i><u>flex-wrap</b></i></u>

flex-wrap determines the nature of flex, where flex will attempt to modify the width of the children elements to fit them all in one line.

<b>[ flex-wrap: no-wrap; ]</b> - default wrapping 

<b>[ flex-wrap: wrap; ]</b> - tells flex to not change the width of boxes

<b>[ flex-wrap: reverse; ]</b> - reverses wrapping

<b><i><u>flex-shrink</b></i></u>

Applied to a child elemenet. Defines the behaviour of a element when flexbox tries to squeeze them. 

<b>[ flex-shrink: 2; ]</b> - the element will squeeze 2x more than other elements in its line

<b><i><u>flex-grow</b></i></u>

flex-grow is the same as flex-shrink but the opposite. It determines how much a element can grow. flex-grow triggers when there is only space that the box can grow, otherwise it will shrink to the same size as other elements.

<b>[ flex-grow: 0; ]</b> - the default value is 0

<b><i><ins>flex-basis</b></i></ins>

flex-basis is like width, however it only sets the initial size before the element is expanded or shrunk. flex-basis is always applied on the main axis (flex-direction). 

<b>[ flex-basis: 300px; ]</b> - can be used sort of like a combined width and height

