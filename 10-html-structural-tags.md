# 🧱 HTML Structural Tags

---

## 📌 What Are Structural Tags in HTML?

Structural tags define the **layout and structure** of a web page. They organize content into meaningful blocks and improve accessibility, SEO, and maintainability.

HTML5 introduced **semantic structural elements** that clearly describe their purpose.

---

## 🏗️ Common Structural Tags

| Tag         | Description                                        |
| ----------- | -------------------------------------------------- |
| `<header>`  | Top section of a page or section (logo, nav, etc.) |
| `<nav>`     | Navigation menus (links to other pages/sections)   |
| `<main>`    | Main content of the document                       |
| `<section>` | A logical group of content (thematic)              |
| `<article>` | Independent content (blog post, news, etc.)        |
| `<aside>`   | Side content (ads, related links)                  |
| `<footer>`  | Bottom section of a page (copyright, links)        |
| `<div>`     | Generic container (non-semantic)                   |

---

## 🧩 Example Layout:

```html
<body>
  <header>
    <h1>My Website</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Welcome</h2>
      <p>This is a section of the site.</p>
    </section>

    <article>
      <h2>Blog Post</h2>
      <p>This is an article.</p>
    </article>
  </main>

  <aside>
    <p>Related Links</p>
  </aside>

  <footer>
    <p>&copy; 2025 My Website</p>
  </footer>
</body>
```

---

## ❓ Interview Questions

### 1. What is the purpose of structural tags in HTML?

**Answer:** They provide meaningful structure to a page, helping with SEO, accessibility, and readability.

---

### 2. What’s the difference between `<section>` and `<div>`?

**Answer:**

* `<section>` is **semantic**, used for related content blocks with headings.
* `<div>` is **non-semantic**, a general-purpose container.

---

### 3. Can we have multiple `<header>` or `<footer>` tags?

**Answer:** Yes. You can have a `<header>` or `<footer>` for the entire page or inside specific sections/articles.

---

## 🧠 Dev Tips

* Use **semantic tags** over `<div>` where possible for better SEO and accessibility
* Group related content inside `<section>` or `<article>` with proper headings
* Keep a consistent structure for easy CSS layouting and responsiveness

---
