# Hammond Systems Laboratory LLC Website Package

This is a static, editable website package for Hammond Systems Laboratory LLC.

## What's included

- `index.html` — the main one-page website
- `assets/css/styles.css` — site styling and brand colors
- `assets/js/main.js` — mobile navigation and small enhancements
- `assets/img/` — logo, submark, favicon, and source logo sheet
- `content/site-copy.md` — editable copy reference
- `robots.txt` and `sitemap.xml` — starter search-engine files

## How to preview locally

Open `index.html` in a web browser.

For a more accurate local preview, you can run a simple local server from this folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to change the brand color

Open:

```text
assets/css/styles.css
```

At the top, edit these variables:

```css
--hsl-navy: #021124;
--hsl-blue: #043ac1;
```

The blue value was sampled from the provided Hammond Systems Laboratory logo image.

## How to publish

This package can be uploaded to most static hosting services, including Netlify, Vercel, Cloudflare Pages, GitHub Pages, or a conventional web host.

For a simple launch, upload the full contents of this folder so that `index.html` is at the web root.

## Suggested next edits

1. Replace placeholder project descriptions with final public-safe summaries.
2. Add a downloadable PDF capability statement.
3. Add a downloadable CV or industry resume.
4. Add LinkedIn and/or Google Scholar links.
5. Update `sitemap.xml` with the final live domain if different from `https://hammondsystems.io/`.
