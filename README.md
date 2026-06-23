# Academic Portfolio | Dr. Jangjae Lee

This repository contains the source code for my personal academic website, hosted via GitHub Pages. It serves as a central hub for my research, publications, and professional curriculum vitae, designed for academic recruitment and collaboration.

## 🔗 Live Website

**Visit the site here:** [https://Jerry03120.github.io](https://Jerry03120.github.io)

---

## 🛠 Overview

This portfolio is built as a **single-page responsive website** using HTML5 and CSS3. It is designed with a focus on **readability, professionalism, and accessibility**, ensuring that search committees and collaborators can easily access key information on any device.

### Key Features

* **Responsive Design:** Fully adaptable layout for Desktop, Tablet, and Mobile.
* **Clean Typography:** Uses *DM Serif Display* for headings (authority) and *Inter* for body text (readability).
* **Academic Focus:** Dedicated sections for Research Interests, Selected Publications, CV download, and reference contacts.
* **Fast Loading:** Minimalist code with no heavy framework dependencies.
* **Scroll Animations:** Lightweight IntersectionObserver-based reveal effects with `prefers-reduced-motion` support.

---

## 📂 Project Structure

```text
.
├── index.html                    # Main website structure and styles
├── README.md                     # This file
├── Jangjae_Lee_CV_0623_2026.pdf  # Curriculum Vitae (ensure this file exists)
└── assets/                       # (Optional) Folder for images/figures
    └── profile.jpg               # Profile picture (used in hero blueprint card)
```

---

## 🚀 Deployment (GitHub Pages)

1. Push all files to the **root of your `main` branch** in the repository named `Jerry03120.github.io`.
2. Go to **Settings → Pages → Source** and select the `main` branch, root folder (`/`).
3. Your site will be live at `https://Jerry03120.github.io` within a few minutes.

> **Note:** If you rename or update the CV file, update the `href` in both the nav bar and the footer link inside `index.html` to match.

---

## ✏️ Updating Content

| What to update | Where in `index.html` |
|---|---|
| Hero tagline / description | `<section class="hero">` → `.hero-desc` |
| New publication | Add a `<div class="pub-item">` block inside `<div class="pub-list">` |
| New position / education | Add a `<div class="tl-item">` block inside `<div class="timeline">` |
| Skills | Edit `<span class="s-tag">` entries inside the relevant `.skill-block` |
| Contact info | `<footer id="contact">` → `.contact-list` |
| Reference contacts | Footer → right-hand references card |

---

## 📬 Contact

**Jangjae Lee**  
Postdoctoral Research Fellow  
Department of Civil and Environmental Engineering  
University of Houston, Houston, TX 77204

* 📧 [jlee277@central.uh.edu](mailto:jlee277@central.uh.edu)
* 💼 [LinkedIn](https://www.linkedin.com/in/jangjlee10)
* 🐙 [GitHub](https://github.com/Jerry03120)
* 🎓 [Google Scholar](https://scholar.google.com/citations?user=cNvgzJ0AAAAJ&hl=en)
