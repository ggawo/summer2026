# Lesson 2: Links, Lists, Images, and Paths

## Objectives
* Understand the absolute vs. relative path difference when sourcing assets.
* Implement ordered (`<ol>`) and unordered (`<ul>`) lists cleanly.
* Embed responsive images using the `<img>` tag alongside `src` and `alt` attributes.
* Create hyperlinks using the anchor (`<a>`) tag to connect multiple local pages together.

## 1. Organizing Data: Lists
When displaying structured data on the web, we use two main types of lists:
* **Unordered Lists (`<ul>`):** Bulleted lists where order doesn't explicitly matter (e.g., a list of ingredients or equipment).
* **Ordered Lists (`<ol>`):** Numbered lists where the sequential order is critical (e.g., recipe instructions or leaderboard standings).

Every individual item within either list type must be wrapped inside a List Item (`<li>`) tag.

## 2. Bringing Pages to Life: Images
The image tag (`<img>`) is unique: it is an **empty element** (also called a self-closing tag), meaning it does not wrap text and does not require a closing `</img>` tag. Instead, it relies on attributes:
* `src`: The source path pointing directly to your image file.
* `alt`: Alternative text that describes the image for screen readers or displays if the image fails to load.

```html
<img src="logo.png" alt="World Cup Tournament official logo">
```

## 3. Connecting the Web: Hyperlinks
The anchor tag (`<a>`) transforms standard text into a clickable link. It relies on the `href` (hypertext reference) attribute to declare the destination URL or target filename.
```html
<a href="https://www.fifa.com">Visit Official Site</a>
```
To force a link to open cleanly in a brand-new browser tab without kicking the user off your current site, attach the `target="_blank"` attribute.