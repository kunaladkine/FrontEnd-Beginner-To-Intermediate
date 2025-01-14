# Day 1: HTML Basics and Tags

Welcome to Day 1 of learning HTML! This guide covers the basic structure of an HTML document and some commonly used tags like `<div>`, `<span>`, `<img>`, `<p>`, and heading tags. Each tag is explained with examples.

## What is HTML?
HTML (HyperText Markup Language) is the standard language for creating web pages. It provides the structure and content of a webpage.

---

## Basic Structure of an HTML Document
Every HTML document follows a standard structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to HTML Basics</h1>
</body>
</html>
```

### Explanation:
1. `<!DOCTYPE html>`: Defines the document type as HTML5.
2. `<html>`: The root element of the HTML document.
3. `<head>`: Contains metadata, such as the title and links to stylesheets.
4. `<title>`: Sets the title of the webpage (visible in the browser tab).
5. `<body>`: Contains the visible content of the webpage.

---

## Commonly Used Tags

### 1. `<div>`: Division Tag
The `<div>` tag is used to define a block-level container.

**Example:**
```html
<div>
    <h2>This is a section</h2>
    <p>This section contains some text and other elements.</p>
</div>
```
**Output:** A block containing a heading and a paragraph.

---

### 2. `<span>`: Inline Tag
The `<span>` tag is used for inline styling or grouping text within a block.

**Example:**
```html
<p>This is <span style="color: red;">highlighted</span> text.</p>
```
**Output:** The word "highlighted" appears in red.

---

### 3. `<img>`: Image Tag
The `<img>` tag is used to embed images in a webpage. It requires the `src` attribute to specify the image source and the `alt` attribute for alternative text.

**Example:**
```html
<img src="example.jpg" alt="Example Image" width="200" height="150">
```
**Output:** Displays an image with specified dimensions.

---

### 4. `<p>`: Paragraph Tag
The `<p>` tag defines a paragraph of text.

**Example:**
```html
<p>This is a simple paragraph of text.</p>
```
**Output:** Displays a block of text as a paragraph.

---

### 5. Heading Tags (`<h1>` to `<h6>`)
Heading tags define headings, with `<h1>` being the largest and `<h6>` the smallest.

**Example:**
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
**Output:** Displays headings in descending sizes from `<h1>` to `<h6>`.

---

### Putting It All Together
Here is an example combining all the tags:

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Basics</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
    <p>This is an introductory paragraph about HTML.</p>
    
    <div>
        <h2>About HTML</h2>
        <p>HTML stands for HyperText Markup Language.</p>
    </div>

    <p>Here is an example of an image:</p>
    <img src="example.jpg" alt="HTML Example Image">

    <p>Inline example with <span style="color: blue;">blue text</span>.</p>
</body>
</html>
```

---

### What's Next?
On Day 2, we'll dive into forms, lists, and tables to create more interactive and structured content. Keep practicing!

Feel free to clone this repository and edit the examples to test them on your own. Happy coding!
