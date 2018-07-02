# GRIDkit. A starter kit for CSS Grid Layout

GRIDkit is a starter kit for CSS Grid Layout. It's simple and mobile-first with a Flexbox fallback for IE 10+.

[View a demo of GRIDkit](https://www.flow14.com/css-gridkit/).

## Structure

GRIDkit uses **blocks** and **columns** to define a page.

**Blocks** are similar to rows in other frameworks. They are containers for columns or groups of columns.

The base block is set to a max-width of 1200px with a defined grid-gap.

There are two variations of the block element:

- **block-flush** sets the grid-gap to 0
- **block-wide** sets the max-width to 100%

**Columns**

GRIDkit is based on a 12 column grid. To define a column, use `col-n`, where 'n' = the number of columns you'd like to span. 

col-1 = 1 column
...
col-12 = 12 columns

There are two sample design patterns:

- **pattern__3-6-3** creates a 6-column span, centered in the middle of the page
- **pattern__2-8-2** creates an 8-column span, centered in the middle of the page

## Roadmap

- Add centering / justification styles
- Add ordering styles

## Credits

- Uses bits of code from [flexboxgrid.com](http://flexboxgrid.com) for IE support (10+)

