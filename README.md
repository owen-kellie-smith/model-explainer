# model-visualisation-demo (Standalone HTML) 
A lightweight, single‑file HTML tool for drawing graphs in the browser — no build step, no backend, no dependencies beyond standard web APIs (and optional CDN libraries if you choose to add them).

## Features
- Simple UI to create/edit graphs
- Zero setup: open `index.html` and go
- Mermaid and Graphviz runs entirely in the browser (works offline once loaded), no data leaves your machine
- (Encoded) PlantUML data does leave your machine and calls on the PlantUML API which produces the image

## Quick Start (local)
1. Clone or download this repo.
2. Open `index.html` in your browser.
   - Optionally, start a local server:
     ```bash
     # Python 3
     python3 -m http.server 8080
     # Then visit http://localhost:8080
     ```
<!--
## Live Demo (GitHub Pages)
This repo is ready for GitHub Pages. Once enabled, your app will be available at: ????
-->

## Privacy & Security
- No tracking, no analytics, no network calls by default.
- Your graphs remain in your browser unless you explicitly export or share them.

## License
MIT — see ./LICENSE.

## Attribution
- Code largely authored by you with assistance from Copilot‑style AI tools.

## Notes for Contributors
- Please open issues for bugs/feature requests.
- Keep the app dependency‑free unless there’s a compelling reason.
