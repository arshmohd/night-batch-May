# title(){return this.options.title||this.options.name}

## Educative Frontend CSS-Grid Notes

Also revise below from Scrimba:

- [Become a professional React developer](https://scrimba.com/course/greact)
- [The Responsive Web Design Bootcamp](https://scrimba.com/course/gresponsive)
- [The Ultimate JavaScript Bootcamp](https://scrimba.com/course/gjavascript)
Happy Coding!


1. CSS Grid: Hands-on:
- Create a basic HTML Layout, with semantic markup.
- Advantage of using CSS Grid is you will save the hassle of using redundant container markup.
- Deine a CSS body element with display grid and min-height of 100%: This makes body and grid-container.
- Next define the row and column for grid.

- IMP unit of CSS-GRID System is "fr": The fractional unit.
- The fractional unit solves the problem of automatically distributing space equally (1fr 1fr 1fr) or based on number of units assigned.
- https://medium.com/flexbox-and-grids/the-css-fractional-unit-fr-in-approachable-plain-language-fdc47bd387f7
- if you have a fixed width element, then you can take up the remaining space with the fr unit
- As an example:

   grid-template-rows: 1fr 50px;
   grid-template-columns: 50px 1fr;

- 50px will be allocated to the fixed tracks, and the remaning space taken up by the other grid track.
- With fractual unit you dont need to recalculations as it handles on its own:
- With the fractional unit(fr) you don’t need to recalculate — at all.
- If you specify a width of 1fr , you can go on to add as many child elements as possible and it will be taken care of. The widths will be equally shared accross all child elements.

You are NOT bound to just “ones” or “whole numbers”. You may have values like: 1.5fr 3fr 4.5fr

In this case, the total fraction is 1.5fr + 3fr + 4.5fr = 9fr

If the parent container has a width of 900px…

The first, (1.5fr) will have a width of 1.5fr/9fr * 900px. This yields 150px.

The second, (3fr) will have a width of 3fr/9fr * 900px. This yields 300px.

The third, (3fr) will have a width of 4.5fr/9fr * 900px. This yields 450px.

With fractional units, a lot of flexibility is introduced. Make sure to enjoy the delight it brings to laying out contents with the CSS Grid layout.




