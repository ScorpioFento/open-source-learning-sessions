# 🎨 CSS Introduction & Basics

**Path 2: CSS**

Welcome to CSS! In this lesson, we’ll learn how to style HTML elements using **Cascading Style Sheets (CSS)**. CSS makes web pages visually appealing by controlling layout, colors, fonts, spacing, and more.

---

## 🎯 Objectives

After this lesson, you will be able to:

- Understand the purpose of CSS in web development.
- Apply CSS to HTML using inline, internal, and external styles.
- Use basic CSS properties such as color, background, font, and spacing.
- Understand the concept of the cascade, specificity, and inheritance.

---

## 📝 What is CSS?

CSS (Cascading Style Sheets) is a language used to describe the **presentation of HTML elements**. While HTML defines the structure, CSS defines **how it looks**.

Think of CSS as the **paint and style** on the skeleton that HTML provides.

---

## 🔹 Why Use CSS?

Using CSS allows you to:

1. **Separate content from design** – HTML handles structure, CSS handles style.
2. **Create visually appealing websites** – colors, fonts, spacing, and layout make pages user-friendly.
3. **Maintain consistency** – change a style once in a CSS file and it updates across all pages.
4. **Enhance readability and accessibility** – proper font sizes, spacing, and colors improve user experience.
5. **Save time** – reusable CSS classes and external stylesheets reduce repetitive coding.

---

## 🏗️ Ways to Apply CSS

1. **Inline CSS**  
   Applied directly in the HTML element using the `style` attribute.

   ```html
   <p style="color: blue; font-size: 18px;">Hello, world!</p>
   ```

2. **Internal CSS**

```html
<head>
  <style>
    p {
      color: green;
      font-size: 20px;
    }
  </style>
</head>
<body>
  <p>Hello World</p>
</body>
```

3. **External CSS**  
   Stored in a separate `.css` file and linked in the HTML `<head>` using `<link>`.

```html
<head>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <p>Hello World</p>
</body>
```

```css
/* styles.css */
p {
  color: red;
  font-size: 22px;
}
```
## 📦 Common CSS Properties Reference (for Beginners)

| Property            | Description                     | Example                         |
|--------------------|---------------------------------|---------------------------------|
| `color`             | Text color                      | `color: blue;`                  |
| `background-color`  | Background color                | `background-color: #f0f0f0;`   |
| `font-family`       | Font type                       | `font-family: Arial, sans-serif;` |
| `font-size`         | Text size                        | `font-size: 16px;`              |
| `font-weight`       | Boldness                         | `font-weight: bold;`            |
| `text-align`        | Text alignment                   | `text-align: center;`           |
| `margin`            | Outer spacing                    | `margin: 10px;`                 |
| `padding`           | Inner spacing                    | `padding: 5px;`                 |
| `border`            | Border around element            | `border: 1px solid black;`      |
| `width` / `height`  | Size of element                  | `width: 200px; height: 100px;` |
| `display`           | How element behaves              | `display: block; display: inline;` |
| `float`             | Positioning left or right        | `float: left; float: right;`    |
| `position`          | Position type                    | `position: relative; absolute; fixed;` |
| `text-decoration`   | Links or text decoration         | `text-decoration: underline;`   |
| `line-height`       | Space between lines of text      | `line-height: 1.5;`             |
| `letter-spacing`    | Space between letters            | `letter-spacing: 2px;`          |
| `background-image`  | Add a background image           | `background-image: url('img.jpg');` |
| `opacity`           | Transparency level               | `opacity: 0.8;`                 |

---

### 🧩 Practice Tip

1. Create an HTML page and experiment with at least **5 properties** from this table.  
2. Observe how `margin`, `padding`, `font-size`, `color`, and `background-color` change the appearance.  
3. Try combining multiple properties to style headings, paragraphs, and links.

---

**Congratulations!** 🎉  
You now have a clear reference for the most common CSS properties and can start styling your web pages with confidence.
