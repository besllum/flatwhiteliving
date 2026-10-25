# Flat White Living — website

Static HTML site, deployed with Vercel from the `main` branch (every push to `main` publishes automatically).

## Structure
- `*.html` — pages (`index.html` is the home page). Plain static HTML: no build step, no JavaScript framework.
- `images/` — photographs, SEO-named (max. 1600 px on the long side)
- `assets/css/styles.css` — styles
- `sitemap.xml`, `robots.txt`, `llms.txt` (summary of the site for AI search engines)
- `vercel.json` — cache headers

## Domain
Canonical URLs, `sitemap.xml`, `robots.txt` and `llms.txt` use `https://www.flatwhiteliving.com/`.
Connect that domain in Vercel → Settings → Domains.

When a page is added: add it to `sitemap.xml` and `llms.txt`.

All project photographs © Flat White Living.
