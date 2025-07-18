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
- Mobile-friendly and responsive
- Minimalist custom styling with Tailwind + custom CSS
- Deployed via **Render.com** with `gunicorn`

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
### 🌐 Live Demo

👉 [View Portfolio](https://portfolio-m7e1.onrender.com)

---
## 🚀 Getting Started Locally

### Prerequisites

- Python 3.8+
- `pip` for package management
- `virtualenv` (recommended)

### 1. Clone the repo

    ```bash
    git clone https://github.com/your-username/My_Portfolio.git
    cd My_Portfolio

### 2. Create & activate virtual environment
      ```bash
      python -m venv venv
      source venv/bin/activate  # On Windows use: venv\Scripts\activate
      
### 3. Install dependencies
      ```bash
      pip install -r requirements.txt
      
### 4. Run the Flask app
      ```bash
      flask run
      
