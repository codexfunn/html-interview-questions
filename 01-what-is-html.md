# 📘 What is HTML?

**HTML (HyperText Markup Language)** is the standard markup language used to create the **structure** of web pages.  
It describes **what** elements are on the page and **how** they are organized, using tags like `<p>`, `<h1>`, `<div>`, `<a>`, etc.

> HTML = Skeleton of the webpage. CSS = Skin. JavaScript = Brain.

---

## ❓ Interview Questions with Answers

### 1. What is HTML and why is it used?
**Answer:**  
HTML is a markup language used to structure content on the web. It provides a way to define text, links, images, forms, and other elements in a structured way that browsers can interpret and render as web pages.

---

### 2. Is HTML a programming language? Why or why not?
**Answer:**  
No, HTML is **not** a programming language. It does not contain logic like conditions, loops, or functions.  
It's a **markup language** — it only defines the structure and layout of content.

---

### 3. How is HTML different from CSS or JavaScript?
**Answer:**  
| Language   | Role                        |
|------------|-----------------------------|
| HTML       | Structure (skeleton)        |
| CSS        | Styling (appearance/skin)   |
| JavaScript | Behavior (logic/brain)      |

They work **together** to build modern web applications.

---

### 4. What happens when a browser loads an HTML page?
**Answer:**  
- The browser downloads the HTML file.
- It parses it **top to bottom**.
- Builds the **DOM (Document Object Model)** tree.
- Then fetches linked CSS, JS, images.
- Applies styles and runs JS to render the final page.

---

### 5. Explain the basic structure of an HTML document.
**Answer:**
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
