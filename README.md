# Tricon

Static mirror of <https://tricon-staging.pages.dev/>, captured 2026-09-10.

Draw icons on a grid of squares and triangles, or trace them from an image. Export as PNG, SVG or JSON.

The files here are the site exactly as served: the built `index.html`, the Vite bundle in `assets/`, icons, `manifest.json` and `robots.txt`. Asset paths are root-absolute (`/assets/...`), so serve the folder from a domain root, e.g.

```bash
python3 -m http.server 8000
```

then open <http://localhost:8000/>.
