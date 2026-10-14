# AI Productivity & Automation for Social Media Content Creation — David Hooi

Bilingual (English / 中文) landing page for D Action Consultancy's 1-day workshop:
Morning — Prompting, Planning & Writing · Afternoon — Visuals, Video & Campaign Sprint.

Intended live URL: https://dhooi266.github.io/ai-social-media-content/ (add `?lang=zh` to open in Chinese)

- `og-share-v1.jpg` — 1200×630 WhatsApp / social link preview, rendered from `og-card-source.html`
- Source parts (`_body.html`, `_base.css`, `_extra.css`) are assembled into `index.html` by `_build.js` (local only)
- `node _render.js hero` re-renders `assets/course-hero.jpg` from `assets/hero-raw.png` plus the share card
