# 🔗 HTML `<a>` Tag (Anchor Tag)

---

## 📌 What is the `<a>` Tag?

The `<a>` tag stands for **anchor**. It is used to **create hyperlinks** in HTML. These links can connect to:

* Another webpage
* A section on the same page
* An email address
* A file to download

---

## 🔹 Basic Syntax:

```html
<a href="URL">Link Text</a>
```

### Example:

```html
<a href="https://www.google.com">Visit Google</a>
```

---

## 🔐 Common Attributes:

| Attribute  | Description                                           |
| ---------- | ----------------------------------------------------- |
| `href`     | URL or path to navigate to (required)                 |
| `target`   | Where to open the link (`_blank`, `_self`, etc.)      |
| `title`    | Tooltip text shown when hovering                      |
| `download` | Prompts user to download the linked resource          |
| `rel`      | Defines relationship (`noopener`, `noreferrer`, etc.) |

### Example with Attributes:

```html
<a href="resume.pdf" download target="_blank" title="Download Resume">
  Download My Resume
</a>
```

---

## 🎯 Anchor for Internal Links:

```html
<a href="#section2">Go to Section 2</a>
...
<h2 id="section2">Section 2</h2>
```

> Use `#id` to jump to specific sections of the same page.

---

## 📧 Anchor for Email Links:

```html
<a href="mailto:someone@example.com">Email Me</a>
```

---

## ☎️ Anchor for Phone Links:

```html
<a href="tel:+1234567890">Call Us</a>
```

---

## ❓ Interview Questions

### 1. What does the `<a>` tag do?

**Answer:** It defines a hyperlink used to navigate to another page, file, or section of the same page.

---

### 2. What are the uses of the `target` attribute in the anchor tag?

**Answer:**

* `_self`: default, opens in the same tab
* `_blank`: opens in a new tab/window
* `_parent`, `_top`: advanced frame usage (rare)

---

### 3. Can we use anchor tags for downloads?

**Answer:** Yes. Add the `download` attribute to prompt file download instead of opening it.

---

### 4. What is the difference between absolute and relative URLs?

**Answer:**

* Absolute: full URL (e.g., `https://example.com/page`)
* Relative: path based on the current file (e.g., `./page.html`)

---

## 🧠 Dev Tips

* Always use `target="_blank"` + `rel="noopener noreferrer"` for external links
* Anchor tags can be styled with CSS to look like buttons or nav items
* Avoid using `#` alone in `href` — it scrolls to the top unnecessarily

---
