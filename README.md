# Trajche Sachkarski — Portfolio

Personal portfolio website for Trajche Sachkarski, UX/UI Designer & Frontend Developer based in Macedonia.

**Live:** [tsachkarski.github.io](https://tsachkarski.github.io) *(or your preferred hosting)*

---

## Overview

A single-file HTML portfolio built with a manga/editorial design aesthetic — cream background, black ink borders, and red as the sole accent colour. No frameworks, no build tools, no dependencies.

---

## Stack

- **HTML / CSS / JavaScript** — everything in one self-contained file
- **Fonts** — Bebas Neue, Barlow Condensed, Space Mono (Google Fonts)
- **Zero dependencies** — no npm, no bundler, no runtime libraries

---

## Structure

```
portfolio_v4_manga.html
│
├── Nav              — sticky, scrolls to sections
├── Hero             — name, role, manga panel grid, live status, ticker bar
├── About            — bio, skills, design philosophy
├── Work             — AgentOS + Forma case studies with live iframe previews
├── Expertise        — UX/UI Design · Motion & Prototyping · Frontend Dev
├── Contact          — email
└── Footer
```

---

## Features

**Design**
- Manga editorial aesthetic — cream/black/red, Bebas Neue headlines
- Animated hero panel grid with embedded photo, MOTION FIRST panel, and live status indicator
- Skills ticker bar
- Custom cursor with ring follow effect
- Scroll-triggered reveal animations on all sections

**Projects**
- Expandable case study rows with browser mockup device frames
- Live iframe previews of [AgentOS](https://tsachkarski.github.io/AgentOS/) and [Forma](https://tsachkarski.github.io/Forma/)
- Lazy-loaded iframes — Load Preview on demand

**Accessibility & Code**
- WCAG 2.1 AA contrast on all primary text
- Semantic HTML with ARIA labels
- Fully keyboard navigable
- Mobile responsive — single column layout below 900px

---

## Projects Featured

### AgentOS
AI-augmented contact center agent interface. 5 screens, single HTML file, pure CSS animations, WCAG 2.1 AA compliant, desktop + mobile responsive.

→ [tsachkarski.github.io/AgentOS](https://tsachkarski.github.io/AgentOS/)

### Forma
Luxury furniture e-commerce experience. 5 pages, full design system (6-colour tokens, dual-font scale, 3 motion curves), 3,326 lines HTML/CSS/JS, zero dependencies. Iterated from 8.3 → 9.1 across 4 scored audits.

→ [tsachkarski.github.io/Forma](https://tsachkarski.github.io/Forma/)

---

## Local Development

No setup required. Open the file directly in any modern browser:

```bash
open portfolio_v4_manga.html
```

Or serve it locally to avoid iframe CORS restrictions on the project previews:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

---

## Deployment

The portfolio is a single HTML file — deploy anywhere that serves static files.

**GitHub Pages**
```bash
# Place the file in your repo root as index.html
cp portfolio_v4_manga.html index.html
git add index.html
git commit -m "deploy portfolio"
git push
```

**Netlify / Vercel** — drag and drop the file into the dashboard.

---

## Contact

**Email:** trajche.sachkarski@gmail.com  
**Location:** Macedonia · Remote OK  
**Status:** Available for full-time roles & freelance projects
