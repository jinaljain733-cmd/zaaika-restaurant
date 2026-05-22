# 🍛 Zaaika — Fine Indian Dining Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=flat&logo=google&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

A fully responsive, dark-themed fine Indian dining restaurant website built with pure HTML, CSS and JavaScript — no frameworks, no dependencies. Features a saffron and turmeric colour palette inspired by Indian culture.

---

## 🌐 Live Demo

**[https://jinaljain733-cmd.github.io/zaaika-restaurant/](https://jinaljain733-cmd.github.io/zaaika-restaurant/)**

---

## 📸 Preview

> Add a screenshot here after deploying
> `![Preview](preview.png)`

---

## ✨ Features

- Fixed frosted-glass navbar with mobile hamburger menu
- Full-screen hero section with radial gradient glow & animated scroll cue
- Our Story section with stats (12 regional cuisines, 80+ dishes, 4.9★)
- Interactive tabbed menu — 24 dishes across Starters, Mains, Breads & Desserts
- Specialties section with hover-animated cards
- Gallery grid with CSS span layout
- Full reservation form with date, time, occasion & special requests
- SVG star pattern overlay on body via CSS `background-image`
- Custom styled `<select>` dropdown with inline SVG arrow
- 4-column footer — properly aligned across all screen sizes
- Deployed on GitHub Pages

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic structure — `<nav>`, `<section>`, `<footer>`, `<form>` |
| CSS3 | Variables, Grid, Flexbox, animations, gradients, pseudo-elements |
| JavaScript (ES6+) | Tab menu, mobile nav, dynamic DOM rendering |
| Google Fonts | Yeseva One + Playfair Display + DM Sans |
| GitHub Pages | Deployment & hosting |

---

## 🧠 CSS Concepts Used

- CSS Custom Properties (variables) — full design token system
- CSS Grid — story layout, menu grid, gallery with `span`, footer
- Flexbox — nav, buttons, hero, reservation info
- `clamp()` — fluid responsive typography
- `backdrop-filter: blur(20px)` — frosted glass navbar
- `@keyframes bounce` — animated scroll cue
- `body::before` — full-page SVG star pattern overlay
- `::before` pseudo-elements — section borders & card hover effects
- Inline SVG via `data:image/svg+xml` — custom select arrow
- `radial-gradient` — hero glow background
- `-webkit-appearance: none` — cross-browser form styling
- `position: fixed` navbar + hamburger menu
- 4 responsive breakpoints: `1024px`, `860px`, `700px`, `440px`

---

## 🍽️ Menu Sections

| Tab | Dishes |
|---|---|
| Starters | Galouti Kebab, Paneer Tikka, Amritsari Machhi, Seekh Kebab + more |
| Mains | Rogan Josh, Butter Chicken, Kerala Fish Curry, Dal Bukhara + more |
| Breads | Naan, Lachha Paratha, Rumali Roti, Parotta + more |
| Desserts | Rasmalai, Kulfi Falooda, Gulab Jamun, Gajar Halwa + more |

---

## 📁 Project Structure

```
zaaika-restaurant/
├── index.html       # Entire site — HTML + CSS + JS in one file
└── README.md
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout Change |
|---|---|
| `≤ 1024px` | Specialties go 2-col, gallery goes 2-col |
| `≤ 860px` | Story stacks, menu goes single col, reservation stacks |
| `≤ 700px` | Hamburger nav, form rows stack, footer goes 2-col |
| `≤ 440px` | Full single column, reduced padding |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/jinaljain733-cmd/zaaika-restaurant.git

# Go into the folder
cd zaaika-restaurant

# Open in browser
open index.html
```

No install, no build step needed.

---

## 👤 Author

**Jinal Jain**
- GitHub: [@jinaljain733-cmd](https://github.com/jinaljain733-cmd)
- LinkedIn: [linkedin.com/in/jinal-jain-08b70328b](https://linkedin.com/in/jinal-jain-08b70328b)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

> ⚠️ Please do not reuse or redistribute this project as your own work.