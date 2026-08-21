# ravish.digital

Static site for Ravish Digital Studio.

- `index.html` — the page (~86 KB)
- content-hashed assets at the repo root — images, fonts, video and JS, served as individual files
- `rdslogo.png` — 1200×630 social preview card (stable URL, referenced by `og:image` / `twitter:image`)
- `vercel.json` — long-lived immutable caching for the hashed assets, 1-day revalidating cache for the social card, no-cache for the HTML

Deployed on Vercel. DNS at Cloudflare.
