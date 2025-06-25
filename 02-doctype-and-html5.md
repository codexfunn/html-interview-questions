# 📘 `<!DOCTYPE html>` and HTML5

---

## 🧞 What is `<!DOCTYPE html>`?

`<!DOCTYPE html>` is a **declaration** that tells the browser:

> “This document is written using HTML5.”

It helps the browser know how to **render the page correctly** using **standards mode** rather than quirks mode.

---

## ❓ Interview Questions on DOCTYPE

### 1. What is `<!DOCTYPE html>` and why is it important?

**Answer:**
It tells the browser to render the page in **standards mode** using the HTML5 specification. Without it, browsers may enter **quirks mode**, causing unexpected rendering issues.

---

### 2. Is `<!DOCTYPE html>` an HTML tag?

**Answer:**
No. It is a **document type declaration**, not an HTML tag. It doesn’t render anything on the page and doesn’t need a closing tag.

---

### 3. How is the HTML5 DOCTYPE different from older versions?

**Answer:**
HTML5:

```html
<!DOCTYPE html>
```

HTML4 (complicated):

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
```

HTML5 made it **simpler**, dropping the DTD and keeping only a clean one-liner.

---

## 🌐 What is HTML5?

### ✅ Definition:

**HTML5** is the **latest and most widely used version** of the HTML standard.
It was created to:

* Provide a **cleaner, more semantic structure**.
* Reduce the need for external plugins (like Flash).
* Make web pages more **interactive, responsive, and mobile-friendly**.
* Introduce **built-in APIs** and **form validation**.

> Released by W3C in 2014, HTML5 is now the **default standard** across all modern browsers.

---

## 🔥 Key Features of HTML5

### 🔹 1. Semantic Tags:

* `<header>`, `<footer>`, `<section>`, `<article>`, `<nav>`, `<aside>`

### 🔹 2. Multimedia Support:

* `<audio>`, `<video>` elements with native playback — **no plugins needed**.

### 🔹 3. Input & Forms:

* New input types: `email`, `url`, `date`, `number`, etc.
* Built-in validation with `required`, `min`, `pattern`, `step`, etc.

### 🔹 4. Graphics:

* `<canvas>` element for drawing graphics via JS.
* **SVG** support for scalable vector images.

### 🔹 5. Powerful APIs:

* **Geolocation API**
* **Web Storage API** (`localStorage`, `sessionStorage`)
* **Web Workers** (background processing)
* **Drag-and-Drop API**
* **WebSockets** for real-time data

---

## ❓ Interview Questions on HTML5

### 1. What is HTML5?

**Answer:**
HTML5 is the latest version of HTML that provides new **semantic elements**, built-in support for **multimedia**, advanced **form controls**, and **browser-side APIs** for building modern, interactive web applications.

---

### 2. How is HTML5 better than previous versions?

**Answer:**

* Cleaner syntax (`<!DOCTYPE html>`)
* Semantic tags
* Multimedia support without plugins
* Built-in form validation
* Access to APIs like geolocation, storage, canvas

---

### 3. What are semantic tags in HTML5?

**Answer:**
Semantic tags define the **meaning** of the content inside them.
Examples: `<article>`, `<nav>`, `<section>`, `<aside>`, `<header>`, `<footer>`
They help with **SEO**, **accessibility**, and **code clarity**.

---

### 4. What new input types were introduced in HTML5?

**Answer:**

* `email`
* `tel`
* `url`
* `number`
* `range`
* `date`
* `color`
  These inputs improve user experience and allow built-in validation.

---

## 💡 Dev Tip

* Always use semantic HTML5 tags — it’s good for SEO, accessibility, and teamwork.
* Avoid `<div>` soup! Use meaningful tags instead.

```
