# 🏷️ HTML Attributes

---

## 📌 What Are HTML Attributes?

**HTML attributes** provide **additional information** about HTML elements. They are always included in the **opening tag** and are made up of a **name** and a **value**.

```html
<tagname attribute="value">Content</tagname>
```

### 🔹 Example:

```html
<img src="logo.png" alt="Site Logo" width="100" height="100">
```

Here, `src`, `alt`, `width`, and `height` are all **attributes** of the `<img>` tag.

---

## 🧱 Basic Structure of an Attribute

* Always written inside the **start tag**
* Follow the format: `attribute="value"`
* **Quotes are recommended**, but not required in modern HTML if value has no spaces

---

## 💼 Common HTML Attributes

| Attribute     | Description                      | Used With Tags            |
| ------------- | -------------------------------- | ------------------------- |
| `id`          | Unique identifier for an element | Any element               |
| `class`       | Assigns one or more classes      | Any element               |
| `style`       | Inline CSS styling               | Any element               |
| `title`       | Tooltip text on hover            | Any element               |
| `href`        | Specifies the URL for a link     | `<a>`                     |
| `src`         | Specifies the source file        | `<img>`, `<iframe>`, etc. |
| `alt`         | Alternative text for images      | `<img>`                   |
| `width`       | Width of an element              | `<img>`, `<video>`, etc.  |
| `height`      | Height of an element             | `<img>`, `<video>`, etc.  |
| `type`        | Defines input or button type     | `<input>`, `<button>`     |
| `value`       | Sets the value of form elements  | `<input>`, `<button>`     |
| `placeholder` | Hint text inside form fields     | `<input>`, `<textarea>`   |
| `disabled`    | Disables a form field            | `<input>`, `<button>`     |
| `readonly`    | Makes input field read-only      | `<input>`, `<textarea>`   |

---

## 🧠 Global Attributes

These can be applied to **any HTML element**:

* `id`
* `class`
* `style`
* `title`
* `lang`
* `data-*` (for storing custom data)

---

## ❓ Interview Questions on Attributes

### 1. What is an attribute in HTML?

**Answer:**
An attribute provides **extra information** about an HTML element. It is always specified in the **start tag** and comes in **name="value"** pairs.

---

### 2. What are global attributes?

**Answer:**
Global attributes can be used with **any HTML tag**, like `id`, `class`, `style`, `title`, etc.

---

### 3. Can you have multiple attributes in a single tag?

**Answer:**
Yes. Elements often have **multiple attributes**, each separated by a space:

```html
<input type="text" placeholder="Enter your name" disabled>
```

---

### 4. What is the `data-*` attribute?

**Answer:**
The `data-*` attribute is used to store **custom data** that can be accessed in JavaScript. Example:

```html
<div data-user-id="42">User</div>
```

---

## 💡 Dev Tips

* Use `alt` with all `<img>` tags for better accessibility & SEO
* Don’t overuse `style` — use CSS instead
* Use `id` for unique elements, `class` for reusable styling

---
