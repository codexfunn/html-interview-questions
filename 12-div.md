# 📦 HTML `<div>` Tag

---

## 📌 What is `<div>` in HTML?

The `<div>` tag stands for **division**. It’s a **container element** used to group HTML elements together.

It has **no semantic meaning** by default — it’s purely structural, used for layout and styling purposes.

---

## 🔹 Syntax:

```html
<div>
  <!-- content goes here -->
</div>
```

---

## 🧱 Use Cases of `<div>`

| Use Case               | Description                                          |
| ---------------------- | ---------------------------------------------------- |
| Grouping elements      | Wrap multiple tags together                          |
| Styling with CSS       | Apply class or ID to target for styling              |
| JavaScript interaction | Attach events (click, hover, etc.)                   |
| Layout structuring     | Build sections, cards, containers, flex/grid layouts |

---

## 📐 Example:

```html
<div class="card">
  <h2>Product Title</h2>
  <p>Price: $99</p>
</div>
```

Styled with CSS:

```css
.card {
  background-color: #f0f0f0;
  padding: 20px;
  border-radius: 8px;
}
```

---

## 🚫 `<div>` vs Semantic Tags

Using too many `<div>`s is called **div soup** — messy and unclear code.

### Better alternatives:

* Use `<header>`, `<main>`, `<section>`, `<footer>`, `<article>` when the purpose is clear
* Use `<div>` when there's **no better semantic choice**

---

## ❓ Interview Questions

### 1. What is a `<div>` tag used for?

**Answer:** It's a block-level container used to group HTML content for styling and layout purposes.

---

### 2. Is `<div>` a semantic element?

**Answer:** No, it is **non-semantic** — it does not describe its contents.

---

### 3. When should you avoid using `<div>`?

**Answer:** When a semantic tag (like `<section>`, `<nav>`, etc.) is more appropriate, or when overusing it leads to messy, hard-to-read HTML.

---

## 🧠 Dev Tips

* Use class names to make `<div>`s meaningful (e.g., `.container`, `.card`, `.wrapper`)
* Minimize nesting too many `<div>`s inside each other
* Keep accessibility in mind — semantic tags improve screen reader experience

---
