# Lesson 6: Advanced Flexbox (Flex Direction & Wrapping)

## Objectives
* Switch orientation configurations easily using the `flex-direction` property[cite: 28].
* Prevent content compression breakage via multi-line `flex-wrap` layout triggers[cite: 28].
* Build multi-row structured grids without standard CSS Grid engines[cite: 28].

## 1. Changing Tracks: `flex-direction`
By default, elements inside a flex system build into an end-to-end horizontal row[cite: 28]. We can instantly change this behavior by altering the main axis setting using `flex-direction`[cite: 28]:
* `flex-direction: row;` (Standard layout alignment behavior from left to right)[cite: 28].
* `flex-direction: column;` (Stacks items vertically from top to bottom, turning horizontal commands into vertical positioning controls)[cite: 28].

## 2. Preventing Squished Layouts: `flex-wrap`
If you jam 10 wide cards into a single flex row, the browser attempts to squash their sizing down to fit everything on one line[cite: 28]. Elements break out of their sizing rules and look crowded[cite: 28].

To fix this, we apply `flex-wrap: wrap;` onto the parent container[cite: 28]. This tells the browser: "If cards run out of space on this row, don't squash them—drop the extra cards down onto a new line below!"[cite: 28]