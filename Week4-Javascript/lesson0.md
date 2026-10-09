# Lesson: Adding Interactivity with JavaScript

## 1. What is JavaScript?

Think of a webpage as a human body:

- **HTML** is the skeleton (structure).
- **CSS** is the skin and clothing (style and design).
- **JavaScript** is the brain (behavior and interactivity).

JavaScript makes your page react when users click buttons, type text, or hover over elements!

---

## 2. Connecting JavaScript to HTML

You link a JavaScript file (`script.js`) to your HTML file (`index.html`) using the `<script>` tag right before `</body>`:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Interactive Page</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Hello, JavaScript!</h1>

    <script src="script.js"></script>
  </body>
</html>
```

---

## 3. The 3 Steps to Interactivity

### Step 1: Find the Element (Selection)

To change something, JS first needs to find it. Give your HTML element an `id`:

```html
<button id="myBtn">Click Me!</button>
```

In JavaScript:

```javascript
const myButton = document.getElementById("myBtn");
```

### Step 2: Listen for User Action (Events)

Tell JavaScript to wait for an event, like a `click`:

```javascript
myButton.addEventListener("click", function () {
  alert("Button was clicked!");
});
```

### Step 3: Change Something (Manipulation)

Update text, styles, or classes dynamically:

```javascript
const heading = document.getElementById("main-heading");
heading.textContent = "You changed me!";
heading.style.color = "blue";
```
