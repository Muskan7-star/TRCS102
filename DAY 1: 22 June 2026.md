# Introduction to HTML

## What is HTML?
**HTML** stands for **HyperText Markup Language**. It is the standard markup language used worldwide to create and structure pages on the World Wide Web. 

HTML is **not a programming language** because it cannot execute logic, loops, or math operations. Instead, it is a **markup language** used to annotate, format, and structure text, images, and other multimedia content so that web browsers know exactly how to display them.

---

## Core Concepts Explained

### 1. HyperText
"HyperText" refers to the text that contains links to other text components or web pages. These connections are known as **hyperlinks**, allowing users to navigate dynamically between different pages with a single click.

### 2. Markup Language
A "Markup Language" is a system for annotating a document using special code structures called **tags** (enclosed in angle brackets, like `<html>` or `<body>`). These tags tell the browser whether a piece of text is a major heading, a regular paragraph, a bulleted list, or a hyperlink.

---

## The Structural Analogy
* **HTML (Structure):** Represents the architectural blueprint or the **skeleton** of a house.
* **CSS (Presentation):** Represents the interior design, paint colors, and layout aesthetics.
* **JavaScript (Behavior):** Represents the electrical wiring and plumbing that adds interactivity.

---
## Features:
* Features of HTML
* Easy to learn and use.
* Platform independent.
* Supports text, images, videos, and links.
* Forms the basic structure of every website.

---

## Common HTML Tags

### Heading Tags
`<h1>Heading 1</h1>` — Used for the main page heading (most important)  
`<h2>Heading 2</h2>` — Used for major sub-sections  
`<h3>Heading 3</h3>` — Used for sub-headings within sections  

### Paragraph Tag
`<p>This is a paragraph.</p>` — Used to define a block of regular text.  

### Formatting Tags
`<b>Bold Text</b>` or `<strong>Important Text</strong>` — Used to make text bold  
`<i>Italic Text</i>` or `<em>Emphasized Text</em>` — Used to italicize text  

### Structural & Layout Tags
`<div>` — A generic container used to group block-level elements together  
`<span>` — An inline container used to style specific words or phrases inside a sentence  

### Structural Modifiers
`<br>` — Inserts a single line break (does not require a closing tag)  
`<hr>` — Inserts a horizontal rule/line to visually separate content (does not require a closing tag)  

### Hyperlink & Media Tags
`<a href="url">Link Text</a>` — Creates a clickable hyperlink to another page  
`<img src="image.jpg" alt="description">` — Embeds an image into the webpage

### Basic Structure of an HTML Page
Every HTML document follows this fundamental layout:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a Main Heading</h1>
    <p>This is a paragraph of text.</p>
</body>
</html>
```
---
### Explanation of tags
| Tag | Purpose |
| :--- | :--- |
| `<!DOCTYPE html>` | Declares HTML5 documents |
| `<html>` | Root element of the webpage |
| `<head>` | Contains metadata |
| `<title>` | Sets the page title |
| `<body>` | Contains visible content |
| `<h1>` | Main heading |
| `<p>` | Paragraph |

---
### Output
* Displays headings.
* Shows paragraphs.
* Adds line breaks and horizontal lines.
* Formats text using bold, italic, and underline.
---

### Conclusion
**HTML** is the foundation of web development. It is used to create the structure of webpages and is the first step in learning frontend development.
