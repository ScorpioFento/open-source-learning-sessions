# Lesson 1 — 🎯 CSS Selectors & Basic Styling

**Path 2: CSS**

In this lesson, we’ll learn how to target HTML elements with **CSS selectors** and apply basic styling. Selectors allow you to apply styles precisely to elements, classes, IDs, and groups of elements.

---

## 🎯 Objectives

After this lesson, you will be able to:

- Understand the different types of CSS selectors.
- Apply styles using element, class, and ID selectors.
- Use grouping and combinators to target multiple elements.
- Understand pseudo-classes for interactive styling.

---

## 📝 What are CSS Selectors?

CSS selectors define **which HTML elements** the styles will apply to. They form the foundation of styling in CSS.

---

## 🔹 Types of CSS Selectors

1. **Element Selector**  
   Targets HTML tags directly.

```css
p {
  color: blue;
  font-size: 16px;
}
```

2. **Class Selector**

```css
.highlight {
  background-color: yellow;
  font-weight: bold;
}
```

```html
<p class="highlight">This text is highlighted.</p>
```

3. **ID Selector**

```css
#main-title {
  font-size: 24px;
  color: red;
}
```

```html
<h1 id="main-title">Welcome!</h1>
```

4. **Group Selector**

```css
h1,
h2,
h3 {
  font-family: Arial, sans-serif;
  margin-bottom: 10px;
}
```

5. **Descendant Selector**

```css
article p {
  line-height: 1.5;
}
```

6. **Pseudo-classes**

```css
a:hover {
  color: green;
  text-decoration: underline;
}

li:first-child {
  font-weight: bold;
}
```

## 🏗️ Code Example: Applying Selectors

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Selectors Example</title>
    <style>
      /* Element Selector */
      p {
        color: blue;
      }

      /* Class Selector */
      .highlight {
        background-color: yellow;
      }

      /* ID Selector */
      #main-title {
        font-size: 28px;
        color: red;
      }

      /* Group Selector */
      h1,
      h2 {
        font-family: Arial, sans-serif;
      }

      /* Descendant Selector */
      article p {
        line-height: 1.5;
      }

      /* Pseudo-class */
      a:hover {
        color: green;
      }
    </style>
  </head>
  <body>
    <h1 id="main-title">Welcome to CSS Selectors</h1>

    <p>This is a paragraph styled with an element selector.</p>
    <p class="highlight">This paragraph uses a class selector.</p>

    <article>
      <h2>Article Heading</h2>
      <p>Paragraph inside an article uses a descendant selector.</p>
    </article>

    <a href="#">Hover over me!</a>
  </body>
</html>
```
