# HTML Basics: Intro & Basic Document Structure  

**Path 1: HTML**  

HTML is the foundation of every web page. It defines the structure and content of a document that browsers can interpret and display.  

---

## Overview  

HTML (HyperText Markup Language) provides the skeleton of a web page. Elements such as headings, paragraphs, links, and images are written in HTML. Understanding its structure is essential for any front-end developer.  

---

## Basic HTML Document Structure  

Every modern web page starts with a declaration that tells the browser to use HTML5. Below is the standard, minimal structure of an HTML document:  

```html
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
        This is a simple HTML file. Edit it and refresh the browser to see the changes.
      </p>
      <p>
        Learn more:
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noopener">
          MDN HTML Documentation
        </a>
      </p>
    </main>

    <footer>
      <p>Goodbye</p>
    </footer>
  </body>
</html>
