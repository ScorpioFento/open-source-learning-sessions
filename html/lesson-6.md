# Lesson 6 — Semantic HTML  

**Path 1: HTML**  

Semantic HTML uses elements that **clearly describe their meaning and purpose** to both browsers and developers. Unlike generic containers like `<div>`, semantic elements convey **structural and contextual information**, which improves accessibility, SEO, and code maintainability.

---

## 🧩 Overview  

Semantic HTML helps developers create web pages that are **easier to read, maintain, and interpret**. It communicates the role of each section of a page, both to browsers and assistive technologies like screen readers.  

From a **technical SEO perspective**, semantic HTML is crucial because:

- Search engines use semantic tags to **understand the structure and hierarchy** of content.  
- Elements like `<header>`, `<main>`, `<article>`, and `<footer>` help search engines **index content accurately**.  
- Proper semantic usage improves **rich results and snippet generation** in search engines.  
- Using semantic HTML reduces the chance of misinterpreted content and ensures **better ranking and visibility**.  

Common semantic elements include:

- `<header>` – defines introductory content or navigation links.  
- `<nav>` – contains navigation menus.  
- `<main>` – represents the main content of a document.  
- `<section>` – groups related content together.  
- `<article>` – represents a self-contained piece of content.  
- `<aside>` – contains content tangentially related to the main content.  
- `<footer>` – defines footer information, such as copyright or contact info.  

Using semantic HTML **reduces the reliance on `<div>` tags**, making web pages more meaningful, accessible, and optimized for search engines.

---

## 📦 Code Examples  

### Basic Page Structure with Semantic Elements  

```html
<header>
  <h1>My Website</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>

<main>
  <section>
    <h2>Latest Articles</h2>
    <article>
      <h3>Understanding HTML</h3>
      <p>HTML structures web content using semantic elements.</p>
    </article>
    <article>
      <h3>CSS Basics</h3>
      <p>CSS styles web pages with visual presentation rules.</p>
    </article>
  </section>

  <aside>
    <h2>Sidebar</h2>
    <p>Additional links and resources.</p>
  </aside>
</main>

<footer>
  <p>© My Website</p>
</footer>
```