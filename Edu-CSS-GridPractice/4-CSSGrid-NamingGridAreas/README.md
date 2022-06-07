# title(){return this.options.title||this.options.name}

## Educative Frontend CSS-Grid Notes

Also revise below from Scrimba:

- [Become a professional React developer](https://scrimba.com/course/greact)
- [The Responsive Web Design Bootcamp](https://scrimba.com/course/gresponsive)
- [The Ultimate JavaScript Bootcamp](https://scrimba.com/course/gjavascript)
Happy Coding!


1. Naming and Positioning Items by Grid Areas:

   - Goal of this section is to learn to position grid items using grid areas:
   - A grid area is any area bounded by 4 grid lines, group of adjacent grid cells such as the entire row span below, may also account for a grid area.

2. How do you start using grid areas?

- logical place to begin is naming grid areas:
- Consider below code:
<div class="aside"></div>
<div class="main"></div>
<div class="footer"></div>

Now, see the naming in CSS for Grid Areas:

.main {
  grid-area: content;
}
.footer {
  grid-area: footer;
}
.aside {
  grid-area: sidebar;
}

=> The code block above says, let the .main element have an area name of content. Let the .footer element have an area name of footer. Finally, let the .aside class have a grid name of sidebar

- Now the same naming convention can be used in JS too:

var gridArea = "content"


**** Every grid item can be assigned to an area within the grid container ****
-> before doing that, it is imperative to attach the grid items to an area name. Like you assign variables in Javascript — sort of.





