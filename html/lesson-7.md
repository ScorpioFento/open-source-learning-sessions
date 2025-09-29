# Lesson 7 — 📈 SEO (Search Engine Optimization) & Semantic HTML

**Path 1: HTML**

In this lesson, we explore how **semantic HTML improves SEO** (Search Engine Optimization). Using the right HTML elements ensures that search engines can **understand, index, and rank your web pages effectively**. Proper structure also improves **accessibility** for screen readers and other assistive technologies.

---

## 🔹 Why Semantic HTML Helps SEO

- **Better Content Understanding**  
  Search engines can interpret `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>` to determine what content is important.

- **Improved Accessibility**  
  Semantic tags help screen readers understand content, indirectly contributing to SEO since accessibility is a ranking factor.

- **Rich Snippets & Featured Results**  
  Proper use of headings (`<h1>`–`<h6>`), lists, tables, and media allows search engines to generate rich snippets in search results.

- **Keyword Hierarchy**  
  Using `<h1>` for main titles, `<h2>` for sections, `<h3>` for subsections, etc., signals content hierarchy and keyword relevance.

---

## 🔹 Key Semantic Elements & Their SEO Role

| Element       | Purpose / Role                          | SEO Benefit |
|---------------|----------------------------------------|-------------|
| `<header>`    | Introductory content or navigation     | Helps search engines identify site header info |
| `<nav>`       | Navigation menus                        | Signals main navigation links for crawlability |
| `<main>`      | Primary page content                     | Indicates core content to search engines |
| `<section>`   | Thematic grouping of content            | Organizes content into meaningful sections |
| `<article>`   | Self-contained content                  | Each article can be indexed independently |
| `<aside>`     | Related or supplemental content         | Marks secondary content for search engines |
| `<footer>`    | Footer information like contact or copyright | Provides consistent site info |
| `<figure>` + `<figcaption>` | Images with captions             | Improves accessibility and context |
| `<h1>`–`<h6>` | Headings                                | Defines content hierarchy and keywords |
| `<table>`     | Structured data                         | Helps search engines parse tabular info |
| `<strong>` / `<em>` | Emphasis                           | Highlights important content for SEO |

---

## 🔹 SEO Principles with Semantic HTML

1. **Single `<h1>` per page**  
   - Represents the main topic of the page.  

2. **Hierarchical headings (`<h2>` → `<h3>` → `<h4>`)**  
   - Break content into logical, SEO-friendly sections.  

3. **Use `<main>` for core content**  
   - Helps search engines quickly identify the primary information.  

4. **Wrap independent content in `<article>`**  
   - Ideal for blog posts, tutorials, or news items.  

5. **Group related content in `<section>`**  
   - Improves readability and indexing of thematic content.  

6. **Navigation with `<nav>`**  
   - Makes internal linking and site structure clear for SEO.  

7. **Sidebar content in `<aside>`**  
   - Indicates secondary or supporting information.  

8. **Footer content in `<footer>`**  
   - Includes copyright, contact info, or site policies consistently.  

9. **Descriptive links**  
   - Use anchor text that clearly describes the target page instead of “click here”.  

10. **Alt attributes for images**  
    - Improves SEO and accessibility by describing images.  

---

## 🔹 Example: SEO-Friendly Semantic HTML Structure

```html
<header>
  <h1>HTML & SEO Practice Page</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Blog</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>

<main>
  <section>
    <h2>Introduction to Semantic HTML</h2>
    <p>Semantic HTML improves both accessibility and search engine understanding.</p>
  </section>

  <section>
    <h2>Articles</h2>
    <article>
      <h3>Understanding HTML Structure</h3>
      <p>Using semantic tags such as &lt;header&gt;, &lt;main&gt;, &lt;section&gt;, and &lt;article&gt; helps SEO.</p>
    </article>
    <article>
      <h3>Using Forms Correctly</h3>
      <p>Properly labeled forms improve usability and search engine comprehension.</p>
    </article>
  </section>

  <aside>
    <h2>Related Resources</h2>
    <ul>
      <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML">MDN HTML Docs</a></li>
      <li><a href="#">SEO Best Practices</a></li>
    </ul>
  </aside>
</main>

<footer>
  <p>© HTML & SEO Practice Page</p>
</footer>
```

🏗️ Code Example: Applying Selectors