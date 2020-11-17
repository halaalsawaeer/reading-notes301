In the same way that flexbox gave us a way to layout block elements next to each other, CSS grid lets us not only arrange elements in a row or a column, but in multiple rows and columns. Finally two dimensional layouts are becoming simpler!
The repeat() function takes two arguments, the first will define the number of column tracks and the second, what width the tracks should be.

This image gallery layout uses features of CSS grid to create different sizes of grid cells. I’ve used the span value on grid-columnand grid-row to make individual cells stretch over two or more slots in the track.

The ‘Holy Grail’ layout describes a page with a header and footer that stick at the top and bottom of the window respectively, and a content section that is split into two sidebars and the main content sits between them. This has been notoriously difficult to solve in an elegant way with CSS due to the need to stretch the content to push the footer down to the bottom of the page. With CSS grid, creating this layout requires very few lines of code.


CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows.


display
Defines the element as a grid container and establishes a new grid formatting context for its contents.

Values:

grid – generates a block-level grid
inline-grid – generates an inline-level grid

justify-self
Aligns a grid item inside a cell along the inline (row) axis (as opposed to align-self which aligns along the block (column) axis). This value applies to a grid item inside a single cell.

Values:

start – aligns the grid item to be flush with the start edge of the cell
end – aligns the grid item to be flush with the end edge of the cell
center – aligns the grid item in the center of the cell
stretch – fills the whole width of the cell (this is the default)