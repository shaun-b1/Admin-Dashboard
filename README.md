# Admin-Dashboard
This is a task from The Odin Project's Intermediate HTML and CSS course. The goal the assignment was to cap off the Intermediate HTML and CSS course, implementing everything from forms to font and text styles, CSS selectors, positioning, variables, and CSS Grid.

## Design 
The design for the page is given below:

![Design wireframe](https://cdn.statically.io/gh/TheOdinProject/curriculum/main/html_css/grid-lessons/project-dashboard/dashboard-project.png)

## Implementation 
I used as many elements from the course as possible to ensure that I really used everything I had learned. All the main sections of the page are implemented using Grid, with the sidebar, header, and main body tags being the three main segments, and there being several more grids inside them. 

All colours, the `box-shadow` and the font are saved at the top of the CSS file, in the `:root` pseudo-element, so all colours can be changed from one spot. Most of the image colours are saved up here as well.

In the `header` bar, the search bar is a functional search form (although without a method to actually send information), and it works both with an enter key and pressing the magnifying glass that acts as a search button. The action buttons are also functional buttons, with a `:hover` pseudo-class applied so you can see the functional button. 

The `aside` has two fully functional `nav` elements, separated using grid. These were stripped of their default `link` css, and were styled to match the rest of the `aside`. 

The `main` section is split into two columns, with the main column holding the projects section, and the secondary column holding the announcements and trending section. These are broken up further with smaller grids inside; a 2x3 grid for the projects, and a 1x2 grid for the announcements and trends. They are broken up again by a 1x3 grid for the announcements, and a 1x4 grid for the trends. 

Overall, I'm pretty happy with how this turned out, although I think I could do more work on getting the padding to better fit in the grid sections, especially in the `main` section. 