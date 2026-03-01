# 🧶 Cozy Yarn Academy

A warm, welcoming website for yarn lovers of every skill level — built by crafters, for crafters.

---

## 📋 Overview

Cozy Yarn Academy is a multi-page static website dedicated to the art of knitting and crocheting. It features course guides, crochet history, a community project gallery, and an enrollment form — all wrapped in a cozy, consistent design system.

---

## 🗂️ Pages

| File | Title | Description |
|---|---|---|
| `index.html` | Home | Landing page with hero section and explore cards |
| `about.html` | About Us | Mission, vision, stats, and features |
| `history.html` | History | Timeline of crochet's origins and cultural significance |
| `tutorials.html` | Tutorials | Course guide table and video tutorial |
| `myproj.html` | My Projects | Community post feed |
| `contact.html` | Contact Us | Contact info, social links, and enrollment form |

---

## 📁 File Structure

```
cozy-yarn-academy/
│
├── index.html
├── about.html
├── history.html
├── tutorials.html
├── myproj.html
├── contact.html
│
├── images/
│   ├── logo.png
│   ├── hero-image.png
│   ├── history-image.png
│   ├── tutorial-image.png
│   ├── myproj-image.png
│   ├── user-prof.png
│   ├── pic-1.png
│   ├── 2.png
│   ├── Facebook.svg
│   ├── Instagram.svg
│   └── Telegram.svg
│
└── media/
    ├── intro_vid.mp4
    ├── intro_vid.webm
    ├── tutorial.mp4
    ├── tutorial.webm
    ├── captions.vtt
    └── descriptions.vtt
```

---

## 🎨 Design System

### Color Palette

| Name | Hex | Usage |
|---|---|---|
| Teal | `#415865` | Primary background, nav, cards |
| Cream | `#F9F8EB` | Page background, text on dark |
| Sky | `#7A9EB1` | Accents, footer, history hero |
| Peach | `#FFE1B6` | Highlights, labels, buttons |

### Typography
- **Font:** [Outfit](https://fonts.google.com/specimen/Outfit) (Google Fonts)
- **Weights used:** 300, 400, 500, 600, 700

---

## ✨ Features

- **Responsive design** — adapts to desktop, tablet, and mobile
- **Fixed navigation** — consistent nav bar across all pages with mobile hamburger menu
- **Video support** — hero intro video and tutorial video with captions and audio descriptions
- **Course guide** — sortable table with beginner, intermediate, and advanced badges
- **Crochet history timeline** — visual vertical timeline with era cards
- **Community feed** — user post cards on My Projects page
- **Enrollment form** — course selection, skill level picker, and personal info fields on Contact page
- **Accessible media** — `.vtt` caption and description tracks on all videos
- **Consistent footer** — full-width sky-blue footer with centered content and social links across all pages

---

## 🚀 Getting Started

No build tools or dependencies required. This is a plain HTML/CSS/JS website.

1. Clone or download the repository
2. Open any `.html` file in your browser
3. Or serve locally with any static server, e.g.:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000` in your browser.

---

## 📬 Enrollment Form

The enrollment form is located on the **Contact Us** page (`contact.html`). It collects:

- Full name, email address, and phone number
- Course selection (Knitting, Advanced Crochet, Yarn Dyeing, Amigurumi, Summer Shawl)
- Skill level (Beginner / Intermediate / Advanced)
- Optional additional notes

> ⚠️ The form currently posts to `/enroll`. Connect it to a backend or form service (e.g. Formspree, Netlify Forms) to handle submissions.

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout changes |
|---|---|
| `≤ 860px` | Single-column grids, stacked hero |
| `≤ 600px` | Mobile nav (hamburger), reduced padding |

---

## 🤝 Credits

- **Font:** Outfit via Google Fonts
- **Icons:** Facebook, Instagram, and Telegram SVG icons
- **Content:** Crochet history sourced and adapted for educational use

---

© 2024 Cozy Yarn Academy. All rights reserved.