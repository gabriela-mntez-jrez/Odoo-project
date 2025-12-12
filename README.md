# Odoo Landing Page (Bootstrap + SCSS)

This project is a static landing page built from a provided mock-up using **Bootstrap 5.3**, **SCSS**, and a small amount of JavaScript where needed.  
The goal was to reproduce the layout and behavior while keeping the code clean, responsive, and maintainable.

---

## 🚀 Tech Stack

- **HTML5**
- **Bootstrap 5.3**
- **SCSS**
- **Bootstrap Icons**
- **Vanilla JavaScript**

---

## 📐 Features

- Fully responsive layout (desktop and mobile)
- Functional and responsive navbar with hamburger menu
- Clickable award cards with hover effects
- Functional FAQ accordion
- Custom styling built on top of Bootstrap utilities
- Organized SCSS structure
- Accessibility considerations (alt attributes, ARIA labels where applicable)

---

## 📂 Project Structure

.
├── css/
│ └── styles.css
├── scss/
│ ├── _variables.scss
│ ├── _navbar.scss
│ ├── _hero.scss
│ ├── _cards.scss
│ ├── _footer.scss
│ └── main.scss
├── js/
│ └── script.js
├── img/
│ └── (project images)
├── index.html
└── README.md

yaml
Copiar código

---

## 🛠️ How to Run the Project Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/gabriela-mntez-jrez/Odoo-project.git
bash
Copiar código
cd Odoo-project
2️⃣ Install Sass (if you don’t have it)
You can install Sass globally using npm:

bash
Copiar código
npm install -g sass
Verify installation:

bash
Copiar código
sass --version
3️⃣ Compile SCSS to CSS
From the project root, run:

bash
Copiar código
sass scss/main.scss css/styles.css
(Optional) To watch changes automatically:

bash
Copiar código
sass --watch scss/main.scss:css/styles.css
4️⃣ Open the project
Simply open index.html in your browser:

bash
Copiar código
open index.html
or double-click the file.

No server is required since this is a static project.

♿ Accessibility Notes
Images include meaningful alt attributes.

Icons and interactive elements use aria-label when needed.

The layout supports keyboard navigation through Bootstrap components.

💭 Reflections
What works well
Clear structure and visual hierarchy

Strong use of Bootstrap components

Easy to extend and maintain

Possible improvements
Convert repeated UI elements into reusable components using React

Improve color contrast in some sections

Extend accessibility support further (focus states, screen reader testing)

📌 Final Notes
This project focuses on clarity, responsiveness, and maintainability while staying aligned with real-world frontend practices.
It is not a pixel-perfect reproduction, but a practical and scalable implementation.

Happy coding 🚀
