# Lesson 3 — 🧩 CSS Grid

**Path 2: CSS**

CSS Grid is a powerful layout system that allows you to create **two-dimensional layouts** (rows and columns) easily. Unlike Flexbox, which is mostly one-dimensional (row or column), Grid handles both **horizontal and vertical placement** simultaneously.

---

## 🎯 Objectives

After this lesson, you will be able to:

- Understand the purpose of CSS Grid.
- Create grid containers and grid items.
- Define rows, columns, and gaps.
- Place items using lines, areas, and spans.
- Build responsive grid layouts.

---

## 📝 What is CSS Grid?

CSS Grid provides a way to **divide the page into rows and columns** and position items precisely in these grids. It is ideal for complex layouts like dashboards, galleries, and multi-column designs.

---

## 🔹 Basic Grid Concepts

- **Grid Container:** The parent element with `display: grid;`
- **Grid Items:** The children of a grid container arranged in rows and columns
- **Grid Lines:** The dividing lines between rows and columns
- **Grid Tracks:** The rows and columns themselves
- **Grid Gaps:** Space between rows and columns

---

## 🔹 Common Grid Properties

### On the Container

| Property                   | Description                          | Example                                   |
| -------------------------- | ------------------------------------ | ----------------------------------------- |
| display                    | Defines the container as grid        | `display: grid;`                          |
| grid-template-columns      | Define column sizes                  | `grid-template-columns: 100px 200px 1fr;` |
| grid-template-rows         | Define row sizes                     | `grid-template-rows: auto 100px;`         |
| gap / row-gap / column-gap | Space between items                  | `gap: 10px;`                              |
| justify-items              | Horizontal alignment of items        | `justify-items: center;`                  |
| align-items                | Vertical alignment of items          | `align-items: start;`                     |
| grid-auto-flow             | Auto-placement of items (row/column) | `grid-auto-flow: row;`                    |

### On the Items

| Property     | Description                   | Example               |
| ------------ | ----------------------------- | --------------------- |
| grid-column  | Span or start/end for columns | `grid-column: 1 / 3;` |
| grid-row     | Span or start/end for rows    | `grid-row: 2 / 4;`    |
| justify-self | Horizontal alignment of item  | `justify-self: end;`  |
| align-self   | Vertical alignment of item    | `align-self: center;` |

---

## 📦 Code Examples

### Basic Grid Container

```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
</div>
```

```css
.grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr; /* two columns */
  grid-template-rows: 100px 200px; /* two rows */
  gap: 10px;
  border: 1px solid #000;
  padding: 10px;
}

.grid-item {
  background-color: #f0f0f0;
  text-align: center;
  padding: 20px;
}
.grid-item:nth-child(1) {
  grid-column: 1 / 3; /* spans two columns */
  grid-row: 1 / 2;    /* spans one row */
}
```
