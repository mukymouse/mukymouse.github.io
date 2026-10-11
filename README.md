# Muhammed Ammar — personal site

Static site, no build step needed to host. Source of truth: `build_site.py` (uses `../brand/system`).

## Publish free on GitHub Pages
1. GitHub account: `mukymouse` → site at https://mukymouse.github.io/
2. New repository named exactly `<username>.github.io`, public.
3. Upload everything in this folder (index.html, work/, assets/, .nojekyll) to the repository root.
4. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Live in about a minute.

## Before publishing
- Set `EMAIL` (the new work Gmail) and `SITE_URL` (your real Pages address) at the top of `build_site.py`, then run `python build_site.py --og`.
