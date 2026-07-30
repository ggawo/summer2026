# Instructor Notes: Week 1, Session 2

## Time Management Guide
* **00:00 - 00:10:** Review and Recap. Display a few student layouts from Session 1 on the screen. Highlight correct header nesting hierarchies.
* **00:10 - 00:25:** Live Demo. Write out a clean list element template. Show how links work locally by creating two dead simple files (`a.html` and `b.html`) and linking them together. 
* **00:25 - 00:50:** Lab Session. Actively track relative asset linking errors.
* **00:50 - 01:00:** Group Review. Explain the extreme risk of broken hot-linked URLs vs local folder mapping models.

## Troubleshooting Quick-Fix List
1. **The Broken Image Icon:** If an image doesn't display and instead shows broken alt text, check for typo elements inside the URL string or check for missing quotation marks around the path attribute parameters (`src=myphoto.jpg` instead of `src="myphoto.jpg"`).
2. **Nesting Layout Accidents:** Look out for students writing text blocks nested raw between list wrapping parents like `<ul>Text<li>Item</li></ul>`. Reinforce the rule: The only elements allowed as direct children of `<ul>` or `<ol>` are `<li>` tags. Everything else must sit inside the list item!