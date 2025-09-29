# GoodBye lesson — HTML Practice: Full Page Example

**Path 1: HTML**  

This is the final practice lesson. Here you will see **all the common HTML elements** you’ve learned in one page. This page uses **semantic HTML** and simple structures for easy practice. Open it in a browser to explore and understand how elements work together.

---

## 🧩 Full HTML Page Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Practice Page</title>
</head>

<body>

  <!-- Header & Navigation -->
  <header>
    <h1>Welcome to HTML Practice</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Content -->
  <main>

    <!-- Section with Text -->
    <section>
      <h2>Introduction</h2>
      <p>This is a practice page combining all HTML elements learned so far.</p>
    </section>

    <!-- Section with Lists -->
    <section>
      <h2>My Favorite Languages</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
      </ul>

      <h2>Steps to Open a Web Page</h2>
      <ol>
        <li>Write your HTML file in a text editor.</li>
        <li>Save it as index.html.</li>
        <li>Open it in your browser.</li>
      </ol>
    </section>

    <!-- Section with Form -->
    <section>
      <h2>Contact Form</h2>
      <form action="#" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name">

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email">

        <input type="submit" value="Submit">
      </form>
    </section>

    <!-- Section with Images, Links & Media -->
    <section>
      <h2>Media Example</h2>

      <img src="images/photo.jpg" alt="A beautiful landscape" width="300" height="200">

      <p>
        Learn more about HTML: 
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noopener">MDN HTML Docs</a>
      </p>

      <audio controls>
        <source src="audio/sample.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>

      <video width="320" height="240" controls>
        <source src="video/sample.mp4" type="video/mp4">
        Your browser does not support the video element.
      </video>
    </section>

    <!-- Section with Table -->
    <section>
      <h2>Sample Table</h2>
      <table border="1" cellpadding="5" cellspacing="0">
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
    </section>

    <!-- Section with Divs -->
    <section>
      <h2>Generic Div Example</h2>
      <div>
        <div>
          <h3>Inner Div 1</h3>
          <p>This is a nested div example.</p>
        </div>
        <div>
          <h3>Inner Div 2</h3>
          <p>Divs are useful for layout and grouping content.</p>
        </div>
      </div>
    </section>

  </main>

  <!-- Sidebar Example -->
  <aside>
    <h2>Sidebar</h2>
    <p>This is an aside section, useful for additional information or links.</p>
  </aside>

  <!-- Footer -->
  <footer>
    <p>© 2025 HTML Practice Page</p>
  </footer>

</body>
</html>
```