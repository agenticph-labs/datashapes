# DataShapes — Interactive 3D Data Visualization

[![Status: Demo-ready](https://img.shields.io/badge/status-demo--ready-22c55e.svg)](https://github.com/agenticph-labs/datashapes)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An interactive 3D data-visualization prototype where geometric forms respond to data inputs in real time. Built with Three.js, the scene cycles through morphing shapes — sphere, cube, torus, cone, cylinder, octahedron — each animated with particle systems, dynamic lighting, and smooth transitions.

> **Demo-ready** — Open `index.html` in any modern browser. No build step, no dependencies.

---

## What It Does

- **Real-time 3D rendering** — Six geometric primitives morph and animate in a dark-theme scene with ambient and point lighting.
- **Particle systems** — Each shape emits a trail of particles that react to mouse movement.
- **Data-driven styling** — Shape color, particle behavior, and rotation speed shift as the cycle progresses, simulating how data attributes can drive visual output.
- **Full-screen experience** — Auto-resizing canvas, keyboard shortcut `h` to toggle the HUD, and a minimal UI overlay.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **3D Engine** | Three.js (r128+) via CDN |
| **Language** | Vanilla JavaScript (ES6 modules) |
| **Styling** | CSS with a dark cyberpunk theme |
| **Deployment** | Static hosting (GitHub Pages, Netlify, etc.) |

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)

### Run Locally

```bash
# Clone the repo
git clone https://github.com/agenticph-labs/datashapes.git
cd datashapes

# Serve with any static server
python3 -m http.server 8000
# Or use VS Code Live Server, npx serve, etc.

# Open in browser
open http://localhost:8000
```

### Deploy to GitHub Pages

1. Push to `main` branch
2. Go to **Settings → Pages**
3. Select `main` branch, root folder
4. Site is live at `https://agenticph-labs.github.io/datashapes/`

---

## Controls

| Key | Action |
|-----|--------|
| `h` | Toggle HUD overlay |
| Mouse move | Look around / influence particle direction |
| (auto) | Shape morphs every few seconds |

---

## Project Structure

```
datashapes/
├── index.html       # Main application (HTML + CSS + Three.js)
├── README.md        # This file
├── LICENSE          # MIT License
└── .gitignore       # Standard ignores
```

---

## License

MIT — see [LICENSE](LICENSE).

---

*Built by [agenticPH Labs](https://agenticph-labs.github.io/portfolio)*
