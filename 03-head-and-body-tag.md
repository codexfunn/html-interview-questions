# 📃 `<head>` and `<body>` Tags in HTML

---

## 📖 What is the `<head>` Tag?

The `<head>` tag is used to contain **metadata** and other elements that aren't directly shown on the webpage. It sits **above the visible part** of the document and provides critical information about the page.

### 🔹 Common elements inside `<head>`:

* `<title>` – Title shown in the browser tab
* `<meta>` – Metadata (like character encoding, keywords, description)
* `<link>` – Linking external files (CSS, favicon, etc.)
* `<style>` – Internal CSS
* `<script>` – JS files to be loaded in the head

### ✅ Example:

```html
<head>
  <title>My Web Page</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
</head>
```

---

## 🌍 What is the `<body>` Tag?

The `<body>` tag contains **everything visible on the webpage** — all content like text, images, buttons, forms, videos, etc.

### ✅ Example:

```html
<body>
  <h1>Welcome to My Website</h1>
  <p>This is a sample paragraph.</p>
  <img src="hero.jpg" alt="Hero Image">
</body>
```

---

## ❓ Interview Questions

### 1. What is the role of the `<head>` tag?

**Answer:**
The `<head>` tag holds metadata and links to resources like stylesheets and scripts. It's used for information **about the page**, not for content displayed **on** the page.

---

### 2. What does the `<body>` tag contain?

**Answer:**
All the **visible content** of the webpage such as headings, paragraphs, images, videos, forms, buttons, and more.

---

### 3. Can we have multiple `<head>` or `<body>` tags?

**Answer:**
No. A valid HTML document should have only **one `<head>`** and **one `<body>`**. Multiple tags can break rendering.

---

### 4. Can scripts be placed inside `<body>`?

**Answer:**
Yes, and it’s often **recommended** to place scripts at the end of `<body>` for better performance — so that HTML content loads first before JS is executed.

---

## 💡 Dev Tips

* Always include `<meta charset="UTF-8">` in the head for character encoding.
* Use `<meta name="viewport">` for mobile responsiveness.
* Place critical CSS in the head, and defer non-critical JS to the end of body.

