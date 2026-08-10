# Instructor Notes: Week 2, Session 2

## Visual Teaching Aid
Use the classroom whiteboard or an active live browser window inspection tool (Chrome DevTools). Open DevTools (`F12`), point to an element, and show the students the color-coded Box Model diagram at the bottom of the style tab (Margin is Orange, Border is Yellow, Padding is Green, Content is Blue). Seeing this instantly connects the terminology to their code layout actions.

## Common Bugs to Catch Early
* **Collapsing Margins:** Explain to advanced students that vertical margins sometimes overlap (e.g., if a top box has a bottom margin of 20px and the bottom box has a top margin of 20px, the gap between them is 20px, not 40px). 
* **The `*` Selector:** Ensure all students put the `* { box-sizing: border-box; }` reset snippet at the very top of their CSS file. It saves them countless layout formatting headaches during project cycles!