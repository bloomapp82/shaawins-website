# Shaawins Credit Repair — website

Demo build of the new shaawinscreditrepair.com. Single static page, no build step.

- `index.html` — the whole site (home, about, services, pricing, report checker, resources, blog, FAQs, contact, legal). Pages switch by URL hash (`#p-about`, `#p-services`, …).
- `assets/` — logo files (SVG).

## Run locally
Open `index.html` in a browser, or `npx serve .`

## Deploy
Any static host (Netlify, Vercel, GitHub Pages, cPanel). Point it at this folder; `index.html` is the entry.

## Before launch
- Replace placeholder prices, team names, blog posts and the `[LEGAL]` text with attorney-reviewed copy (CROA notice is required).
- Verify bureau mailing addresses on the Resources page.
- Wire the two forms to a real endpoint (currently demo-only: `preventDefault` in `index.html`).
- Move support email to the shaawinscreditrepair.com domain.
