<h3>grid</h3>

grid is similar to flexbox where we want to always talk to the parent element to change what happens to the children elements.

<b>[ grid-template-columns: 20px 55px 89px 100px; ] </b> - This is used to change the width of elements. We can change the number of columns in a row by adding or removing values. <i>auto</i> can be used to fill up the maximum space of the screen.

<b>[ grid-template-rows: 100px 50px 300px; ] </b> - This is used to change height of elements. We can also use <i>repeat(3, 200px)</i> to repeat the same values.

<b>[ column-gap: row-gap: gap: ]</b> - The column-gap and row-gap provide a gap for its respective name and gap is used for both column and row

<b>[ grid-template-areas: ] </b> - We tell the class for the grid-template-areas what they are ( grid-area: header; ) for grid-template-areas to know what it is dealing with.

![image](https://user-images.githubusercontent.com/107847685/201828273-38de9bc6-cc9a-48f8-9ec1-81224712f0be.png)

<b>[ grid-column-start: 1; ]</b> - this tells the element at which line it should start.

<b>[ grid-column-end: 5; ]</b> - this tells the element at which line it should end.

<b>[ grid-row-start: 2; ]</b> - similar to grid-column-start but for row

<b>[ grid-row-end: 4; ]</b> - similar to grid-column-end but for row

Like above, we can do similar things but in a much easier fashion:

<b>[ grid-row: 2 / 4; ]</b> - tells the element that it starts at line 2 and ends at line 4

<b>[ grid-column: 1 / -1; ]</b> - tells the element to go from start to the end. (- sign starts from the end). We can also use [ span 4 ] to tell the element that it takes up 4 grids.

When setting up grid-template we can do the following to name each line and refer back to them to select the start and end points:

<b>[ grid-template-columns: [first-line] 100px [second-line] 200px; ]</b>
