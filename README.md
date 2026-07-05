# Portfolio Demo 01 — Dark Landing Page

A single-page dark portfolio landing page with cinematic HLS background video, GSAP scroll animations, and a scroll-driven parallax gallery.

Built as a portfolio demo piece.

## Stack

- **React 18** + **TypeScript**
- **Vite** — build tooling
- **Tailwind CSS** — styling (forced dark theme, custom HSL design tokens)
- **GSAP** (+ ScrollTrigger) — hero entrance, pinned parallax gallery, marquee
- **Framer Motion** — loading screen, scroll-reveal sections
- **hls.js** — adaptive streaming background video

## Sections

1. **Loading Screen** — rAF counter 000→100, rotating words, gradient progress bar
2. **Hero** — HLS video background, cycling role text, GSAP entrance, scroll indicator
3. **Selected Works** — 12-col bento grid with halftone overlay + hover reveal
4. **Journal** — horizontal pill cards
5. **Explorations** — pinned center + scroll-driven parallax columns with lightbox
6. **Stats** — animated counters
7. **Contact / Footer** — flipped HLS video, GSAP marquee, live status dot

## Design System

| Token       | HSL          | Use                |
| ----------- | ------------ | ------------------ |
| `--bg`      | `0 0% 4%`    | Page background    |
| `--surface` | `0 0% 8%`    | Cards / pills      |
| `--text`    | `0 0% 96%`   | Primary text       |
| `--muted`   | `0 0% 53%`   | Secondary text     |
| `--stroke`  | `0 0% 12%`   | Borders / dividers |

Accent gradient: `linear-gradient(90deg, #89AACC 0%, #4E85BF 100%)`

Fonts: **Inter** (body) + **Instrument Serif** (display, italic)

## Run locally

```bash
npm install
npm run dev      # start dev server
npm run build    # production build
npm run preview  # preview the build
```

## License

MIT — free to use as a reference or starting point.
