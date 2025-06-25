# 🔠 Difference Between `<h1>` to `<h6>` Tags

---

## 🧾 What Are `<h1>` to `<h6>` Tags?

The `<h1>` to `<h6>` tags in HTML are **heading tags** used to define headings in a web page.

* `<h1>` is the **highest-level heading** (most important)
* `<h6>` is the **lowest-level heading** (least important)

They represent a **hierarchical structure**, not just size!

---

## 🔁 Syntax Examples:

```html
<h1>This is an H1 heading</h1>
<h2>This is an H2 heading</h2>
<h3>This is an H3 heading</h3>
<h4>This is an H4 heading</h4>
<h5>This is an H5 heading</h5>
<h6>This is an H6 heading</h6>
```

Each lower level is visually smaller by default (but size can be changed with CSS).

---

## 📊 Key Differences Between `<h1>` to `<h6>`

| Tag    | Importance Level | Default Size (approx.)  | Use Case Example                     |
| ------ | ---------------- | ----------------------- | ------------------------------------ |
| `<h1>` | Highest          | Largest (usually 32px+) | Main page title                      |
| `<h2>` | High             | Smaller than `<h1>`     | Section title                        |
| `<h3>` | Medium-high      | Medium                  | Sub-section heading                  |
| `<h4>` | Medium           | Smaller                 | Sidebar or module title              |
| `<h5>` | Low              | Even smaller            | Minor headings                       |
| `<h6>` | Lowest           | Smallest                | Rarely used; footnotes, extra detail |

> ⚠️ You can style them however you want using CSS, but the **semantic meaning** stays the same.

---

## 🚦 Best Practices

* Always have **one `<h1>` per page** — it’s the main title.
* Use headings to build a **logical structure** — like a document outline.
* Don’t skip levels unnecessarily (e.g., don’t go from `<h1>` to `<h4>` directly).
* Headings help **screen readers** and **search engines** understand the content.

---

## ❓ Interview Questions

### 1. What is the difference between `<h1>` and `<h6>`?

**Answer:**
`<h1>` is the highest-level heading and should be used for the **main title**. `<h6>` is the lowest-level and is used for **least important** sub-headings.

---

### 2. Can we use multiple `<h1>` tags on a page?

**Answer:**
While HTML5 allows multiple `<h1>` tags inside different `<section>`s, it’s still best practice to use **one main `<h1>`** per page for SEO and accessibility.

---

### 3. Are `<h1>` to `<h6>` only for styling text sizes?

**Answer:**
No. They define the **structure and meaning** of content, not just style. Use CSS to control appearance.

---

## 💡 Dev Tip

Use heading tags to create an outline of your content, not to control font size. That’s what CSS is for. Think **structure first, style second**.
