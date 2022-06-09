# title(){return this.options.title||this.options.name}

## Educative Frontend CSS-Grid Notes

Also revise below from Scrimba:

- [Become a professional React developer](https://scrimba.com/course/greact)
- [The Responsive Web Design Bootcamp](https://scrimba.com/course/gresponsive)
- [The Ultimate JavaScript Bootcamp](https://scrimba.com/course/gjavascript)
Happy Coding!

===== Responsive Design  ========
Media Queries #
Media queries are at the heart of responsive design. They let you target specific screen sizes and specify code to be run on the devices alone.

1. Redefining Grid Areas with Media Queries:

   - The Grid areas you create within the parent grid container are not set in stone. The grid areas can be changed based on the screen size of the user’s device.

2. Refactoring for a mobile first approach:
   - single column.
   - 2 rows: content and footer.
body{
    margin: 0;
    padding: 0;
    display: grid;
    min-height: 100vh;
    min-width: 100vw;
    grid-template-rows: 1fr 90px;
    grid-template-columns: 1fr;
    grid-template-areas: "content"
                         "footer";
}

- once we have the we would address desktop approach in media query:
- Notice that rows for both mobile and desktop remain same:
- In case of mobile: there is only 1 column.


@media screen and (min-width: 600px) {
  body {
    display: grid;
    grid-template-rows: 1fr 90px;
    grid-template-columns: 45px 1fr;
    grid-template-areas: "sidebar content"
                         "footer footer";
  }
}







