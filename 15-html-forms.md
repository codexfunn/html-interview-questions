# 📝 HTML Forms

---

## 📌 What Is an HTML Form?

An HTML `<form>` is used to **collect user input** and send it to a server for processing. Forms are commonly used for login, registration, search, feedback, and more.

---

## 🔹 Basic Syntax

```html
<form action="/submit" method="POST">
  <!-- form elements go here -->
</form>
```

### Attributes:

| Attribute | Description                     |
| --------- | ------------------------------- |
| `action`  | The URL where form data is sent |
| `method`  | HTTP method (`GET` or `POST`)   |

---

## 🔘 Common Form Elements

| Element      | Purpose                         |
| ------------ | ------------------------------- |
| `<input>`    | For text, email, password, etc. |
| `<textarea>` | For multi-line input            |
| `<select>`   | Dropdown list                   |
| `<option>`   | Options inside `<select>`       |
| `<button>`   | Button to submit or reset       |
| `<label>`    | Describes input fields          |
| `<fieldset>` | Groups related fields           |
| `<legend>`   | Caption for `<fieldset>`        |

---

## 🧩 Input Types

```html
<input type="text">
<input type="password">
<input type="email">
<input type="checkbox">
<input type="radio">
<input type="submit">
<input type="file">
<input type="date">
```

---

## ✍️ Example Form:

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <input type="submit" value="Submit">
</form>
```

---

## ❓ Interview Questions

### 1. What is the purpose of the `<form>` tag?

**Answer:** To collect user input and send it to the backend server for processing.

---

### 2. Difference between GET and POST methods?

**Answer:**

* `GET`: Data is visible in the URL; used for non-sensitive data.
* `POST`: Data is sent in the body; used for secure or large data.

---

### 3. What does the `required` attribute do?

**Answer:** It ensures that a field must be filled out before submitting the form.

---

### 4. Can you explain how `<label>` improves accessibility?

**Answer:** It binds text to an input field, improving usability and screen reader support.

---

## 🧠 Dev Tips

* Use `name` attributes for every input — it's required to send data to the server
* Always use `label` with `for` and matching `id` for accessibility
* Use `fieldset` and `legend` to group related inputs
* Use proper input types for built-in validation (`email`, `number`, `url`, etc.)

---
