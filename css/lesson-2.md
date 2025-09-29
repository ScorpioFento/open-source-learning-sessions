# Lesson 2 — 🧩 CSS Flexbox

**Path 2: CSS**

Flexbox is a CSS layout module that makes it easier to design **flexible and responsive layouts**. It allows you to align and distribute space among items in a container, even when their size is unknown or dynamic.

---

## 🎯 Objectives

After this lesson, you will be able to:

- Understand the purpose of Flexbox.
- Create flex containers and flex items.
- Align, justify, and distribute space within a flex container.
- Build responsive layouts using Flexbox.

---

## 📝 What is Flexbox?

Flexbox (Flexible Box) provides an efficient way to **arrange elements in a row or column**. It simplifies common layout tasks like centering, spacing, and ordering elements without using floats or positioning.

---

## 🔹 Basic Flexbox Concepts

- **Flex Container:** The parent element with `display: flex;`
- **Flex Items:** The children of a flex container that are arranged automatically.

---

## 🔹 Common Flexbox Properties

### On the Container

| Property        | Description                   | Example                    |
| --------------- | ----------------------------- | -------------------------- |
| display         | Defines the container as flex | `display: flex;`           |
| flex-direction  | Row or column layout          | `flex-direction: row;`     |
| justify-content | Align items horizontally      | `justify-content: center;` |
| align-items     | Align items vertically        | `align-items: center;`     |
| flex-wrap       | Wrap items to next line       | `flex-wrap: wrap;`         |
| gap             | Space between items           | `gap: 10px;`               |

### On the Items

| Property   | Description                  | Example                   |
| ---------- | ---------------------------- | ------------------------- |
| flex       | Grow, shrink, and basis      | `flex: 1 1 100px;`        |
| order      | Change display order         | `order: 2;`               |
| align-self | Override container alignment | `align-self: flex-start;` |

---

## 📦 Code Examples

### Basic Flex Container

```html
<div class="flex-container">
  <div class="flex-item">1</div>
  <div class="flex-item">2</div>
  <div class="flex-item">3</div>
</div>
```

```css
.flex-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
  border: 1px solid #000;
  padding: 10px;
}

.flex-item {
  background-color: #f0f0f0;
  padding: 20px;
  text-align: center;
  flex: 1;
}
```

### Align individual item

```css
.flex-item:nth-child(2) {
  align-self: flex-start;
}
```


### 💡 Reference for Beginners: CSS-Tricks Flexbox Guide https://css-tricks.com/snippets/css/a-guide-to-flexbox/
 — keep it bookmarked to explore all flex properties visually.
