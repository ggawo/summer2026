# Lesson 5: Introduction to CSS Flexbox (Aligning Elements)

## Objectives
* Understand the core concept of a Parent (Flex Container) vs. Children (Flex Items)[cite: 31].
* Activate Flexbox layouts using `display: flex;`[cite: 31].
* Control horizontal distribution using `justify-content`[cite: 31].
* Control vertical alignment using `align-items`[cite: 31].

## 1. What is Flexbox?
Imagine you are placing physical box objects inside a shipping container[cite: 31]. Without Flexbox, block elements naturally stack vertically on top of each other like heavy bricks[cite: 31]. 

When you apply `display: flex;` to a parent container, it acts like a magic magnetic field[cite: 31]. All immediate child items instantly line up horizontally in a row and stretch or shrink dynamically to fit the space[cite: 31].

## 2. Parent Container vs. Child Items
Flexbox properties are strictly split based on where you apply them[cite: 31]:
* **The Flex Container (Parent):** The outer box that controls the overall magnetic layout grid[cite: 31].
* **The Flex Items (Children):** The individual inner items moving dynamically inside the grid[cite: 31].

## 3. The Two Direction Alignment Controls
Once a parent is set to `display: flex;`, you control the elements using two main alignment properties[cite: 31]:

### A. `justify-content` (Main Axis / Horizontal Alignment)
Controls how items spread out across the horizontal row width[cite: 31]:
* `flex-start`: Smashes all items tightly together to the left side (default)[cite: 31].
* `center`: Gathers all items cleanly directly in the absolute horizontal center[cite: 31].
* `space-between`: Pushes the first and last items to the outer edges, distributing remaining space perfectly between them[cite: 31].
* `space-around`: Pushes items out with equal white space around every individual element[cite: 31].

### B. `align-items` (Cross Axis / Vertical Alignment)
Controls how items align up and down within the container's height[cite: 31]:
* `stretch`: Stretches items vertically to match the height of the tallest item (default)[cite: 31].
* `center`: Centers items vertically relative to the container's height baseline[cite: 31].
* `flex-end`: Pushes all items flat against the bottom edge of the container box[cite: 31].