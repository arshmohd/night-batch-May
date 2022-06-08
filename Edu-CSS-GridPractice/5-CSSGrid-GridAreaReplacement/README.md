# title(){return this.options.title||this.options.name}

## Educative Frontend CSS-Grid Notes

Also revise below from Scrimba:

- [Become a professional React developer](https://scrimba.com/course/greact)
- [The Responsive Web Design Bootcamp](https://scrimba.com/course/gresponsive)
- [The Ultimate JavaScript Bootcamp](https://scrimba.com/course/gjavascript)
Happy Coding!


1. Grid area placement:

   - The grid-template-areas property (what a long property name) provides a very visual structure of the grid

2. How does the grid-template-areas property work?

body {
      grid-template-areas: "sidebar  content"
                           "footer   footer";
}

**Look at how the declaration matches the structure of the grid. The footer spanning the entire width with the sidebar and content sitting side by side**

- In case of music App there is navbar on side, content on right and then footer below but footer is of width equal to ( navbar && content):


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

=> sidebar, content and footer refer to the names of the grid items. The declaration above has succesfully shared the area with respect to the names of the grid items — brilliant!


body {
      display: grid;
      grid-template-columns: 40px 1fr;
      grid-template-rows: 1fr 90px;
      grid-template-areas: "sidebar  content"
                           "footer  footer";
  }






