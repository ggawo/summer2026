# Exercise 2: Building a Multi-Page Tournament Guide

## Core Challenge (Level 1)
Expand your tournament fan hub by building a completely separate, standalone roster schedule page and linking your files together cleanly.

### Step-by-Step Instructions
1. Open VS Code and open your project directory. 
2. Create a new file right next to your session 1 profile file named `roster.html`.
3. Set up the standard modern HTML shell framework.
4. Add an `<h1>` specifying your team's name along with the phrase "Official Roster & Strategy".
5. Use an **unordered list (`<ul>`)** to list out at least 4 key starting players.
6. Use an **ordered list (`<ol>`)** to break down the step-by-step game-day warm-up routine for the squad.
7. Use an `<a>` anchor tag on your main homepage file that links directly to `roster.html`.
8. Add an anchor link inside `roster.html` that returns the user back to your homepage.

---

## Intermediate Challenge (Level 2)
Integrate dynamic visual media elements into your layouts.
1. Find a sports image URL online, or copy a dynamic image address directly from your favorite site.
2. Embed the image at the top of your `roster.html` page using the `<img >` tag.
3. Make sure to define a clear, meaningful `alt` text attribute describing the image action.
4. Control the layout dimensions by applying the `width="400"` attribute directly inside the tag.

---

## Extreme Challenge (Level 3 - Fast Finishers)
1. Learn about the `target="_blank"` attribute for anchor tags.
2. Apply it to an external link directing fans to an online match highlights video clip.
3. Fix the image path layout behavior: What happens if you deliberately create an empty folder named `images`, place an image file inside it, and try to point your code directly to `src="images/myphoto.png"`? Write out the relative file layout tracking structure correctly.