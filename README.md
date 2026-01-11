# Hogarth Frontend Dev Test

This project is a **pixel-perfect frontend implementation** based on the provided Hogarth design mockups.  
The objective was to replicate the UI **exactly**, following strict technical and visual constraints.

---

## 🛠 Tech Stack

- **HTML5**
- **SCSS (Sass)** – modular architecture
- **Pure CSS** (compiled from SCSS)
- ❌ No JavaScript
- ❌ No CSS frameworks (Bootstrap, Tailwind, etc.)

---

## ✨ Key Features

- Pixel-perfect layout matching the provided mockups
- Responsive layouts at **exactly three breakpoints**:
  - Default (Desktop)
  - **1068px**
  - **734px**
- Responsive images implemented using the `<picture>` element
- Apple-style typography using **SF Pro Display**
- Clean, scalable, and maintainable SCSS architecture
- Smooth hover interactions
- No visual regressions across breakpoints

---

## 📁 Project Structure

```text
project-root/
│
├── index.html
│
├── css/
│   └── style.css            # Compiled CSS output
│
├── scss/
│   ├── abstracts/           # Variables, mixins, breakpoints
│   ├── base/                # Reset, typography, global styles
│   ├── layout/              # Container, header, footer
│   ├── components/          # Cards, buttons, hero, links
│   ├── pages/               # Page-specific styles
│   └── styles.scss          # Root SCSS entry file
│
├── assets/
│   └── images/              # Provided images (used as-is)
│
├── favicon/
│   └── *.png / *.ico        # Favicon assets
│
└── README.md
```

## ⚙️ Installation & Setup (Local)

1️⃣ Clone the Repository
git clone https://github.com/<your-username>/hogarth-frontend-dev-test.git
cd hogarth-frontend-dev-test

## 2️⃣ Install Sass (If Not Installed)

Using npm:
npm install -g sass

Verify installation:
sass --version

## 3️⃣ Compile SCSS to CSS

Compile once:
sass scss/styles.scss css/style.css

Or run in watch mode (recommended during development):
sass --watch scss/styles.scss:css/style.css

## 4️⃣ Run the Project

## You can run the project in any modern browser:

Open index.html directly
OR (Recommended):
Use VS Code Live Server
Right-click index.html → Open with Live Server

## 🌍 Live Website

# 👉 Live Demo:

https://your-live-site-link.com

# 🧾 GitHub Repository

# 👉 Source Code:

https://github.com/BeWithSohail/hogarth-dev-test

# 📌 Notes & Constraints Followed

Line breaks, spacing, and typography strictly match the mockups
Images are used only from the provided assets folder
Each breakpoint uses its correct image version
No JavaScript used for layout or responsiveness
Media queries handled only via Sass
Code is structured for readability and maintainability

## ✅ Final Remarks

This project demonstrates:
Strong attention to detail
Solid understanding of CSS and Sass architecture
Ability to follow strict UI and technical constraints
Production-ready frontend practices
Thank you for reviewing this submission.
