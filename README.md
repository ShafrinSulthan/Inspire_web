# 💡 Inspire IT Solution — Business Website

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)
![Poppins](https://img.shields.io/badge/Google_Fonts-Poppins-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-5764ec?style=for-the-badge)

**A modern, fully responsive single-page IT solutions business website built with pure HTML, CSS & JavaScript.**

[🌐 Live Demo](https://shafrinsulthan.github.io/Inspire_web/) • [📁 Folder Structure](#-folder-structure) • [🚀 Getting Started](#-getting-started)

</div>

---

## 📌 Overview

**Inspire IT Solution** is a professional, responsive business landing page designed for IT service companies. It features a dual-bar navigation system, rich content sections — from services to client testimonials — and a clean, corporate aesthetic using a blue and orange color scheme. Built entirely with vanilla HTML, CSS, and JavaScript — no frameworks required.

> Perfect for showcasing frontend skills, using as a business website template, or learning responsive web design.

---

## ✨ Features

| Section | Description |
|---|---|
| 📢 **Top Info Bar** | Fixed contact bar with address, email, phone & social media icons |
| 🧭 **Sticky Navbar** | Hover-triggered dropdown menus on desktop; slide-in drawer on mobile/tablet |
| 🦸 **Hero Section** | Full-viewport background image with headline and dual CTA buttons |
| 🏢 **About Us** | Split layout with image, certified company & quality IT solution highlights |
| 📞 **Consultation Banner** | Parallax-style CTA banner with overlay gradient |
| 🛠️ **IT Solutions** | Icon-driven service cards (Strategy, Network, Software, Data Science, etc.) |
| 📚 **Courses / Training** | 3-column grid of training cards with hover accent border |
| 📊 **Stats Counter** | Metrics bar (clients, projects, awards, team members) |
| 💬 **Testimonials** | 3-column grid of client quotes with names and roles |
| 🖼️ **Featured Works** | Project portfolio grid with floating hover-gradient buttons |
| 🌟 **Client Feedback** | 2-column testimonial cards with profile photos and star ratings |
| 📅 **Upcoming Project CTA** | Full-width parallax CTA with phone number and contact button |
| 📰 **Latest Blog** | 3-column blog card grid with category tags and read-more links |
| 🦶 **Footer** | 4-column footer with logo, links, services, contact info, and newsletter |
| 📱 **Fully Responsive** | Hamburger drawer + accordion dropdowns for mobile & tablet |

---

## 🗂️ Folder Structure

```
inspire-it-solution/
│
├── index.html                  # Main single-page website
│
├── css/
│   └── style.css               # All styles + responsive media queries
│
└── images/
    ├── point1.png              # Certified company icon
    ├── point2.png              # Quality IT icon
    ├── profile1.jpg            # Feedback profile photo
    ├── profile2.jpg            # Feedback profile photo
    └── profile3.jpg            # Feedback profile photo
```

---

## 🧰 Tech Stack

- **HTML5** — Semantic, structured markup
- **CSS3** — Custom properties (CSS variables), Flexbox, CSS Grid, transitions, parallax backgrounds
- **Vanilla JavaScript** — Mobile drawer open/close, overlay toggle, accordion dropdown menus
- **Font Awesome 6.5** — Icons (CDN)
- **IcoFont 1.0** — Supplementary icon set (CDN)
- **Google Fonts** — Poppins (body) + Montserrat (headings)

---

## 🚀 Getting Started

### Option 1 — Open directly
```bash
git clone https://github.com/your-username/inspire-it-solution.git
cd inspire-it-solution
# Open index.html in any browser
```

### Option 2 — VS Code Live Server
1. Install the **Live Server** extension in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. Opens at `http://localhost:5500`

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout Behavior |
|---|---|
| `> 900px` | Full desktop layout — sticky nav, horizontal menu, multi-column grids |
| `501px – 900px` | Tablet — hamburger drawer, 2-column grids, stacked about section |
| `≤ 500px` | Mobile — single column, full-width cards, collapsed footer grid |

**Mobile Navigation highlights:**
- Hamburger icon opens a slide-in left drawer
- Semi-transparent overlay closes the menu on tap
- Dropdowns become accordion-style (tap to expand/collapse)
- Close (✕) button injected via JavaScript at the top of the drawer

---

## 🎨 Color Palette

| Role | Color | Hex / Value |
|---|---|---|
| Primary (Blue) | Slate Blue | `rgb(87, 100, 236)` / `#5764ec` |
| Secondary (Orange) | Burnt Orange | `#ff561d` |
| Top Nav Bar | Indigo Blue | `#5764ec` |
| Background Tint | Soft Lavender | `rgba(136, 116, 181, 0.11)` |
| Text | Dark Gray | `#333` |
| Footer | Dark | `rgba(2, 2, 2, 0.865)` |

---

## 🔧 Customization Guide

| What to change | Where |
|---|---|
| Brand colors | Update `--color-primary` and `--color-secondary` in `style.css` `:root` |
| Logo | Replace the `<img src="...logo-black.png">` in `index.html` navbar |
| Contact info | Update top nav bar and footer contact details in `index.html` |
| Hero background | Change the `background-image` URL in `#hero-section` in `style.css` |
| Placeholder text | Search and replace all `Lorem ipsum` content in `index.html` |
| Form action | Wire up the newsletter email input to your backend or service |

---

## 🐛 Known Issues / Roadmap

- [ ] Stats counter doesn't animate on scroll (currently static numbers)
- [ ] No JavaScript form validation on the newsletter subscription input
- [ ] Hamburger menu doesn't auto-close when a non-dropdown link is tapped on mobile
- [ ] All `Lorem ipsum` placeholder text needs real content
- [ ] External image URLs depend on third-party CDN (should be hosted locally)
- [ ] No dark mode support yet

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

Built with ❤️ using HTML, CSS & JavaScript — no frameworks, no dependencies.

⭐ **Star this repo if you found it useful!**

</div>
