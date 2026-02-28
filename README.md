# cvpr26wmas.github.io

Static site for the CVPR 2026 workshop: **World Models Meet Active Sensing and Closed-Loop Planning (WMAS)**.

## Deploy (GitHub Pages)

This repository is a **GitHub Pages user site** repo (`cvpr26wmas.github.io`). GitHub Pages will serve the site from the **root of the default branch**.

- The site entrypoint is `index.html` (this redirects to `cvpr26wmas.html`).
- `.nojekyll` is included so GitHub serves files as-is.

### Publish steps

```bash
git add .
git commit -m "Add workshop site"
git remote add origin https://github.com/cvpr26wmas/cvpr26wmas.github.io.git
git push -u origin main
```

Then on GitHub, check **Settings → Pages**:

- **Source**: Deploy from a branch
- **Branch**: `main` / `(root)`

After a minute or two, the site should be live at `https://cvpr26wmas.github.io/`.

