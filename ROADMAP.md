# Personal Website — Roadmap

Static single-page portfolio site. Deployed to GitHub Pages.

**Live:** [lishuai8888.github.io/Personal-Website](https://lishuai8888.github.io/Personal-Website/)

**Stack:** Vanilla HTML/CSS/JS — no build step, no framework. Single `index.html`.

---

## Legend

- `[x]` Done
- `[ ]` Not started

---

## v1 — Current (Live) ✅

- [x] Single-page design — dark theme, amber accent, JetBrains Mono + Syne + Instrument Serif
- [x] Hero section — name (EN + CN), title, one-liner description
- [x] About section — background, role, interests
- [x] Projects section — Equity Hub, Algo Trading, Travel App cards with links
- [x] Skills section — Python, FastAPI, React, Bloomberg/LNG domain
- [x] Contact section — LinkedIn, GitHub, email
- [x] OG meta tags — title, description, image for social sharing
- [x] Favicon — LS monogram SVG
- [x] Mobile-responsive layout
- [x] Light/dark mode variants (v2.html, v3.html drafts exist)

---

## v2 — Planned

### Content

- [x] Add algo trading system to projects — IBKR Algo Trading System card (RSI d2, 144-combo optimizer, paper trading)
- [x] Add Equity Hub to projects — personal trading intelligence platform card (React + FastAPI, deployed)
- [x] Add LNG diversion analysis to projects (Kirk's approximation, spread option pricing)
- [ ] Add a writing/blog section (research notes, market commentary)
- [ ] Update resume PDF — ensure `Li_Shuai_CV.pdf` is latest version

### UX

- [x] Smooth scroll with active nav highlight (IntersectionObserver — already implemented)
- [x] Skills section with visual proficiency bars (3 categories × 5 skills each)
- [x] Animated entrance for sections (scroll-triggered reveal via IntersectionObserver)
- [ ] Project cards: add live demo link + GitHub link per card (GitHub links added; live demo TBD)
- [x] Print-friendly CV stylesheet (white bg, hides nav/code panels, reveal override)

### Technical

- [x] Add sitemap.xml for SEO (with `<link rel="sitemap">` in head)
- [ ] Move to a proper build pipeline (Vite) to support component reuse
- [ ] Self-host fonts to avoid Google Fonts dependency
- [ ] Lighthouse audit — aim for 100/100 performance + accessibility

---

## Known Issues

- `tweaks-panel.jsx` is a local dev helper — not part of the deployed site
- Multiple draft versions (`v2.html`, `v3.html`) should be consolidated or deleted
- Resume PDF should be verified to match current role/projects
