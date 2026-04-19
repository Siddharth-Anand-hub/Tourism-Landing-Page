# 🏔️ Adventure — Travel & Tour Website

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![FontAwesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**A responsive, multi-section travel and adventure tourism website with dark mode support.**

[Live Demo](#-live-demo) • [Features](#-features) • [Sections](#-sections) • [Installation](#-installation) • [Project Structure](#-project-structure) • [Contributing](#-contributing)

</div>

---

## 📌 Overview

**Adventure** is a fully responsive travel and tour website built with plain **HTML5**, **CSS3**, and **JavaScript (jQuery)**. It showcases upcoming travel events, destination tours, an about carousel, and a contact form — all wrapped in a sleek glassmorphism navbar with a light/dark mode toggle.

> 🌍 Explore. Discover. Adventure.

---

## 🎬 Live Demo

> 🔗 [View Live Site](#) *(add your deployed link here — Netlify / GitHub Pages / Vercel)*

| Light Mode | Dark Mode |
|---|---|
| *(add screenshot)* | *(add screenshot)* |

---

## ✨ Features

- ✅ **Fully responsive** — works on mobile, tablet, and desktop
- ✅ **Dark / Light mode toggle** with smooth transition
- ✅ **Glassmorphism navbar** with active link highlighting
- ✅ **Mobile hamburger menu** for small screens
- ✅ **CSS-only image carousel** in the About section (no JS dependency)
- ✅ **Scroll-to-top button** for easy navigation
- ✅ **Contact form** with name, email, country, and remarks fields
- ✅ **Font Awesome icons** for social links and contact info
- ✅ **Smooth scroll** between sections
- ✅ **Semantic HTML5** structure throughout

---

## 📄 Sections

| Section | Description |
|---|---|
| **Home / Hero** | Full-screen header with tagline and CTA |
| **Events** | Cards for upcoming adventure events |
| **Explore** | Inspirational full-width banner with quote |
| **Tours** | Upcoming tour dates with image gallery |
| **About** | CSS-only image carousel with brand identity |
| **Contact** | Contact form + direct contact info |
| **Footer** | Creator credit and social media links |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, glassmorphism, dark mode, animations |
| JavaScript (Vanilla) | Mobile menu toggle, scroll-to-top button |
| jQuery 3.6.0 | DOM manipulation, active nav link styling |
| Font Awesome 4.7 | Icons for navigation and contact section |
| CSS Custom Properties | Theme variables for dark/light mode |

---

## 📁 Project Structure

```
adventure-website/
│
├── index.html              # Main HTML file
│
├── css/
│   ├── style.css           # Core styles, layout, components
│   └── responsive.css      # Media queries for responsiveness
│
├── js/
│   └── script.js           # Scroll-to-top, nav transitions, animations
│
├── img/
│   ├── mountain.png        # Navbar logo icon
│   ├── mountain_dark.jpg   # About section logo
│   ├── menu-btn.png        # Mobile hamburger icon
│   ├── img1.jfif           # Everest event card image
│   ├── img2.jfif           # Walking holidays & Andaman cards
│   ├── img3.png – img6.png # Tour image gallery
│   ├── carousel-img4.jpg   # About carousel image 1
│   ├── carousel-img5.jpg   # About carousel image 2
│   ├── carousel-img6.jpg   # About carousel image 3
│   └── favicon-*.png       # Favicons (16x16, 32x32, apple-touch)
│
├── site.webmanifest        # PWA manifest file
└── README.md
```

---

## ⚙️ Installation & Setup

No build tools or package managers needed — this is a pure static website.

### 1. Clone the Repository

```bash
git clone https://github.com/Avii-Kumar18/adventure-website.git
cd adventure-website
```

### 2. Open in Browser

Simply open `index.html` directly in your browser:

```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or use a local development server for best results:

```bash
# Using VS Code Live Server extension (recommended)
# Right-click index.html → "Open with Live Server"

# Or using Python
python -m http.server 8000
# Then visit: http://localhost:8000
```

---

## 🌙 Dark Mode

The site includes a built-in **dark/light mode toggle** in the navbar, implemented using:

- A CSS checkbox toggle with a styled label
- Font Awesome moon (`fa-moon-o`) and sun (`fa-sun-o`) icons
- CSS custom properties (`var(--color)`) that switch values on toggle

---

## 📱 Responsive Design

Responsive behavior is handled in `css/responsive.css`:

| Breakpoint | Behavior |
|---|---|
| Desktop (> 900px) | Full horizontal navbar, multi-column layouts |
| Tablet (600–900px) | Adjusted grid columns, scaled typography |
| Mobile (< 600px) | Hamburger menu, single-column stacked layout |

---

## 🚀 Deployment

Deploy for free on any static hosting platform:

**GitHub Pages:**
```bash
# Push to main branch → Settings → Pages → Deploy from branch
```

**Netlify:**
```
Drag and drop the project folder at netlify.com/drop
```

**Vercel:**
```bash
npx vercel
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. **Fork** the repository
2. **Create** a branch: `git checkout -b feature/your-feature`
3. **Commit** your changes: `git commit -m "Add: your feature"`
4. **Push** to the branch: `git push origin feature/your-feature`
5. **Open** a Pull Request

---

## 📌 Roadmap / TODO

- [ ] Add more destinations to the Events section
- [ ] Expand the country dropdown in the Contact form
- [ ] Connect contact form to EmailJS or a backend
- [ ] Add scroll-reveal animations for section entries
- [ ] Improve SEO with meta description and Open Graph tags
- [ ] Add a page loading animation

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙋 Author

**Siddharth Anand**  
Web Developer | Bhilai, Chhattisgarh, India

[![GitHub](https://img.shields.io/badge/GitHub-Siddharth--Anand--hub-black?style=flat&logo=github)](https://github.com/Siddharth-Anand-hub)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/siddhartha-anand-a08059327/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat&logo=gmail)](mailto:anandsidd04@gmail.com)

---

<div align="center">
  <sub>Built with ❤️ using HTML, CSS & JavaScript</sub>
</div>
