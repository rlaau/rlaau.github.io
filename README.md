# rlaau.github.io

Personal website for https://rlaau.github.io/.

This is a static GitHub Pages portfolio for `rlaau`, focused on systems work:
static analysis, graph analysis, specialized benchmarks, streaming pipelines,
reactive frameworks, and quant-oriented tooling.

## Preview Locally

From this directory:

```bash
cd /home/rlaaudgjs5638/trash/website/rlaau.github.io
python3 -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173/
```

Stop the server with `Ctrl+C`.

You can also open the HTML file directly:

```text
/home/rlaaudgjs5638/trash/website/rlaau.github.io/index.html
```

Using the local server is preferred because it matches the way GitHub Pages
serves relative assets.

## Deployment

No build step is required. This repository is served as static GitHub Pages
content. Once changes are pushed or synced to the GitHub Pages repository, the
public site updates at:

```text
https://rlaau.github.io/
```

## Structure

- `index.html`: the full static portfolio page.
- `assets/projects/`: project screenshots and diagrams used by the site.
- `manifest.json`: browser/PWA metadata.
- `asset-manifest.json`: simple inventory of static assets.
- `robots.txt`, `favicon.ico`, `logo192.png`, `logo512.png`: site metadata assets.

## Maintenance Notes

- Keep paths relative, such as `./assets/projects/...`, so the site works both
  locally and on GitHub Pages.
- Update project claims carefully when repository or PR status changes.
- The Gno fuzzer PR should be described as proposed external work, not as a
  merged contribution.
