# title(){return this.options.title||this.options.name}

## Educative Frontend CSS-Grid Notes

Also revise below from Scrimba:

- [Become a professional React developer](https://scrimba.com/course/greact)
- [The Responsive Web Design Bootcamp](https://scrimba.com/course/gresponsive)
- [The Ultimate JavaScript Bootcamp](https://scrimba.com/course/gjavascript)
Happy Coding!

1. Baby Steps:
  - Just like flexbox everything starts with one liner:
  - display: grid or display:inline-grid for an inline version.
div {
  display: grid;
}

2. Creating columns and rows in grid:
   - grid-template-columns and grid-template-rows.
   - grid-template-columns defines the placement of the columns within the grid container.
   - grid-template-rows defines the placement of the rows within the grid container.
   - You pass in length values into these properties, and they create row and column tracks within the grid container.
   - grid-template-columns: 100px 200px 300px => This will create 3 new columns within the grid container. The first with a length of 100px, the other, 200px and the last, 300px.
   - grid-template-rows: 100px 200px 300px => This will create 3 new rows within the grid container.

.grid-container {
  display: grid;
  grid-template-columns: 100px 200px 300px
  grid-template-rows: 100px 200px 300px
}