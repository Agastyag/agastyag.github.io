# agastyagupta.me

Personal site for Agastya Gupta. A single static page, no build step.

- `index.html` — the whole site (markup + styles). Company logos are inlined as SVG where available.
- `assets/` — headshot, Circuit logo, favicon.
- `CNAME` — custom domain for GitHub Pages (`agastyagupta.me`).
- `.nojekyll` — tells Pages to serve files as-is.

Preview locally:

```bash
python3 -m http.server 8765
```

Deploys automatically from `master` via GitHub Pages.
