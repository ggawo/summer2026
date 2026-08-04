# Lesson 1: How the Web Works & Your First Tag

## Objectives

- Understand the Client-Server model using the "Restaurant Analogy."
- Write, save, and render a basic HTML document locally.
- Use headings (`<h1>` to `<h6>`) and paragraphs (`<p>`) correctly.

## The Big Picture: How Does the Internet Work?

Think of the internet like a giant restaurant:

1. **The Client (You):** You sit at a table and look at a menu. You ask the waiter for a burger.
2. **The Server (The Remote Computer):** The waiter takes your request to the kitchen (the server), where the chefs prepare your food.
3. **The Response:** The waiter brings the burger back to your table.

In web dev, your **Web Browser** (Chrome, Edge, Safari) is the client making a request, and **HTML** is the actual food delivered to your plate. HTML stands for **HyperText Markup Language**—it isn't a programming language; it's a blueprint that tells the browser _what_ content to display.

## Anatomy of an HTML Element

Most tags act like sandwiches; they need a top bun (opening tag) and a bottom bun (closing tag).

```html
<p>This is a paragraph of text!</p>
│ └────────── Content ─────────┘ │ └─ Opening Tag Closing Tag ─┘
<div>...</div>
```

## Core Structural Tags

Every webpage requires a basic structural shell to tell the browser how to interpret it:

- `<!DOCTYPE html>`: Declares that this is a modern HTML5 document.
- `<html>`: The root container for the whole page.
- `<head>`: Contains invisible setup info (like the page title shown on the browser tab).
- `<body>`: Contains everything visible to the user.
