# AGENTS.md

## Cursor Cloud specific instructions

This is a static HTML/CSS/JS site (no build step, no package manager, no dependencies).

### Running the dev server

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/index.html` in a browser.

### Lint / Test / Build

There are no linters, test frameworks, or build tools configured. The CI workflow (`.github/workflows/blank.yml`) is a no-op stub. HTML/CSS/JS can be validated manually in the browser or with external tools (e.g., `npx html-validate index.html`).

### Key files

| File | Purpose |
|---|---|
| `index.html` | Single-page static site |
| `style.css` | All styles (responsive, CSS custom properties) |
| `script.js` | Vanilla JS interactivity (tabs, smooth scroll, reveal animations) |
