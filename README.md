# Restaurant Apollonia 1991 - Static HTML Website

This folder contains a plain static HTML/CSS version of the demo website. No React, no build step, no server required.

## What is inside

- `index.html` - The complete website in one file (Albanian and English)
- `styles.css` - Plain CSS styling
- `assets/` - Restaurant photos and logo
- `robots.txt` - Search-engine instructions

## How to use

1. Open `index.html` directly in any web browser (Chrome, Safari, Firefox, Edge).
2. Or upload the entire folder to any static hosting service (Netlify, Vercel, Cloudflare Pages, GitHub Pages, or any simple web server).
3. Click the **SQ / EN** buttons in the top-right to switch between Albanian and English.

## Editing

Because this is static HTML, you can edit the text directly in `index.html` using any text editor (Notepad, VS Code, etc.).

- Look for `<span data-lang="sq">...</span>` for Albanian text.
- Look for `<span data-lang="en">...</span>` for English text.
- To change a phone number, search for `tel:` links.
- To replace a photo, put a new image in the `assets/` folder and update the `src` in `index.html`.

## Important notes

- The map is an embedded OpenStreetMap iframe centered on Ferizaj. Replace it with the real Google Maps embed if you want exact positioning.
- The Instagram link points to the official profile: https://www.instagram.com/restaurantapollonia1991
- This is a demo website. Do not hand it to the client until an agreement is in place.

---
Generated: 2 August 2026
