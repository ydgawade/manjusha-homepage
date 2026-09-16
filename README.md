# Manjusha Khaire — Professional Homepage

Single-page portfolio site for Manjusha Khaire, PMP® — Specialist Global Agile Scrum Master (Lake Orion, Michigan).

## Contents

- `index.html` — the entire site (HTML, CSS and JS in one file, no build step, no dependencies except Google Fonts)

## Sections

Hero · About · Experience timeline · Capabilities · Certifications &amp; education · Beyond work · Contact

## Deploy with GitHub Pages

1. Repository → **Settings** → **Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main`, folder `/ (root)` → **Save**
4. Live in ~1 minute at `https://ydgawade.github.io/manjusha-homepage/`

## Custom domain (e.g. manjushakhaire.com)

1. Buy the domain (Cloudflare Registrar or Namecheap).
2. Add DNS records at the registrar:
   - `A` @ → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` www → `ydgawade.github.io`
3. Settings → Pages → **Custom domain** → enter the domain → Save.
4. Tick **Enforce HTTPS** once the certificate is issued.

Adding the custom domain through the Pages UI creates the `CNAME` file automatically.

## Editing

Everything is plain HTML. Colors live in the `:root` CSS variables at the top of `index.html`:

```css
--bg   /* page background */
--acc  /* teal accent */
--acc2 /* green accent */
```

To add a headshot, drop the image in an `assets/` folder and reference it from the hero section.
