# CSS Styles Cheat Sheet

This guide lists basic CSS properties, what they do, and common values you can use.

## 1. Color

### `color`

- Changes the text color.
- Example values:
  - `red`
  - `blue`
  - `green`
  - `#ff0000`
  - `rgb(255, 0, 0)`

### `background-color`

- Changes the background color of an element.
- Example values:
  - `white`
  - `black`
  - `yellow`
  - `#00ff00`
  - `rgba(0, 0, 0, 0.5)`

## 2. Text

### `font-size`

- Changes the size of the text.
- Example values:
  - `12px`
  - `16px`
  - `20px`
  - `1.5em`

### `font-family`

- Changes the font style.
- Example values:
  - `Arial, sans-serif`
  - `Verdana, sans-serif`
  - `Times New Roman, serif`

### `font-weight`

- Changes how thick or bold the text looks.
- Example values:
  - `normal`
  - `bold`
  - `bolder`
  - `lighter`

### `text-align`

- Aligns text horizontally.
- Example values:
  - `left`
  - `center`
  - `right`
  - `justify`

### `text-decoration`

- Adds decoration to text.
- Example values:
  - `none`
  - `underline`
  - `line-through`
  - `overline`

## 3. Box Model

### `width`

- Sets the width of an element.
- Example values:
  - `100px`
  - `50%`
  - `auto`

### `height`

- Sets the height of an element.
- Example values:
  - `50px`
  - `100%`
  - `auto`

### `padding`

- Adds space inside an element.
- Example values:
  - `10px`
  - `20px 10px`
  - `5px 10px 15px 20px`

### `margin`

- Adds space outside an element.
- Example values:
  - `10px`
  - `20px auto`
  - `5px 10px 15px 20px`

### `border`

- Adds a border around an element.
- Example values:
  - `1px solid black`
  - `2px dashed red`
  - `3px solid #333`

## 4. Layout

### `display`

- Controls how an element is displayed.
- Example values:
  - `block`
  - `inline`
  - `inline-block`
  - `flex`
  - `grid`

### `position`

- Sets the positioning method for an element.
- Example values:
  - `static`
  - `relative`
  - `absolute`
  - `fixed`

### `top`, `right`, `bottom`, `left`

- Move an element from its normal position.
- Example values:
  - `0`
  - `10px`
  - `50%`

### `float`

- Moves an element to the left or right.
- Example values:
  - `left`
  - `right`
  - `none`

## 5. Styling

### `background`

- A shorthand for background color and image settings.
- Example values:
  - `red`
  - `url('image.jpg')`
  - `linear-gradient(red, yellow)`

### `border-radius`

- Rounds the corners of an element.
- Example values:
  - `5px`
  - `10px`
  - `50%`

### `box-shadow`

- Adds a shadow behind an element.
- Example values:
  - `2px 2px 5px gray`
  - `0 0 10px black`

## 6. Common CSS Values

- `auto` = browser decides the value
- `none` = no value / no effect
- `hidden` = hide something
- `visible` = show something
- `center` = center alignment
- `solid` = solid border line
- `dashed` = dashed border line

## 7. Basic Example

```css
h1 {
  color: blue;
  font-size: 30px;
  text-align: center;
}

button {
  background-color: green;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
}
```

## Quick Reminder

CSS is written like this:

```css
selector {
  property: value;
}
```

Examples:

- `p { color: red; }`
- `div { background-color: yellow; }`
- `h2 { text-align: center; }`
