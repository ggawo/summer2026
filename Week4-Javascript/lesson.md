# Lesson: Getting Input, Adding Numbers & Showing Results

## 1. How JavaScript Interacts with Inputs
When a user types into an HTML `<input>` field, JavaScript can grab that content using its `.value` property.

```html
<input type="number" id="user-age" placeholder="Enter your age">
```

```javascript
const ageInput = document.getElementById('user-age');
// Read what the user typed inside an event listener:
let userAge = ageInput.value; 
```

---

## 2. Converting Text to Numbers
Everything retrieved from an HTML `<input>` comes in as **text (a String)**.

If you try to add two inputs without converting them:
```javascript
let num1 = "5";
let num2 = "10";
console.log(num1 + num2); // Output: "510" (Text sticking together!)
```

To perform math, wrap the input values inside `Number()`:
```javascript
let num1 = Number(document.getElementById('num1').value);
let num2 = Number(document.getElementById('num2').value);

let sum = num1 + num2; // Output: 15 (Actual addition!)
```

---

## 3. The Full Pattern: Read, Calculate, Display

```html
<!-- HTML Structure -->
<input type="number" id="numA" placeholder="First Number">
<input type="number" id="numB" placeholder="Second Number">
<button id="addBtn">Add Numbers</button>

<h2 id="result">Result: --</h2>
```

```javascript
// JavaScript Logic
const numAInput = document.getElementById('numA');
const numBInput = document.getElementById('numB');
const addBtn = document.getElementById('addBtn');
const resultHeading = document.getElementById('result');

addBtn.addEventListener('click', function() {
    // 1. Read input values and convert to numbers
    let valA = Number(numAInput.value);
    let valB = Number(numBInput.value);

    // 2. Do the math
    let total = valA + valB;

    // 3. Display the result on screen
    resultHeading.textContent = "Result: " + total;
});
```
