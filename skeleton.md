Question :
What happens to the layout when you resize the screen to less than 550 px. How do you think that works?

Answer :
When the window is resized to be less than 550 px wide the grid structure is changed so that the content in columns are now stacked rather than placed side by side.
This is done so that as the screen resolution gets smaller, the layout that is best suited, is applied (or vice versa).
Media queries are used so that the browser is asked as to the resolution, the resulting answer defines the CSS rule sets to then be applied.