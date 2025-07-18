# 💼 Personal Portfolio Website

This is my personal portfolio website built as part of my **Python Full-Stack Development Assignment**. It showcases my introduction, skills, projects, blog, and contact form. The site is designed using **HTML**, **TailwindCSS**, and **JavaScript**, with Flask used in development for dynamic rendering. The final deployed version is fully static, using **FormSubmit** for contact functionality.

---

## 🌟 Features

- 🧑 Personal Introduction
- 🛠 Skills and Tools
- 💻 Projects Showcase (with GitHub/demo links)
- 📝 Blog Section (static JSON or hardcoded posts)
- 📬 Contact Form (powered by [FormSubmit](https://formsubmit.co))
- 📱 Fully Responsive (TailwindCSS)
- 💡 Scroll Animations using AOS.js

---

## 🧰 Technologies Used

| Layer     | Tech                                |
|-----------|-------------------------------------|
| Frontend  | HTML, TailwindCSS, JavaScript       |
| Animations| AOS.js (Animate on Scroll)          |
| Backend   | Flask (for local dev only)          |
| Contact   | FormSubmit (no backend needed)      |
| Hosting   | GitHub Pages / Vercel (static site) |

---

## 📂 Project Structure

├── index.html # Home page
├── about.html # About section
├── blog.html # Blog page
├── contact.html # Contact form
├── projects.html # Project showcase
├── skills.html # Skills & tools
├── style.css # Tailwind-based styling
├── README.md # This file
├── /images/ # All images
├── /js/ # AOS.js or custom scripts
└── /data/
└── blog.json # Blog posts (optional)


---

## 💡 Setup Instructions (Local)

> You can preview the site without a backend. Just open in browser:

```bash
# Open the project folder
>>cd my-portfolio
>> python -m venv venv
>> venv\Scripts\activate
>> pip install -r requirements.txt
>> python app.py

# Double-click index.html or open with browser
