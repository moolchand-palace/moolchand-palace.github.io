# moolchand-palace.github.io

Modern single-page site for Moolchand Royal Palace.

Local testing

Serve the site locally and open http://localhost:8282:

```bash
# from the repository root
python3 -m http.server 8282
```

Deployment

- Push the repository to GitHub and enable GitHub Pages for the repository (use `main` branch or `gh-pages`).

Notes

- Images are in `/images`. For better performance convert large PNGs to WebP/AVIF and add `srcset`.
- Next improvements: add favicon, JSON-LD structured data, Lighthouse/a11y audit, and image optimization.

If you'd like, I can run a Lighthouse report and implement the top suggestions.