# Exercise 3: Creating a Custom Visual Card Deck

## Core Challenge (Level 1)
Create a clean HTML directory layout paired with an external CSS style sheet. Create a page containing 3 custom "Hero Cards" profiling famous football teams or legendary players.

### Step-by-Step Instructions
1. Open VS Code and create `card_deck.html` and `style.css` next to each other in a folder.
2. Link the CSS file inside your HTML `<head>` using `<link rel="stylesheet" href="style.css">`.
3. In your HTML, create three distinct card layouts using paragraphs or headings.
4. Give each card a class attribute of `card`.
5. In `style.css`, target `.card` and give them a light background color, dark text, and a custom font.
6. Give one specific card an ID of `#champion` and overwrite its text color to a gold-yellow variant.

---

## Intermediate Challenge (Level 2)
1. Use the CSS `text-transform` property to make headers uppercase.
2. Experiment with hex codes to choose custom color palettes using an online picker (like Google's Color Picker). Use three different shades of your favorite color on your page.
3. Apply `text-align: center;` to your page elements.

---

## Extreme Challenge (Level 3 - Fast Finishers)
1. CSS styles apply "cascade" priorities. What happens if you style the same element using a tag selector (`p`), a class selector (`.card`), and an ID selector (`#champion`) all at once? Which color wins?
2. Write a brief inline style on one element and see if it defeats your external CSS rules. Discuss the concept of **specificity** with your instructor.