# Product DEX — Virtuary

A clean, scalable product gallery built for live streaming. Styled with a trading-card-gallery look — fixed 9:16 card slots, click-to-enlarge closeup viewer, and a MAIN/HOLO toggle for optional foil-style lighting on the enlarged view.

Built by Virtuary as a lightweight, no-build showcase for streaming inventory on OBS (Browser Source) without reconfiguring a physical display setup between products, or to Embed in any page online.

## Tech stack

- **HTML5** — single self-contained file, no external framework
- **CSS3** — Grid layout, custom properties, `mix-blend-mode` for the holo lighting effect, no preprocessor
- **Vanilla JavaScript** — no dependencies, no build step, no bundler

## How it works

- Product images are listed in a single array (`PRODUCTS`) near the top of the `<script>` section — adding a new product is one line.
- The gallery grid, card numbering, and modal navigation all generate automatically from that array.
- Images live in the `images/` folder alongside the HTML file.

## Live demo

Hosted via GitHub Pages: `https://virtuary.github.io/product-dex-virtuary/ff2026-product-gallery.html`
