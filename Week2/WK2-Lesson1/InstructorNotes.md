# Instructor Notes: Week 2, Session 1

## Key Concept to Anchor
The concept of **Specificity (Priority Hierarchy)** is the hardest part of CSS for beginners. If they get confused about why their text isn't changing color, write this golden priority scale on the board:
1. **Inline style** (Attribute directly inside HTML) -> *Highest Priority*
2. **ID Selector** (`#id`)
3. **Class Selector** (`.class`)
4. **Element Selector** (`tag name`) -> *Lowest Priority*

## Common Student Hang-ups
* **Missing the Dot or Hash:** Students will write `card { ... }` instead of `.card { ... }` in CSS, or `#champion` in HTML instead of `id="champion"`. Remind them: The dots/hashes are *only* used in CSS, not HTML attribute declarations.
* **Typo in the link tag:** If their styles aren't applying at all, the CSS link in the HTML head is usually misspelled or the path is incorrect. Teach them to use VS Code auto-completion to prevent typos!