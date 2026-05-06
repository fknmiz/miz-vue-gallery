# 📸 A Vue 3 Gallery

> **A Vue 3 photography portfolio with animated category filtering, masonry grid layout, and a full lightbox viewer — built with real photographs by Mirza Causevic.**

Built by **[Mirza Causevic](https://www.linkedin.com/in/mirzacausevic/)** for front-end portfolio.

---

## ✨ Features

- 🗂️ **Category Filtering** — Animated filter buttons with `aria-pressed` states (Landscape, Food)
- 🧱 **Masonry Grid** — CSS columns layout that adapts to image aspect ratios naturally
- 🔍 **Lightbox Viewer** — Full-size photo viewer with keyboard navigation (←→ Esc)
- 🌙 **Dark / Light Mode** — Toggle with smooth CSS custom property transitions
- ♿ **Fully Accessible** — Semantic HTML, keyboard nav, ARIA roles, skip link, focus management
- 📱 **Responsive** — 3-column desktop → 2-column tablet → 1-column mobile
- 📷 **Real Photography** — Original shots 

---

## 🛠 Tech Stack

| Tool | Role |
|---|---|
| **Vue 3** | Composition API reactive pattern (CDN build for demo) |
| **Plain CSS** | Design tokens, CSS custom properties, no framework |
| **CSS Columns** | Native masonry layout |
| **Vanilla JS** | Lightbox, keyboard nav, theme toggle |

---

## 📂 Project Structure

```
miz-vue-gallery/
├── index.html                  ← Single-file app
├── public/
│   └── images/
│       ├── landscape/          ← 5 landscape photographs
│       └── food/               ← 5 Bosnian food photographs
├── screenshots/                ← README preview images
└── README.md
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/fknmiz/miz-vue-gallery.git
cd miz-vue-gallery
# Add your photos to public/images/landscape/ and public/images/food/
# Open index.html in browser or serve locally:
npx serve .
```

---

## ☁️ Deploy to Vercel

1. Push to GitHub ✅
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Select `fknmiz/miz-vue-gallery`
4. Framework: **Other** (static) — Output: `./`
5. Click **Deploy**

---

## 🎯 Portfolio Value

- ✅ Reactive state management with filter logic (Vue 3 Composition API pattern)
- ✅ Event-driven UI — filter, lightbox open/close, keyboard navigation
- ✅ CSS custom property theming (dark/light mode)
- ✅ Accessibility-first: ARIA roles, focus management, keyboard support
- ✅ Responsive CSS columns masonry layout
- ✅ Original photography content — Landscape & Bosnian cuisine

---

## 🔮 Roadmap

- [ ] Migrate to full Vue 3 SFC (`.vue` files) with Vite
- [ ] Add more categories (Urban, Travel, Portrait)
- [ ] GSAP entrance animations on filter transition
- [ ] Vercel live demo link

---

## 📄 License

MIT — free to use and modify.  
Photography © Mirza Causevic — all rights reserved.

---

**Built by Miz Causevic**  
[LinkedIn](https://www.linkedin.com/in/mirzacausevic/) · [Skills Portal](https://mizcausevic.com/skills/) · [GitHub](https://github.com/fknmiz)
