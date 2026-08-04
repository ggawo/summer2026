# HTML Tags Reference

A quick reference of the most commonly used HTML tags, organized by category.

---

# 1. Document Structure

| Tag               | Purpose                                      | Example                                    |
| ----------------- | -------------------------------------------- | ------------------------------------------ |
| `<!DOCTYPE html>` | Declares the document as HTML5.              | `<!DOCTYPE html>`                          |
| `<html>`          | Root element of an HTML document.            | `<html lang="en">`                         |
| `<head>`          | Contains metadata, links to CSS, title, etc. | `<head>...</head>`                         |
| `<title>`         | Browser tab title.                           | `<title>My Website</title>`                |
| `<meta>`          | Metadata (charset, viewport, SEO).           | `<meta charset="UTF-8">`                   |
| `<link>`          | Links external files like CSS.               | `<link rel="stylesheet" href="style.css">` |
| `<script>`        | Includes JavaScript.                         | `<script src="app.js"></script>`           |
| `<style>`         | Internal CSS.                                | `<style>body{}</style>`                    |
| `<body>`          | Contains all visible webpage content.        | `<body>...</body>`                         |

---

# 2. Headings

HTML provides six heading levels.

| Tag    | Purpose           |
| ------ | ----------------- |
| `<h1>` | Main page heading |
| `<h2>` | Section heading   |
| `<h3>` | Subsection        |
| `<h4>` | Smaller heading   |
| `<h5>` | Minor heading     |
| `<h6>` | Smallest heading  |

Example:

```html
<h1>Main Title</h1>
<h2>Section</h2>
<h3>Subsection</h3>
```

---

# 3. Text Formatting

| Tag            | Purpose                  |
| -------------- | ------------------------ |
| `<p>`          | Paragraph                |
| `<br>`         | Line break               |
| `<hr>`         | Horizontal line          |
| `<strong>`     | Important text (bold)    |
| `<b>`          | Bold text                |
| `<em>`         | Emphasized (italic)      |
| `<i>`          | Italic                   |
| `<u>`          | Underline                |
| `<small>`      | Smaller text             |
| `<mark>`       | Highlighted text         |
| `<sup>`        | Superscript              |
| `<sub>`        | Subscript                |
| `<code>`       | Inline code              |
| `<pre>`        | Preformatted text        |
| `<blockquote>` | Long quotation           |
| `<span>`       | Generic inline container |

Example:

```html
<p>This is <strong>important</strong> text.</p>

<p>Water is H<sub>2</sub>O.</p>

<p>E = mc<sup>2</sup></p>
```

---

# 4. Links

| Tag   | Purpose   |
| ----- | --------- |
| `<a>` | Hyperlink |

Example:

```html
<a href="https://example.com"> Visit Website </a>
```

Common attributes:

- href
- target
- title
- download

Example:

```html
<a href="about.html"> About Us </a>

<a href="https://google.com" target="_blank"> Google </a>
```

---

# 5. Images

| Tag     | Purpose           |
| ------- | ----------------- |
| `<img>` | Displays an image |

Example:

```html
<img src="images/photo.jpg" alt="Mountain" width="500" />
```

Important attributes:

- src
- alt
- width
- height
- loading

---

# 6. Lists

## Unordered List

```html
<ul>
  <li>Apple</li>
  <li>Orange</li>
</ul>
```

## Ordered List

```html
<ol>
  <li>Step One</li>
  <li>Step Two</li>
</ol>
```

## Description List

```html
<dl>
  <dt>HTML</dt>
  <dd>Markup language</dd>
</dl>
```

Tags:

- `<ul>`
- `<ol>`
- `<li>`
- `<dl>`
- `<dt>`
- `<dd>`

---

# 7. Tables

Example:

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>

  <tr>
    <td>Alice</td>
    <td>20</td>
  </tr>
</table>
```

Common tags:

| Tag         | Purpose      |
| ----------- | ------------ |
| `<table>`   | Table        |
| `<tr>`      | Table row    |
| `<th>`      | Header cell  |
| `<td>`      | Data cell    |
| `<thead>`   | Table header |
| `<tbody>`   | Table body   |
| `<tfoot>`   | Table footer |
| `<caption>` | Table title  |

---

# 8. Containers

These tags organize page layout.

| Tag      | Purpose          |
| -------- | ---------------- |
| `<div>`  | Block container  |
| `<span>` | Inline container |

Example:

```html
<div class="card">
  <h2>Title</h2>
  <p>Description</p>
