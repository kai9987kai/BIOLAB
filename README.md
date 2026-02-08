# BIOLAB

**BIOLAB** is a **browser-based biology sandbox**: a small collection of “BIO innovation tools” implemented as a static web app (HTML/CSS/JS) with multiple mini-labs (cellular automata, genetic algorithms, CRISPR concept tooling, protein visualization, and a research hub).  
Open `index.html` and explore the tools locally—no build step required.  

---

## What’s inside

This repo is structured as a simple front-end app with a main page and feature modules:

### Included mini-labs
- **Cellular Automata Lab** (`cellular-automata.js`)  
  Explore grid-based biological/complex-systems dynamics (useful for “growth”, patterning, emergence experiments).
- **Genetic Algorithm Playground** (`genetic-algorithm.js`)  
  Run evolutionary optimization experiments (populations, mutation/selection loops, fitness exploration).
- **CRISPR Designer (educational)** (`crispr-designer.js`)  
  A concept/learning-oriented UI for thinking about guide design and sequence constraints.
- **Protein Visualizer** (`protein-visualizer.js`)  
  A module intended for exploring proteins/structures visually in the browser.
- **Research Hub** (`research-hub.js`)  
  A place to centralize links, references, and research workflows around the above tools.

### App shell
- `index.html` — the entry point UI
- `app.js` — app controller / wiring between modules
- `style.css` — global styling

---

## Run it locally

Because this is static HTML/CSS/JS, you can technically double-click `index.html`.  
However, a local server is recommended (avoids browser restrictions and matches real hosting behavior more closely).

### Option A — Python
```bash
python -m http.server 8080
