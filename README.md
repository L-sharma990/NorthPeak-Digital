# 🏔️ NorthPeak Digital — Agency Landing Page

> A premium, fully responsive digital agency landing page built with pure **HTML**, **CSS**, and **vanilla JavaScript** — no frameworks, no dependencies.

🔗 **Live Site:** [https://north-peak-digital-iota.vercel.app](https://north-peak-digital-iota.vercel.app)

---

## 📸 Preview

| Desktop | Mobile |
|---------|--------|
| Dark-themed glassmorphism design with animated hero, service cards, pricing tiers, testimonials, and contact form | Fully responsive layout with hamburger menu, stacked cards, and touch-optimized interactions |

---

## ⚡ Lighthouse Scores

| Category | Score |
|----------|-------|
| **Performance** | 🟢 90+ |
| **Accessibility** | 🟢 96 |
| **Best Practices** | 🟢 100 |
| **SEO** | 🟢 100 |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic structure with proper ARIA attributes |
| **CSS3** | Custom utility-class design system, animations, glassmorphism |
| **Vanilla JavaScript** | Form validation, scroll animations, mobile menu, header effects |
| **Google Fonts** | Inter (body) + Outfit (headings) — loaded non-render-blocking |
| **Vercel** | Deployment & hosting |

---

## ✨ Key Features

### Design & UI
- **Glassmorphism Design System** — frosted glass cards with `backdrop-blur`, subtle borders, and layered transparencies
- **Gradient Text Effects** — animated gradient on hero heading and metric counters
- **Micro-Animations** — hover lifts on cards, shimmer effect on CTAs, floating background orbs, fade-in reveals on scroll
- **Grid Pattern Background** — subtle dot-grid overlay for visual depth
- **Dark Theme** — premium dark color palette with curated blue brand accents

### Sections
- **Hero** — animated headline with trust stats (150+ projects, 98% retention, 4.9★ rating) and dual CTAs
- **Services** — 6-card grid (Web Dev, UI/UX, SEO, Brand Strategy, Paid Ads, Analytics & CRO) with unique icon colors
- **Results & Testimonials** — 4 metric cards (340% ROI, 2.4x leads, 67% bounce reduction, #1 rankings) + 3 client testimonial cards with star ratings
- **Pricing** — 3-tier pricing (Basic $1,499 / Pro $3,999 / Enterprise Custom) with "Most Popular" badge and glow effect on the Pro plan
- **Contact** — fully validated contact form with real-time error messages, ARIA live regions, and success confirmation
- **Footer** — brand info, quick links, social icons, and Digital Heroes attribution

### Responsiveness
- **3 breakpoints** — mobile (< 640px), tablet (640–1024px), desktop (1024px+)
- **Mobile hamburger menu** — full-screen overlay with backdrop blur
- **Touch-optimized** — proper button padding and tap targets for mobile users
- **Responsive grid** — service cards: 1 → 2 → 3 columns; pricing: 1 → 3 columns

### Performance Optimizations
- Non-render-blocking Google Fonts (`media="print" onload` pattern)
- Font fallback `@font-face` with `size-adjust` to eliminate CLS
- CSS preloading via `<link rel="preload">`
- DNS prefetching for Google Fonts domains
- Reduced GPU blur effects on mobile (64px → 16px)
- Paused CPU-intensive animations on mobile viewports
- SVG favicon as data URI (zero extra HTTP requests)
- Passive scroll event listeners
- All JavaScript at end of `<body>` (non-render-blocking)

### Accessibility (WCAG AA)
- Skip-to-content navigation link
- Semantic HTML: `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`, `<article>`
- Proper heading hierarchy: `h1` → `h2` → `h3`
- ARIA attributes: `aria-label`, `aria-hidden`, `aria-required`, `aria-expanded`, `aria-controls`
- Form validation with `role="alert"`, `aria-live="polite"`, `aria-invalid`, `aria-describedby`
- WCAG AA color contrast ratios on all text elements
- `lang="en"` on `<html>` for screen readers

---

## 📁 Project Structure

```
NorthPeak Digital/
├── index.html              # Complete single-page application (907 lines)
├── styles.css              # Custom CSS design system (580+ lines)
├── README.md               # Project documentation
├── OPTIMIZATION_CHANGELOG.md  # Performance & accessibility optimization log
└── .git/                   # Version control
```

---

## 🚀 Deployment

The site is deployed on **Vercel** with automatic deployments from the `main` branch.

**To run locally:**
1. Clone the repository:
   ```bash
   git clone https://github.com/L-sharma990/NorthPeak-Digital.git
   ```
2. Open `index.html` in your browser, or use a local server:
   ```bash
   npx serve .
   ```

---

## 📝 Optimization Changelog

See [OPTIMIZATION_CHANGELOG.md](./OPTIMIZATION_CHANGELOG.md) for a detailed log of all performance and accessibility optimizations made, including before/after contrast ratios and Lighthouse impact analysis.

---

## 👤 Author

**Lokesh Sharma**  
Built as part of the [Digital Heroes](https://digitalheroesco.com) internship qualification task.

---

## 📄 License

This project is open source and available for educational purposes.
