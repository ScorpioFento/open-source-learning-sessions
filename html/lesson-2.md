# Lesson 2 — HTML Forms & Inputs

**Path 1: HTML**  
Welcome to Lesson 2! In this lesson, we’ll learn how to create **forms and input fields**, which are essential for any interactive website.

---

## 🎯 Objectives
After this lesson you will be able to:
- Understand the purpose of HTML forms.
- Create input fields, text areas, radio buttons, checkboxes, and submit buttons.
- Organize forms using labels and fieldsets.
- Understand the `action` and `method` attributes of forms.

---

## 📝 What is a Form?
HTML forms allow users to **submit information** to a server.  
Think of forms as **the way websites interact with people** — login forms, contact forms, search boxes, surveys, etc.

---

## 🏗️ Basic Form Structure

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" placeholder="Enter your name" />

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="Enter your email" />

  <input type="submit" value="Submit" />
</form>
