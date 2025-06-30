# ↔️ HTML Inline vs Block Elements

---

## 📌 What Are Inline and Block Elements?

In HTML, elements are categorized based on how they **behave in layout**:

* **Block-level elements**: Start on a new line and take up the full width available.
* **Inline elements**: Do NOT start on a new line and only take up as much width as necessary.

---

## 🧱 Block-Level Elements

### Characteristics:

* Always start on a **new line**
* Occupy **full width** of parent container
* Can contain **inline and other block elements**

### Examples:

```html
<div>, <p>, <h1> to <h6>, <ul>, <ol>, <li>, <section>, <article>, <main>, <header>, <footer>
```

### Example:

```html
<p>This is a paragraph.</p>
<h1>This is a heading</h1>
```

---

## 🧵 Inline Elements

### Characteristics:

* Do NOT start on a new line
* Take up **only the space needed**
* Cannot contain **block-level elements**

### Examples:

```html
<span>, <a>, <strong>, <em>, <img>, <input>, <label>, <br>
```

### Example:

```html
<span>This is inline text</span>
<a href="#">Link</a>
```

---

## 🎭 Visual Difference:

```html
<p>This is a <span>mix of inline</span> and block-level elements.</p>
```

> The `<p>` is a block element. The `<span>` inside behaves inline — no line break!

---

## ❓ Interview Questions

### 1. What’s the difference between inline and block elements?

**Answer:**

* Block elements take full width and break onto a new line.
* Inline elements stay on the same line and only occupy necessary space.

---

### 2. Can you nest block elements inside inline elements?

**Answer:** No, that’s invalid HTML. Inline elements should not contain block elements.

---

### 3. Is `<img>` inline or block?

**Answer:** Inline. Even though it looks big, it behaves inline.

---

### 4. Can an element behave both ways?

**Answer:** Yes. With CSS `display` property, you can change behavior using:

```css
display: inline;
display: block;
display: inline-block;
```

---

## 🧠 Dev Tips

* Use `inline-block` when you want inline behavior **with block-like layout control**
* Avoid wrapping block elements inside `<a>` or `<span>` unless using HTML5-safe nesting
* Use semantic block tags for better structure

---
