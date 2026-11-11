# QG Solutions site

Static site. No build step. Hosted on GitHub Pages.

- `index.html` — public landing page
- `meet-qg/index.html` — UNLISTED booking page (Calendly). Not linked anywhere. Share the URL directly.
- `assets/` — logo, favicon, shared stylesheet

## Two things to edit before publishing
1. `meet-qg/index.html` — set `CALENDLY_URL` to your Calendly event link.
2. `index.html` — replace `YOUR_FORM_ID` in the form action with your Formspree form ID.

## Moving hosts later
Upload this whole folder to any static host (Netlify, Cloudflare Pages, IONOS, etc.). Nothing here depends on GitHub.
