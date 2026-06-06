# Turing Pattern Generator (Reaction-Diffusion)

[![Live demo](https://img.shields.io/badge/live-demo-blue)](https://novasolver.jp/tools/turing-patterns.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Gray-Scott reaction-diffusion system: spots, stripes, mazes from two parameters.

🌐 **[Try it live](https://novasolver.jp/tools/turing-patterns.html)** · 🌍 [EN](https://novasolver.jp/en/tools/turing-patterns.html) · 🌏 [ZH](https://novasolver.jp/zh/tools/turing-patterns.html)

---

## Why

Gray-Scott reaction-diffusion system: spots, stripes, mazes from two parameters. Built as part of **[NovaSolver](https://novasolver.jp)** — 1600+ interactive physics & engineering simulators.

## Tech

- **Vanilla JavaScript** — no build step, no framework lock-in
- **Canvas / Chart.js** rendering
- **MathJax** for equations
- **Self-contained** — drop `index.html` anywhere and it runs

## Run locally

```bash
git clone https://github.com/novasolver/turing-pattern-generator
cd turing-pattern-generator
python -m http.server 8000
# open http://localhost:8000
```

## Use it in your project

The `index.html` is self-contained and MIT-licensed. Take it, fork it, embed it.

## Part of NovaSolver

This repo is a "flagship" version of one simulator from the [physics-simulators monorepo](https://github.com/novasolver/physics-simulators). The monorepo has 1600+ more tools across:

- Structural mechanics (beam, buckling, fatigue, FEM)
- Fluid dynamics (Reynolds, Bernoulli, potential flow, CFD basics)
- Heat transfer (1D/2D conduction, fins, radiation)
- Electromagnetics (RC/RL, Bode, antennas, FDTD)
- Multi-physics & math fun (Lorenz, boids, Lissajous, n-body)

→ **[novasolver.jp/tools/](https://novasolver.jp/tools/)** for the full catalog.

## License

[MIT](LICENSE)
