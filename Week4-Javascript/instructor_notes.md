# Instructor Notes: JavaScript Basics for Teens (Session 2 - Interactive Inputs & Calculations)

## Overview
This session builds on HTML/CSS by introducing JavaScript through practical, hands-on user inputs, numerical operations, button click events, and dynamically updating results on the page.

## Learning Objectives
By the end of this session, students will be able to:
1. Select HTML `<input>` elements using `document.getElementById()`.
2. Extract user input values using `.value`.
3. Convert text input strings into numbers using `Number()` or `parseFloat()`.
4. Perform basic arithmetic operations in JS (+, -, *, /).
5. Output calculation results back to the webpage DOM (`textContent` or `innerHTML`).

## Lesson Flow & Timing (60-90 minutes)
- **10 mins**: Recap HTML/CSS + Intro to JavaScript inputs & numbers (`.value` & `Number()`).
- **20 mins**: Live Demo & Walkthrough (Interactive Number Calculator & Result Display).
- **25 mins**: Hands-on Student Exercise (Tip / Bill Split Calculator).
- **10 mins**: Review, Live Debugging & Wrap-Up.

## Common Pitfalls & Troubleshooting Tips for Instructors
- **String Concatenation Trap**: Remind students that `input1.value + input2.value` will combine text (e.g., `"5" + "5"` becomes `"55"`). Explicitly highlight wrapping inputs in `Number()` to get numeric addition (`5 + 5 = 10`).
- **Empty Inputs (`NaN`)**: If a student clicks the add button before typing numbers, show them that `Number("")` evaluates to `0` or `NaN`.
- **Retrieving `.value` Too Early**: Ensure students read `.value` **inside** the button click event listener function, not globally at page load when the inputs are still empty.
