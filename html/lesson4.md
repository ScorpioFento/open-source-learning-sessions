# Lesson 4 — HTML Tables  

**Path 1: HTML**  

Tables are used to display structured data in rows and columns. They are ideal for presenting statistics, schedules, or any data that benefits from a grid layout.  

---

## 🗂️ Overview  

HTML tables organize information using a combination of rows (`<tr>`) and cells (`<td>` for data, `<th>` for headers). Proper table structure improves readability, accessibility, and semantic meaning.  

---

## 📊 Table Structure  

- `<table>`: Wraps the entire table.  
- `<thead>`: Contains header rows (`<th>`).  
- `<tbody>`: Contains data rows (`<td>`).  
- `<tfoot>`: Optional footer row for summaries or totals.  

---

## Code Example  

```html
<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>Country</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>25</td>
      <td>USA</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>30</td>
      <td>Canada</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>28</td>
      <td>UK</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">Total: 3 people</td>
    </tr>
  </tfoot>
</table>
```
