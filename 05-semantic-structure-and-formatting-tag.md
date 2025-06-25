# 🧱 Semantic, Structural, and Formatting Tags in HTML

---

## 🧠 What Are Semantic Tags?

**Semantic HTML** means using HTML elements that clearly describe their meaning — both to the browser **and** developers.

> Example: `<article>` is semantic, `<div>` is not.

### ✅ Benefits:

* Improves **SEO** and **accessibility**
* Makes code **easier to read & maintain**
* Helps screen readers and search engines understand your content better

### 🔹 Common Semantic Tags:

| Tag         | Purpose                           |
| ----------- | --------------------------------- |
| `<header>`  | Defines a page or section header  |
| `<nav>`     | Navigation links                  |
| `<main>`    | Main content of the page          |
| `<article>` | Independent, self-contained block |
| `<section>` | Group of related content          |
| `<aside>`   | Sidebar / related content         |
| `<footer>`  | Bottom/footer of section/page     |

---

## 🧱 What is Structure in HTML?

The **structure** of an HTML page refers to how content is **logically organized** from top to bottom.

### 🔹 Basic Structure Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <header>Site Header</header>
    <nav>Navigation Bar</nav>
    <main>
      <section>
        <article>
          <h1>Blog Post Title</h1>
          <p>Post content...</p>
        </article>
      </section>
    </main>
    <footer>Site Footer</footer>
  </body>
</html>
```

This structure helps browsers, search engines, and devs understand the **hierarchy** of content.

---

## ✍️ What Are Formatting Tags?

Formatting tags are used to **style text content** in a simple way (inline level, not layout-based).

### 🔹 Common Formatting Tags:

| Tag        | Use                              |
| ---------- | -------------------------------- |
| `<b>`      | Bold text (without importance)   |
| `<strong>` | Important bold text              |
| `<i>`      | Italic text (no emphasis)        |
| `<em>`     | Emphasized text                  |
| `<u>`      | Underlined text                  |
| `<mark>`   | Highlighted text                 |
| `<sup>`    | Superscript                      |
| `<sub>`    | Subscript                        |
| `<br>`     | Line break                       |
| `<hr>`     | Horizontal rule (thematic break) |

> ⚠️ Avoid overusing formatting tags for design — use **CSS** for that instead.

---

## ❓ Interview Questions

### 1. What is semantic HTML?

**Answer:**
Semantic HTML uses tags that describe the meaning of the content they contain (like `<article>`, `<nav>`, etc.). It improves accessibility, SEO, and code clarity.

---

### 2. Why is structure important in HTML?

**Answer:**
A well-structured page ensures that content is organized logically and hierarchically, making it easier for browsers, screen readers, and devs to understand the layout.

---

### 3. What is the difference between semantic and non-semantic tags?

**Answer:**

* **Semantic:** Tags like `<section>`, `<article>`, `<nav>` — their purpose is clear.
* **Non-semantic:** Tags like `<div>`, `<span>` — have no meaning by themselves.

---

### 4. What are formatting tags? Give examples.

**Answer:**
Formatting tags affect how inline text looks. Examples include `<b>`, `<i>`, `<strong>`, `<u>`, `<mark>`, `<sup>`, `<sub>`.

---

## 💡 Dev Tips

* Use **semantic tags** to replace `<div>` wherever possible.
* Keep HTML **clean and well-structured**.
* Use formatting tags only when there's a **semantic reason**, not just for style.

---
