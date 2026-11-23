<div align="center">

# 🌳 Josh Alpay — Portfolio

**BSIT student @ De La Salle University – Dasmariñas · BIT14**

A single-page personal portfolio with a pixel-game look inspired by **Terraria** (night mode) and **Stardew Valley** (day mode), a retro pixel-art hero scene, and playful hover effects.

![HTML5](https://img.shields.io/badge/HTML5-7bd44a?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-0a1322?style=for-the-badge&logo=css3&logoColor=7bd44a)
![JavaScript](https://img.shields.io/badge/JavaScript-0a1322?style=for-the-badge&logo=javascript&logoColor=7bd44a)

</div>

---

## ✨ Features

- 🌳 **Terraria night and Stardew day themes** — a deep navy night sky with grass-green accents, and a warm parchment day mode with a blue sky and a sun
- 👾 **Retro pixel-art hero background** drawn on a canvas with flapping birds, a moving car, drifting clouds, and a sun or moon, plus a film-grain overlay
- 🖼️ **Avatar swap** — a cartoon picture in dark mode that switches to my photo in light mode
- ✨ **Card hover effects** on projects and skills
- 🪟 **Click a project to open it** — shows what it does, runnable links, code, and a live mini demo for some projects
- 🎨 **Poster thumbnails** on each project, tinted green to match the theme and revealing full color on hover
- 🔤 **Professional fonts** — Inter for text and headings, IBM Plex Mono for labels and code, both built into the page so it works offline
- 🖱️ **Custom pixel cursor** — arrow with a little kitty, a pointing hand over links, and a ring ripple on click (desktop only)
- ⌨️ **Typing effect** that cycles through roles in the hero
- 🌗 **Dark / light toggle** that remembers your choice
- 🗂️ **Filterable projects** grid (Web, Java, School)
- 📈 **Scroll-reveal animations** and animated stat counters
- 🧭 **Sticky nav** with active-section highlighting and a mobile menu
- 📱 **Fully responsive** — works on phones, tablets, and desktops
- 📨 **Contact section** with a demo form

## 📁 Files

| File | What it is |
| --- | --- |
| `Josh_Alpay_Portfolio.html` | The full portfolio — HTML, CSS, and JS in one file (photo included) |
| `index.html` | Blank starter page |
| `README.md` | You are here |
| `LICENSE` | License |

## 🚀 Run it

No build step and no dependencies. Just open the file:

```bash
git clone https://github.com/Kyocumberrr/Portfolio.git
cd Portfolio
# then open Josh_Alpay_Portfolio.html in your browser
```

## 🎨 Customize

All theme colors live at the top of the `<style>` block:

```css
:root {
  --bg: #0a1322;        /* background */
  --card: #14233b;      /* cards */
  --accent: #7bd44a;    /* grass green */
  --accent-2: #b6f08a;  /* lighter green */
}
```

Look for `EDIT` comments in the HTML to update your projects, education timeline, and contact links, and edit the `roles` array in the script to change the typing text.

## 🌐 Deploy (GitHub Pages)

1. Go to **Settings → Pages**
2. Set the source to the `main` branch
3. Your site goes live at `https://kyocumberrr.github.io/Portfolio/`

> Tip: GitHub Pages opens `index.html` by default, so rename the portfolio file to `index.html` (or copy its contents into it) to make it the home page.

## 📬 Contact

Open to projects and internships — reach out through the contact section of the site.

---

<div align="center">

*keep learning.* 🌱

© Josh Alpay · BIT14, DLSU-D

</div>

## 🧩 Icons

Icons come from [IconBuddy](https://iconbuddy.com/), which collects open-source icon sets:

- **Pixelarticons** (MIT) for the interface and soft-skill icons
- **Simple Icons** (CC0) for the tech and social logos

## 📱 Works on every device

- Fully responsive from small phones (320 px) to large desktop screens, with no sideways scrolling
- Touch-friendly: 44 px tap targets, no accidental zoom when typing in a field, tap on the project cards to open them
- Safe-area support for phones with a notch, and a dynamic browser color that follows dark and light mode
- Lighter on phones: the film-grain overlay and blur effects are switched off, and the animated background pauses when it is off screen
- The custom cursor only appears on computers with a mouse
- Respects "reduce motion" settings
