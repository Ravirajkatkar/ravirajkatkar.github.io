# 🚀 Raviraj Katkar – Portfolio Website

Personal portfolio of **Raviraj Katkar** — Full Stack Developer | Cloud & Mobile Application Engineer with 4+ years of experience across React Native, Node.js, TypeScript, AWS, Microsoft Azure, REST APIs and CI/CD.

🌐 **Live Site:** [ravirajkatkar.github.io](https://ravirajkatkar.github.io/)

---

## 👨‍💻 About Me

I build and operate web and mobile applications end to end — React Native and React.js front ends, Node.js REST APIs, MySQL data models, and the AWS / Microsoft Azure infrastructure and GitHub Actions pipelines they ship through. My path runs from internship to Senior Software Engineer across fintech, edtech, IoT and AI-powered platforms.

---

## ✨ Features

- ⚛️ Plain HTML, CSS & vanilla JavaScript — no framework, no build step
- 🌙 Dark / Light theme toggle (remembered, applied before first paint)
- 📱 Responsive from 320px phones to large desktops
- 🧭 Sticky navigation with active-section highlighting
- ☁️ Cloud & architecture flow, grouped skills, experience timeline, project case studies
- 📊 Animated counters and scroll reveals (disabled for `prefers-reduced-motion`)
- 📬 Contact form via EmailJS (loaded only when the form is used)
- 🔎 SEO: meta/Open Graph tags, JSON-LD structured data, sitemap and robots.txt
- ⚡ Performance: self-hosted fonts, AVIF/WebP images, inline SVG icon sprite

---

## 🛠️ Site Tech

| Area | Technology |
|------|------------|
| Markup & styles | HTML5, CSS3 (custom properties, Bootstrap-compatible grid subset) |
| Scripts | Vanilla JavaScript (IntersectionObserver, canvas) |
| Fonts | Bebas Neue, DM Sans, JetBrains Mono — self-hosted woff2 |
| Icons | Inline SVG sprite (Bootstrap Icons + Devicon, MIT) |
| Contact form | EmailJS |
| Hosting / CI | GitHub Pages via GitHub Actions |

---

## 📁 Project Structure

```
ravirajkatkar.github.io/
├── index.html                    # The whole site (HTML, CSS, JS)
├── robots.txt
├── sitemap.xml
└── assets/
    ├── RavirajKatkar-Resume.pdf  # Resume (download button)
    ├── raviraj-katkar-cutout-*   # Hero portrait cut-out, 480 & 840px (AVIF / WebP / PNG with transparency)
    ├── raviraj-katkar-photo-700.jpg  # Square portrait (search-result structured data)
    ├── og-image.jpg              # Social sharing preview (1200×630)
    ├── image.png                 # Previous illustrated avatar (unused)
    └── fonts/                    # Self-hosted woff2 fonts
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/ravirajkatkar/ravirajkatkar.github.io.git
cd ravirajkatkar.github.io

# Open directly…
open index.html

# …or serve locally (closer to GitHub Pages)
python3 -m http.server 8000
```

No build tools or dependencies required.

### Editing content

Everything lives in `index.html`, one commented block per section (`HERO`, `ABOUT`, `CLOUD & ARCHITECTURE`, `SKILLS`, `EXPERIENCE`, `PROJECTS`, …).

- **Skills:** add an `<li>` to the right `skill-list`; add `class="core"` to highlight it as primary stack.
- **Projects:** copy an existing `project-card` block.
- **Icons:** use `<svg class="bi"><use href="#bi-NAME"></use></svg>`. Only icons already in the sprite at the top of `<body>` are available — add new ones as `<symbol>` elements there.
- **Resume:** replace `assets/RavirajKatkar-Resume.pdf` (keep the file name).

---

## 💼 Experience Highlights

- **EarnWealth Solutions Pvt. Ltd.** *(Nov 2023 – Present)* — Senior Software Engineer (Full-Stack & DevOps)
- **Appzia Technologies** *(Jul 2022 – Nov 2023)* — React Native Developer
- **Aadi Technology** *(Dec 2021 – Jul 2022)* — Software Engineer Intern

---

## 📬 Contact

- 📧 Email: [ravirajhkatkar@gmail.com](mailto:ravirajhkatkar@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/raviraj-katkar-736438227](https://linkedin.com/in/raviraj-katkar-736438227/)
- 🐙 GitHub: [github.com/ravirajkatkar](https://github.com/ravirajkatkar/)
- 📍 Location: Pune, Maharashtra, India

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ❤️ and lots of React Native
