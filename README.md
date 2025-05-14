# 🎧 Musicca Web Pages – HTML/CSS/SCSS Integration

This is my integration project for lesson 1 of the Web Dev course at EMSE (Autumn 2024).  
The goal was to build two responsive and styled web pages from static mockups, using HTML and SCSS.

## 🌐 Pages included

- **About Musicca** – General info page styled based on the provided mockup.
- **Login Page** – A form page with input validation, styled interactions, and submission handling.

## 🛠️ Tech stack

- **HTML5**
- **SCSS** (compiled to CSS via Sass)
- **Python 3** (for running a local dev server)

## 🔧 How to run it locally

1. Make sure you’ve got Python 3, Node, npm and Sass installed.
2. Start the local server:
   ```bash
   python3 run_server.py
````

3. In another terminal, run the SCSS watcher:

   ```bash
   ./compile_css.sh
   ```
4. Then open:

   * `http://localhost:8000/integration/about.html`
   * `http://localhost:8000/integration/login.html`

## ✅ Features

* Clean semantic HTML structure
* Responsive and visually accurate styling based on mockups
* Interactive login form with client-side validation:

  * Required fields
  * Email format check
  * Real-time UX feedback (valid/invalid/focused states)
* Form submits to `/register` with hardcoded correct values

## 🙋‍♂️ Notes

This was a solo TP, and everything here was coded from scratch based on the given design files. The SCSS is compiled to CSS and ignored from Git.

## 👤 Made by

* Lahoussine Bouhmou