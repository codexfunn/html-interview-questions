# 📊 HTML `<table>` Tag

---

## 📌 What Is the `<table>` Tag?

The `<table>` tag in HTML is used to display **tabular data** — information organized in rows and columns.

---

## 🧱 Basic Table Structure:

```html
<table>
  <thead>     <!-- Optional: Header -->
    <tr>
      <th>Heading 1</th>
      <th>Heading 2</th>
    </tr>
  </thead>

  <tbody>     <!-- Main data body -->
    <tr>
      <td>Row 1, Col 1</td>
      <td>Row 1, Col 2</td>
    </tr>
    <tr>
      <td>Row 2, Col 1</td>
      <td>Row 2, Col 2</td>
    </tr>
  </tbody>

  <tfoot>     <!-- Optional: Footer -->
    <tr>
      <td colspan="2">Footer Row</td>
    </tr>
  </tfoot>
</table>
```

---

## 🧩 Common Tags Inside a Table

| Tag       | Description                              |
| --------- | ---------------------------------------- |
| `<table>` | Container for the entire table           |
| `<tr>`    | Table row                                |
| `<td>`    | Table data cell                          |
| `<th>`    | Table header cell (bold + centered text) |
| `<thead>` | Group of header rows                     |
| `<tbody>` | Group of body rows                       |
| `<tfoot>` | Group of footer rows                     |
| `colspan` | Merge multiple columns into one          |
| `rowspan` | Merge multiple rows into one             |

---

## 🎨 Styling Tables with CSS

```css
table {
  width: 100%;
  border-collapse: collapse;
}
th, td {
  border: 1px solid #ccc;
  padding: 10px;
  text-align: left;
}
```

---

## ❓ Interview Questions

### 1. What’s the purpose of the `<table>` tag?

**Answer:** To display structured tabular data using rows and columns.

---

### 2. Difference between `<td>` and `<th>`?

**Answer:** `<td>` is a regular data cell, while `<th>` is a header cell (usually bold and centered).

---

### 3. What is `colspan` and `rowspan` in HTML tables?

**Answer:**

* `colspan` merges multiple **columns** into one cell
* `rowspan` merges multiple **rows** into one cell

---

### 4. Why use `<thead>`, `<tbody>`, and `<tfoot>`?

**Answer:** They improve **semantic meaning**, **styling**, and help with **JavaScript access** to different parts of the table.

---

## 🧠 Dev Tips

* Use tables only for **tabular data**, not for layout!
* Always close your `<td>` and `<th>` tags properly
* Combine with `<caption>` for accessible table titles

---

