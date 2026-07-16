# One Click Done — Portfolio Website

Video editing team portfolio: faceless YouTube editing, Shorts/Reels, motion graphics.
Single-file site (HTML + CSS + GSAP) — no build step needed.

## Files
- `index.html` — the whole website
- `assets/logo.jpg` — logo (used as social share / OG image)
- `robots.txt`, `sitemap.xml` — SEO
- `README.md` — this file

## Deploy (free, ~5 minutes)
1. Create empty GitHub repo `oneclickdone-website`
2. In this folder:
   ```
   git init
   git add .
   git commit -m "One Click Done portfolio v1"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/oneclickdone-website.git
   git push -u origin main
   ```
3. vercel.com → Add New Project → import the repo → Deploy (no settings needed)

## After deploy — 3 TODOs
1. **Domain**: replace `https://oneclickdone-website.vercel.app` with your real URL in
   `index.html` (canonical, og:url, og:image, JSON-LD), `robots.txt`, `sitemap.xml`.
2. **Form**: create a free form at formspree.io, copy the endpoint URL, paste it into
   `FORM_ENDPOINT = ""` in index.html. Until then the form runs in demo mode.
3. **SEO**: Google Search Console → add property → verify → submit sitemap.xml.

## Update content
- Stats numbers: search `data-count` in index.html
- Gig prices/features: search `gig-grid`
- Portfolio cards: search `work-grid`
