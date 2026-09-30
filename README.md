# HMJ for Audit & Advisory — CRAZY Edition

Premium bilingual one-page corporate website for HMJ in Amman, Jordan.

## Open in VS Code
1. Extract the ZIP.
2. Open the `HMJ_Website_CRAZY` folder in VS Code.
3. Install the VS Code extension **Live Server** if needed.
4. Right-click `index.html` -> **Open with Live Server**.

## Main files
- `index.html` — page structure + SEO + structured data
- `styles.css` — full responsive design and animations
- `script.js` — Arabic/English switching, intro sequence, counters, parallax, animated line, scroll reveal and navigation interactions
- `assets/` — visual assets, favicon and social share image
- `robots.txt`, `sitemap.xml`, `site.webmanifest` — deployment/search files

## Language
Use the EN / عربي switch in the navbar. Arabic is RTL and can also be opened with `?lang=ar`.

## Before publishing
Confirm the final domain, all phone numbers and partner details with HMJ, then update canonical/OG/sitemap URLs if the final domain differs from `www.rh-audit.com`.

## Deployment
This is a static site and works on GitHub Pages, Netlify, Vercel or normal shared hosting.


## Final polish
- Main photography now loads in high resolution from Pexels CDN, with bundled local fallbacks.
- The “Talk to our experts” CTA has protected spacing so it does not cover the HMJ/company heading on desktop or mobile.
- Hero image is prioritized for fast loading; below-the-fold photography lazy-loads.

For production, keep internet access enabled so the HD CDN images load. The local fallback images are included in `assets/`.
