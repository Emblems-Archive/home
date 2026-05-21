# Emblems Archive — Static Registry

A static, open-source registry of legal, civil and humanitarian emblems.

Contents
- Static website (HTML/CSS/JS) for a concise, Wikipedia-style registry.
- Local images stored in `assets/symbols/` (see `ATTRIBUTION.md` regarding rights).

Quick start (preview locally)
1. From the repository root run a simple HTTP server (Python 3):

```bash
python -m http.server 8000
# then open http://localhost:8000/ in your browser
```

2. Or use the VS Code Live Server extension to preview the site.

Repository structure
- `index.html` — English registry dashboard (site root)
- `registry/<slug>/index.html` — emblem detail pages
- `assets/` — styles and symbol images

Contributing
- See `CONTRIBUTING.md` for guidelines and the PR workflow.

License
- Code and site assets created by repository contributors are licensed under the MIT License (see `LICENSE`).
- Note: emblem images in `assets/symbols/` may be subject to third-party rights. Check `ATTRIBUTION.md` before reusing or publishing.