# Exercise: Simple Tip & Total Calculator

## Goal
Build a webpage where users can enter a restaurant bill amount and the tip percentage they want to leave, then click a button to calculate the tip amount and the final total!

## Student Instructions
1. Create an `index.html` file with:
   - Input `#bill` for the total bill amount.
   - Input `#tip-percent` for the tip percentage (e.g., enter 15 for 15%).
   - A button `#calc-btn` that says "Calculate Total".
   - A `div` or `h3` with `id="output"` to display the calculated result.
2. Link your `script.js` file.
3. In `script.js`:
   - Add a click event listener to `#calc-btn`.
   - Read both input values and convert them to numbers.
   - Calculate the tip amount: `tipAmount = bill * (tipPercent / 100)`.
   - Calculate the total bill: `total = bill + tipAmount`.
   - Update `#output` to display: "Tip: $X | Total Bill: $Y".

---

# Solution Code

### `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tip & Total Calculator</title>
    <style>
        body { font-family: sans-serif; max-width: 400px; margin: 40px auto; text-align: center; }
        input { display: block; width: 90%; padding: 10px; margin: 10px auto; font-size: 16px; }
        button { padding: 10px 20px; font-size: 16px; background: #28a745; color: white; border: none; border-radius: 5px; cursor: pointer; }
        .output-box { margin-top: 20px; padding: 15px; background: #e9ecef; border-radius: 5px; font-size: 20px; font-weight: bold; }
    </style>
</head>
<body>

    <h2>💵 Tip Calculator</h2>
    <input type="number" id="bill" placeholder="Bill Amount ($)">
    <input type="number" id="tip-percent" placeholder="Tip % (e.g. 15)">
    <button id="calc-btn">Calculate Total</button>

    <div class="output-box" id="output">Result: $0.00</div>

    <script src="script.js"></script>
</body>
</html>
```

### `script.js`
```javascript
const billInput = document.getElementById('bill');
const tipPercentInput = document.getElementById('tip-percent');
const calcBtn = document.getElementById('calc-btn');
const outputBox = document.getElementById('output');

calcBtn.addEventListener('click', function() {
    let bill = Number(billInput.value);
    let tipPercent = Number(tipPercentInput.value);

    let tipAmount = bill * (tipPercent / 100);
    let total = bill + tipAmount;

    outputBox.textContent = "Tip: $" + tipAmount.toFixed(2) + " | Total: $" + total.toFixed(2);
});
```
