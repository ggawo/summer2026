# Creating a Webpage Menu with HTML & CSS

## Overview

This lesson teaches students how to build a simple, accessible website menu using semantic HTML and CSS. We'll cover the HTML structure for navigation, styling the menu with CSS, adding hover/focus effects, and making the menu work on small screens.

## Learning Objectives

- Understand the purpose of the `nav`, `ul`, `li`, and `a` elements.
- Build a horizontal navigation menu using CSS Flexbox.
- Add hover and focus styles for better user experience.
- Make the menu responsive so it stacks on small screens.
- Apply simple accessibility improvements (meaningful link text, keyboard focus).

## Prerequisites

- Basic familiarity with HTML tags and structure.
- Basic CSS knowledge (selectors, properties like `display`, `padding`, `color`).

## Vocabulary

- Navigation (`nav`) — the section that holds links to site pages.
- List (`ul` / `li`) — used to group menu items.
- Link (`a`) — clickable menu item.
- Flexbox — CSS layout tool useful for horizontal menus.

## Lesson Steps (Instructor Notes)

1. HTML structure
   - Use a `nav` element with `aria-label` to indicate the navigation region.
   - Inside `nav`, create an unordered list (`ul`). Each menu item is an `li` containing an `a`.
   - Example:

```html
<nav aria-label="Main">
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
```

2. CSS basics for menus
   - Remove default list styles with `list-style: none; margin: 0; padding: 0;`.
   - Use `display: flex;` on the `ul` to lay out items in a row.
   - Style the `a` elements with padding, background color, and rounded corners to make them look like buttons.

3. Hover and focus states
   - Add `:hover` and `:focus` styles to make it clear when a link is interactive.
   - Use `outline` or background change to support keyboard users.

4. Responsive design
   - Use a media query (e.g., `@media (max-width: 520px)`) and set `flex-direction: column` to stack items vertically on small screens.

5. Accessibility tips
   - Use descriptive link text (avoid “click here”).
   - Ensure focus styles are visible for keyboard users.
   - Use `aria-label` on `nav` if there are multiple navigation areas.

## Instructor Activity Plan

- 5 minutes: Explain HTML structure and vocabulary.
- 10 minutes: Live-code the nav structure into an HTML file.
- 10 minutes: Add CSS to style the menu and demonstrate `display: flex`.
- 10 minutes: Add hover/focus states and show the effect of media queries.
- 15 minutes: Students complete the exercise and share results.

## Assessment

- Ask students to create a menu with at least four links, styled using CSS, that stacks on small screens and shows visible focus styles when tabbing.

## Extensions / Challenges

- Add a dropdown submenu under one `li` using absolute positioning.
- Use CSS variables to let students change colors easily.
- Animate the hover state smoothly with `transition`.

## Resources

- Demo files in this folder: `index.html`, `style.css`, and `starter.html`.
