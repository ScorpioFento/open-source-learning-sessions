# Lesson 1 — HTML Basics: Intro & Basic Document Structure

**Path 1: HTML**  
Welcome! This lesson introduces the basic HTML document structure you'll use in every web page. Read the explanation, try the example, then follow the short exercises.

---

## 🎯 Objectives

After this lesson you will be able to:

- Understand the purpose of HTML and where it fits in front-end development.
- Create a valid basic HTML document.
- Know what `<head>` and `<body>` contain and why `<meta>` tags matter.
- Open your HTML file in a browser and see the result.

---

## 🧭 Prerequisites

- VS Code (or any text editor)
- A web browser (Chrome, Firefox, Edge)
- Basic familiarity with files and folders

---

## 📘 What is HTML?

HTML (HyperText Markup Language) is the language used to describe the structure of web pages. Think of it as the **skeleton** of a page — headings, paragraphs, images, links, forms, and more.

---

## 🏗️ Basic HTML Document Structure (explained)

Below is the minimal, recommended HTML structure for modern webpages. Copy this into a file named `index.html` and open it in your browser.

```html
<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>My First HTML Page</title>
  </head>

  <body>
    <header>
      <h1>Welcome to HTML Basics</h1>
    </header>

    <main>
      <p>
        This is a simple HTML file. Edit it and refresh the browser to see
        changes.
      </p>

      <p>
        Learn more:
        <a
          href="https://developer.mozilla.org/en-US/docs/Web/HTML"
          target="_blank"
          rel="noopener"
          >MDN HTML docs</a
        >
      </p>
    </main>

    <footer>
      <p>GoodBye</p>
    </footer>
  </body>
</html>
```
