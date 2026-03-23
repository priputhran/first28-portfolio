# First 28 — PM Portfolio Case Study

A single-page portfolio site for the First 28 neonatal health app case study.
Built as a standalone HTML file — no build step, no dependencies, deploys directly to GitHub Pages.

## Live site

`https://YOUR_USERNAME.github.io/first28-portfolio/`

## Publishing to GitHub Pages

### Option A — Dedicated portfolio repo
```bash
# Create a new repo: first28-portfolio
git init
git add index.html _config.yml
git commit -m "feat: First 28 portfolio site"
git remote add origin https://github.com/YOUR_USERNAME/first28-portfolio.git
git push -u origin main

# In GitHub repo settings → Pages → Source: main branch, / (root)
# Site live at https://YOUR_USERNAME.github.io/first28-portfolio/
```

### Option B — docs/ folder inside the main first28 repo
```bash
# Copy into the first28 monorepo
cp index.html ../first28/docs/portfolio.html

# In GitHub repo settings → Pages → Source: main branch, /docs folder
# Site live at https://YOUR_USERNAME.github.io/first28/
```

## Customisation checklist

Before publishing, update these placeholders in `index.html`:

- `YOUR_USERNAME` → your GitHub username (appears in nav CTA, footer links, CTA section)
- `hello@yoursite.com` → your contact email
- Add your name somewhere in the footer if you want credit visible

## Design decisions

- **Single HTML file** — no build tools, no npm, no bundler. Paste and publish.
- **Google Fonts** — Lora (serif display) + DM Sans (body). Loads from CDN.
- **Scroll reveal** — pure IntersectionObserver, no libraries.
- **Interactive phone** — auto-advances through 6 app screens, clickable dots.
- **Fully responsive** — mobile nav collapses, phone mockup hides on small screens.
- **Dark mode** — not implemented (warm cream base works well in both contexts).

## Disclaimer

This portfolio page includes a prominent disclaimer that First 28 is an educational prototype,
not a clinical product. Do not remove it.