</div>
```

---

# 9. Semantic Layout Elements

Semantic tags describe the meaning of content.

| Tag            | Purpose                |
| -------------- | ---------------------- |
| `<header>`     | Top of page or section |
| `<nav>`        | Navigation menu        |
| `<main>`       | Main content           |
| `<section>`    | Major section          |
| `<article>`    | Independent content    |
| `<aside>`      | Sidebar                |
| `<footer>`     | Footer                 |
| `<figure>`     | Image or media         |
| `<figcaption>` | Caption                |
| `<address>`    | Contact information    |

Example:

```html
<header>
  <h1>My Website</h1>
</header>

<nav>...</nav>

<main>
  <section></section>
</main>

<footer></footer>
```

---

# 10. Forms

Forms collect user input.

## Form

```html
<form></form>
```

Common tags:

| Tag          | Purpose            |
| ------------ | ------------------ |
| `<form>`     | Form container     |
| `<input>`    | User input         |
| `<textarea>` | Multi-line input   |
| `<button>`   | Button             |
| `<label>`    | Field label        |
| `<select>`   | Dropdown           |
| `<option>`   | Dropdown item      |
| `<fieldset>` | Group fields       |
| `<legend>`   | Fieldset title     |
| `<datalist>` | Suggestions        |
| `<output>`   | Calculation result |

---

# 11. Common Input Types

```html
<input type="text" />

<input type="password" />

<input type="email" />

<input type="number" />

<input type="date" />

<input type="checkbox" />

<input type="radio" />

<input type="file" />

<input type="color" />

<input type="range" />

<input type="submit" />
```

---

# 12. Buttons

```html
<button>Click Me</button>
```

Button types:

```html
<button type="submit">Submit</button>

<button type="button">Normal Button</button>

<button type="reset">Reset</button>
```

---

# 13. Audio & Video

Video:

```html
<video controls></video>
```

Audio:

```html
<audio controls></audio>
```

Tags:

- `<video>`
- `<audio>`
- `<source>`
- `<track>`

---

# 14. Embedded Content

| Tag        | Purpose                 |
| ---------- | ----------------------- |
| `<iframe>` | Embed another webpage   |
| `<embed>`  | Embed external resource |
| `<object>` | External object         |

Example:

```html
<iframe src="https://example.com"> </iframe>
```

---

# 15. Useful Global Attributes

Nearly every HTML tag supports these attributes.

| Attribute         | Purpose             |
| ----------------- | ------------------- |
| `id`              | Unique identifier   |
| `class`           | CSS class           |
| `style`           | Inline CSS          |
| `title`           | Tooltip             |
| `hidden`          | Hide element        |
| `tabindex`        | Keyboard navigation |
| `contenteditable` | Editable text       |
| `draggable`       | Drag-and-drop       |
| `lang`            | Language            |
| `dir`             | Text direction      |

Example:

```html
<div id="header" class="container" title="Main Header"></div>
```

---

# 16. Frequently Used HTML Attributes

## Links

```html
href target download rel
```

## Images

```html
src alt width height loading
```

## Forms

```html
name value placeholder required readonly disabled checked selected maxlength min
max step
```

---

# 17. HTML Comments

```html
<!-- This is a comment -->
```

---

# 18. Character Entities

| Entity   | Result |
| -------- | ------ |
| `&nbsp;` | Space  |
| `&lt;`   | <      |
| `&gt;`   | >      |
| `&amp;`  | &      |
| `&copy;` | ©      |
| `&reg;`  | ®      |
| `&quot;` | "      |

---

# 19. HTML5 Semantic Page Template

```html
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>My Website</title>

    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <header>
      <h1>Website Title</h1>
    </header>

    <nav></nav>

    <main>
      <section>
        <article>
          <h2>Article Title</h2>

          <p>Content goes here.</p>
        </article>
      </section>

      <aside></aside>
    </main>

    <footer></footer>

    <script src="script.js"></script>
  </body>
</html>
```

---

# 20. Most Important Tags to Learn First

If you're just getting started, focus on mastering these tags:

1. `<html>`
2. `<head>`
3. `<body>`
4. `<h1>`–`<h6>`
5. `<p>`
6. `<div>`
7. `<span>`
8. `<a>`
9. `<img>`
10. `<ul>`
11. `<ol>`
12. `<li>`
13. `<table>`
14. `<form>`
15. `<input>`
16. `<button>`
17. `<label>`
18. `<header>`
19. `<nav>`
20. `<main>`
21. `<section>`
22. `<article>`
23. `<footer>`
24. `<script>`
25. `<link>`

Mastering these tags will enable you to build the vast majority of modern websites.
