# agastyag.github.io

Personal site for Agastya Gupta. A single static page, no build step.

- `index.html` — the whole site (markup + styles). Company logos are inlined as SVG where available.
- `assets/` — headshot, Circuit logo, favicon.
- `.nojekyll` — tells Pages to serve files as-is.

Preview locally:

```bash
python3 -m http.server 8765
```

Deploys automatically from `master` via GitHub Pages to https://agastyag.github.io/.

To use a custom domain later, register it, point its DNS at GitHub Pages, and add a `CNAME` file containing the domain.
