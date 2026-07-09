# 🚀 Raj Mali — Personal Portfolio

> **Live Site:** [technicalraj.xyz](https://technicalraj.xyz)

A modern, animated personal portfolio website built with pure **HTML, CSS, and JavaScript** — no frameworks, no build tools, no dependencies.

---

## ✨ Features

- 🧠 Animated neural-network particle canvas in the hero section
- 🌙 Dark theme with violet + blue gradient accents
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎞️ Scroll-reveal animations via IntersectionObserver
- 🏅 Dynamic certifications section — just drop images into `certificates/`
- ⚡ Zero dependencies — single `index.html` file

---

## 📁 Folder Structure

```
portfolio/
├── index.html          ← Main portfolio file
├── README.md           ← You are here
└── certificates/       ← Drop your certificate images here
    ├── python.png
    ├── ml-course.jpg
    └── ...
```

---

## 🏅 How to Add Certificates

1. Drop your certificate image (`.png`, `.jpg`, `.webp`) into the `certificates/` folder
2. Open `index.html` and find the `CERTIFICATES` array near the bottom
3. Add an entry:

```js
const CERTIFICATES = [
  {
    file:   "python.png",         // filename inside certificates/
    name:   "Python Basics",      // certificate title
    issuer: "HackerRank",         // issuing platform
    date:   "Jan 2025",           // month & year
    link:   "https://verify-url"  // optional: credential verify URL
  },
];
```

4. Save → `git add . && git commit -m "add certificate" && git push`

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Interactivity | Vanilla JavaScript |
| Fonts | Space Grotesk · Inter · JetBrains Mono |
| Hosting | GitHub Pages |

---

## 🚀 Deployment

This site is deployed via **GitHub Pages**.

```
Settings → Pages → Branch: main → Folder: / (root)
```

Any push to `main` automatically updates the live site.

---

## 📬 Contact

| | |
|---|---|
| 📧 Email | raj.sukdev.mahajan@gmail.com |
| 💼 LinkedIn | [raj-mali-b2b2852a7](https://www.linkedin.com/in/raj-mali-b2b2852a7) |
| 🐙 GitHub | [technicalraj01](https://github.com/technicalraj01) |
| 🌐 Portfolio | [technicalraj.xyz](https://technicalraj.xyz) |

---

<p align="center">Designed & built by <strong>Raj Mali</strong> · Nashik, Maharashtra, India</p>
