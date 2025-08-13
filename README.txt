# Precision Physiotherapy Cardiff — Static Website

This is a lightweight, static website (HTML/CSS/JS) with a working Netlify contact form and a thank‑you page.

## Files
- `index.html` — main site
- `thank-you.html` — redirect after contact form submission
- `styles.css` — site styling
- `script.js` — minimal JS (year auto-updates)
- `assets/hero.jpg` and `assets/logo.png` — images
- `favicon.png` — browser tab icon

## Deploy (GitHub → Netlify)
1. Create a new **GitHub repository** (empty).
2. Upload **all files in this folder** to the repo (drag & drop via the GitHub web UI).
3. In **Netlify**: Add new site → Import from Git → choose your repo.
4. Build settings: **No build command**, **Publish directory**: `/` (root).
5. Deploy.

## Enable Email Notifications
- In Netlify: Site → **Forms** → you'll see `contact` after the first submission.
- Go to **Site settings → Forms → Form notifications → Add notification → Email** and add your Outlook address.

## Edit Content
- Hero tagline: in `index.html` inside the `<section class="hero">`.
- Services: edit the cards in the Services section of `index.html`.
- Email/Instagram links: search `mailto:` and `instagram.com` in `index.html`.
- Colours: adjust CSS variables in `styles.css` (`--brand`, etc.).
- Images: replace files in `assets/` with the same names.