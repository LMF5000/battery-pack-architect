# 🔋 Battery Pack Architect

**A browser-based 3D design, visualization, and simulation tool for DIY Li-ion battery packs.**

[**🚀 Launch Live Tool**](https://lmf5000.github.io/battery-pack-architect/)

## Overview
Battery Pack Architect is a parametric CAD tool designed for hobbyists and engineers building custom battery packs (18650, 21700, and more). Unlike simple calculators, this tool visualizes your pack in 3D, calculates physical dimensions, and **simulates electrical performance** under load.

## ✨ New in v78
* **Physics Simulation:** Calculates real-time Voltage Sag, Output Power, and Efficiency based on load.
* **Thermal Estimates:** Estimates heat generation (Watts) in both the cells and the nickel strips (Joule heating).
* **STL Export (Beta):** Export your design geometry directly to .STL for 3D printing spacers or CAD integration.
* **Expanded Database:** Integrated searchable database of 100+ commercial cells (Samsung, Molicel, etc.).
* **Performance:** Rendering engine overhauled to support 5,000+ cell packs via GPU instancing.
* **Mobile Support:** Fully responsive UI for designing on the go.

## Key Features
* **Parametric Design:** Adjust Series (S), Parallel (P), Layers, and Spacing dynamically.
* **Multi-Chemistry:** Supports Li-ion, LiFePO4, LTO, NiMH, and Na-Ion.
* **Cost & Weight:** Auto-calculates total pack weight, volume, and estimated BOM cost.
* **Save/Load:** Save your custom configurations and cell presets locally via JSON.

## Tech Stack
* **Three.js:** For high-performance WebGL 3D rendering.
* **Vanilla JS (ES6):** No build steps required, run it directly from the HTML file.

## License
This project is licensed under the **GNU General Public License v3.0**.
*Note: This software is a visualization aid and not a substitute for professional engineering certification.*