# Model Explainer

A lightweight, single-file web tool for turning text-based model definitions into clear, shareable diagrams.

**Live demo:** https://owen-kellie-smith.github.io/model-explainer/

---

## What this is for

Model Explainer supports **explanation, review, and shared understanding** in complex technical domains — particularly where models are defined as text (e.g. Mermaid, PlantUML, Graphviz) and need to be discussed by people.

Typical uses include:
- Explaining model structure to non-developers
- Reviewing or discussing changes to complex logic
- Making implicit structure visible during design or refactoring

---

## Supported formats

- **Mermaid** (rendered fully in the browser)
- **Graphviz (DOT)** (rendered fully in the browser)
- **PlantUML** (rendered via the public PlantUML service)

---

## Features

- Live preview with debounced rendering
- SVG and PNG export
- Shareable URLs (diagram encoded in the query string)
- No tracking, no analytics

Mermaid and Graphviz render entirely locally once loaded.  
PlantUML diagrams are encoded and rendered via the PlantUML API.

---

## Quick start (local)

1. Clone or download the repository
2. Open `index.html` in a browser

Optionally, serve locally:

```bash
python3 -m http.server 8080
```
then visit http://localhost:8080
