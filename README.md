# AristoVerse

A Next.js recreation of a nature-inspired venture studio website (inspired by Anima.ai), rebranded as **AristoVerse**.

## Theme
- Mostly organic, nature-inspired aesthetic (forest greens, cream, sage, elegant serif + modern sans)
- Ventures lean into a **biohack** visual language (mycelium, lab peptides, ambient energy, AI photocatalysts, etc.)
- Fonts: Cormorant Garamond (headings) + Manrope (body) — cool, editorial, refined

## Getting started

```bash
cd aristoverse-nextjs
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Structure
- `app/page.js` — full single-page experience
- `app/globals.css` — design system
- `app/layout.js` — fonts + metadata

Images are sourced from Unsplash (free to use). Replace with your own photography or generated assets for production.

## Customize
- Edit the `ventures` and `team` arrays in `app/page.js`
- Adjust CSS variables in `globals.css` for color palette
- Add more pages under `app/` if you want multi-page (About, Ventures detail, etc.)

Built with Next.js 14 App Router.
