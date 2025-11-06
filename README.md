# Cynic Cafe – Static Homepage

Personal static site for GitHub Pages (user site). Semantic HTML + a single mobile-first CSS file.

## Project

- Repo (recommended): `dagon575.github.io`
- Custom domain: `www.cyniccafe.top` (CNAME points to `dagon575.github.io`)
- Hosting: GitHub Pages (no build step)

## Structure

```bash
.
├── index.html        # Main page (semantic HTML)
├── style.css         # Single stylesheet (mobile-first)
├── images/           # Media assets
├── CNAME             # Custom domain for GitHub Pages
├── .gitignore        # Ignore OS/editor junk
└── DEPLOYMENT.md     # How to deploy
```

## Local Preview

```bash
python3 -m http.server 8000
# open http://127.0.0.1:8000
```

## Deploy

See DEPLOYMENT.md for one-time setup. Typical push:

```bash
git add .
git commit -m "Add static homepage"
git push -u origin main
```
