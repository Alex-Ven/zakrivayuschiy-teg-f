# Closing Tag — A Journey Through Web Development (Educational Project)

**An emotional, responsive storytelling website** about the **student’s journey** in learning HTML, CSS, and frontend — from fear to confidence.

**This is my educational project** — built to master **semantic HTML, responsive design, and interactive JavaScript**.

Live Demo: [closing-tag-weld.vercel.app](https://closing-tag-weld.vercel.app)

---

## Technologies

| Category           | Technologies |
|--------------------|--------------|
| **Language**       | HTML5, CSS3, **Vanilla JavaScript** |
| **Layout**         | CSS Grid, Flexbox, BEM |
| **Interactive**    | **Like buttons**, **theme switcher** |
| **State**          | `localStorage` for theme persistence |
| **Responsive**     | Mobile-first, fluid typography |
| **Accessibility**  | Semantic tags, `aria-hidden`, focus states |

---

## Interactive Features (JavaScript)

### Like Buttons
- Click **heart icon** or **"Like" button** → toggles `.is-liked`
- **Animation delay**: 500ms
- **Text changes**: `Like` → `Unlike`
- Works on **all cards**

```js
heart.classList.toggle('is-liked');
setTimeout(() => button.textContent = 'Unlike', 500);
```

### Theme Switcher
- **3 themes**: `light`, `dark`, `auto`
- **Saved in `localStorage`**
- **Active button disabled**
- Smooth CSS transitions

```js
document.documentElement.classList.add(`theme-${theme}`);
localStorage.setItem('theme', theme);
```

---

## Features

- **Fully Responsive** — mobile, tablet, desktop
- **8 Emotional Chapters** with pixel art
- **Like Buttons** on every chapter
- **Theme Switcher** (Light / Dark / Auto)
- **Smooth Scrolling**
- **Semantic HTML**
- **No frameworks** — pure code

---

## Project Chapters

| Chapter | Theme | JS Feature |
|--------|------|-----------|
| Freetrack | First steps | Like + Theme |
| 1st Sprint | Blank page | Like |
| 1st Sprint | "What if I fail?" | Like |
| 2nd Sprint | Perfectionism | Like |
| 2nd Sprint | Community | Like |
| 3rd Sprint | Creative blocks | Like |
| 3rd Sprint | Overwhelm | Like |
| **Now** | Growth | Like + Theme |

---

## How to Run Locally

```bash
# 1. Clone
git clone https://github.com/Alex-Ven/zakrivayuschiy-teg-f.git
cd zakrivayuschiy-teg-f

# 2. Open
open public/index.html
```

> Works **offline**, **all devices**, **no build**

---

**Stack**: `HTML | CSS | JavaScript | Responsive | Interactive`  
**Tags**: `vanilla-js`, `responsive`, `educational-project`, `like-button`, `theme-switcher`, `journey`

## Author

**Alexander Venedyukhin** — Aspiring Frontend / Full Stack Developer  
[LinkedIn](https://linkedin.com/in/alexander-venedyukhin-1288abb2) | [GitHub](https://github.com/Alex-Ven)

---

## Support the Project

Like it? ⭐ Star the repo!  
Have ideas? → [Open an Issue](https://github.com/Alex-Ven/zakrivayuschiy-teg-f/issues)
