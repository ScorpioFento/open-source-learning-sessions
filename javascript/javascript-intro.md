# Lesson 1 — Introduction to JavaScript

**Path 1: JavaScript**  
Welcome to Lesson 1! In this lesson, we’ll learn the basics of **JavaScript**, the programming language that makes web pages interactive.

---

## 🎯 Objectives

After this lesson, you will be able to:

- Understand what JavaScript is and its role in web development.
- Learn how to include JavaScript in HTML files.
- Write basic JavaScript statements and use variables.
- Perform simple operations and output results.

---

## 📝 What is JavaScript?

JavaScript is a **high-level, interpreted programming language** that is widely used to create interactive and dynamic web pages. Unlike HTML and CSS, which structure and style content, JavaScript allows you to manipulate content, respond to user actions, and communicate with servers.

Key points:

- Runs in the browser and on the server (Node.js).
- Can manipulate HTML elements via the DOM.
- Supports variables, functions, loops, and events.
- Essential for modern web development.

---

## ⚡ Including JavaScript in HTML

You can include JavaScript in your webpage in two main ways:

1. **Inline** in the HTML file:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>JavaScript Example</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <script>
      alert("Hello from JavaScript!");
    </script>
  </body>
</html>
```

### Variable and data Types

```javascript
// Using let
let name = "John Doe";
let age = 21;

// Using const
const pi = 3.14159;

// Output to console
console.log("Name:", name);
console.log("Age:", age);
console.log("Pi:", pi);
```

```javascript
Common Data Types:

Number → 42, 3.14

String → "Hello"

Boolean → true / false

Array → [1, 2, 3]

Object → { name: "John Doe", age: 21 }
```

### ➕ Operators

```javascript
let x = 10;
let y = 5;

// Arithmetic
console.log(x + y); // 15
console.log(x - y); // 5
console.log(x * y); // 50
console.log(x / y); // 2

// Comparison
console.log(x > y); // true
console.log(x === y); // false
```
