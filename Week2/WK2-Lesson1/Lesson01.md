# Lesson 3: CSS Basics, Target Selectors, and Colors

## Objectives
* Understand how CSS (Cascading Style Sheets) connects to HTML.
* Distinguish between inline, internal, and external CSS style methods.
* Select elements using element tags, `.classes`, and `#ids`.
* Work with diverse color frameworks (Color keywords, Hex codes, and RGB).

## 1. What is CSS?
If HTML is the skeletal structure of our home, **CSS** is the paint on the walls, the tiling on the floors, and the styling of the curtains. It stands for **Cascading Style Sheets**. 

The word **Cascading** is crucial: it means styles flow down and overwrite each other based on hierarchy and specificity rules. If you tell the browser at the top of your sheet that all text is gray, but later specify that paragraphs are blue, the paragraphs cascade into blue!

## 2. Linking CSS to HTML (The 3 Methods)
* **Inline CSS:** Applied directly on a tag using a `style` attribute (Not recommended for big projects).
  ```html
  <p style="color: red;">Quick Style</p>
  ```
* **Internal CSS:** Written inside `<style>` tags within your HTML document's `<head>`.
* **External CSS (Best Practice):** Written in a separate `.css` file and linked in the HTML head.
  ```html
  <link rel="stylesheet" href="style.css">
  ```

## 3. The Anatomy of a CSS Rule
```css
h1 {
  color: darkblue;
  font-size: 24px;
}
```
* **Selector (`h1`):** Tells the browser exactly *which* element to target.
* **Declaration Block (`{ ... }`):** Contains one or more style declarations separated by semicolons.
* **Property (`color`):** The feature you want to change.
* **Value (`darkblue`):** The styling setting you want to apply.

## 4. Selector Power: Element, Class, and ID
To make styling targeted and clean, we avoid styling raw tags directly when we only want to change specific parts. Instead, we use:
* **Element Selector:** Targets all tags of that type (e.g., `p {}`).
* **Class Selector (`.name`):** Targets any element containing that class attribute. Can be reused as many times as you like! (e.g., `<p class="alert-text">` -> `.alert-text {}`).
* **ID Selector (`#name`):** Targets one highly specific element on the page. Must be unique to a single element! (e.g., `<p id="main-feature">` -> `#main-feature {}`).

## 5. Playing with Color Models
Browsers interpret colors in three main formats:
1. **Named Colors:** Simple keywords like `crimson`, `navy`, `forestgreen`.
2. **RGB (`rgb(Red, Green, Blue)`):** Defines light intensity values from `0` to `255`. (e.g., `rgb(255, 0, 0)` is solid red).
3. **Hexadecimal Codes (`#RRGGBB`):** Compact six-character codes representing RGB values in base-16. (e.g., `#0000FF` is pure blue, `#FF5733` is a trendy bright orange).