# Lesson 4 — 📱 Responsive Layouts

**Path 2: CSS**  

Responsive design ensures that web pages **look good on all devices**, from large desktop screens to tablets and mobile phones. It allows your layout and content to adapt automatically to different screen sizes and orientations.

---

## 🎯 Objectives

After this lesson, you will be able to:

- Understand the principles of responsive web design.  
- Use CSS media queries to apply different styles for various screen sizes.  
- Combine flexible units, Flexbox, and Grid for responsive layouts.  
- Build mobile-first and adaptive designs.

---

## 📝 What is Responsive Design?

Responsive design is the practice of making your website **flexible and adaptive** so it works well on any device. Instead of creating separate websites for each device, you use CSS to **adjust layout, text, and images** dynamically.

---

## 🔹 Key Principles

1. **Fluid Grids:** Use relative units like `%` or `fr` instead of fixed pixels.  
2. **Flexible Images and Media:** Ensure images scale with their container using `max-width: 100%; height: auto;`.  
3. **Media Queries:** Apply different styles based on screen width or device type.  
4. **Mobile-First Approach:** Design for small screens first, then scale up for larger devices.  

---

## 🔹 CSS Media Queries

Media queries allow you to **apply styles conditionally** based on screen size, resolution, or other features.

```css
/* Mobile-first default */
body {
  font-size: 14px;
}

/* Tablet and up */
@media (min-width: 768px) {
  body {
    font-size: 16px;
  }
}

/* Desktop and up */
@media (min-width: 1024px) {
  body {
    font-size: 18px;
  }
}
