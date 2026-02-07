# 🔋 Battery Pack Architect

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow.svg)](https://buymeacoffee.com/lmf5000)
![Version](https://img.shields.io/badge/version-v78-green)

**Battery Pack Architect** is a free, open-source, browser-based tool for designing, visualizing, and **simulating** custom battery packs in 3D.

**[🚀 Launch Live Tool](https://lmf5000.github.io/battery-pack-architect/)**

---

## ⚡ What's New in v78?
The tool has evolved from a visualizer into a **physics simulator**.
* **Physics Simulation:** Calculate real-time Voltage Sag, Efficiency, and Output Power based on load (Amps).
* **Thermal Estimates:** Estimates heat generation (Watts) in both the cells and the nickel strips (Joule heating).
* **STL Export (Beta):** Export your pack geometry directly to `.STL` for 3D printing custom spacers or CAD integration.
* **Integrated Database:** Searchable library of 100+ commercial cells (Samsung 30Q, Molicel P42A, etc.) with auto-filled specs.
* **Performance:** Rendering engine overhauled (GPU instancing) to support **5,000+ cell packs** without lag.
* **Mobile Support:** Fully responsive UI for designing on phones and tablets.

---

## 📖 About

I created **Battery Pack Architect** because I needed a better way to visualize custom configurations before committing to spot welding. As someone with a passion for sustainable tech, I often find myself with a pile of 18650 cells recovered from old devices, trying to figure out the most efficient way to repack them.

This tool allows DIYers and engineers to:
1.  **Visualize** packs in 3D with realistic components (spacers, caps, busbars).
2.  **Simulate** electrical performance to ensure the pack won't overheat or sag too much under load.
3.  **Export** models to help build enclosures.

## ✨ Key Features

### 🛠️ Design & Visualize
* **Parametric Modeling:** Adjust Series (S), Parallel (P), Layers, and Spacing on the fly.
* **Layouts:** Toggle between **Hexagonal** (honeycomb) and Rectangular nesting.
* **Smart Components:** Spacers and caps automatically appear/disappear based on gap settings.
* **Multi-Chemistry:** Supports Li-ion, LiFePO4, LTO, NiMH, and Na-Ion.

### 🔌 Simulation & Analysis
* **Load Testing:** Apply a virtual load (e.g., 50A) to see how the pack performs.
* **Efficiency Logic:** Calculates voltage drop based on cell IR and nickel strip thickness/material (Pure Nickel, Steel, Copper).
* **Comparison Matrix:** Save snapshots of different builds and compare them side-by-side to optimize for Density vs. Cost.

### 💾 Build & Export
* **BOM Generation:** Automatically estimates total weight, volume, and **nickel strip length**.
* **Save/Load:** Save your custom configurations and cell presets locally via JSON.
* **STL Export:** Download the 3D model for use in Fusion 360, SolidWorks, or slicers.

---

## 🎮 Controls

* **Left Click + Drag:** Rotate the view
* **Right Click + Drag:** Pan the view
* **Scroll Wheel:** Zoom in/out
* **Touch:** Standard pinch-to-zoom and drag-to-rotate support.

## 🛠️ Installation / Running Locally

Since this tool is a standalone web application with **no build steps required**, running it is incredibly simple. You do **not** need Node.js, Python, or a server.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/battery-pack-architect.git](https://github.com/your-username/battery-pack-architect.git)
    ```
2.  **Open the file:**
    Navigate to the folder and double-click `index.html`. It will open in your default browser.

## ☕ Support the Project

Building and maintaining this tool takes many late nights of coding (and caffeine). If this tool helped you plan a build, save money on materials, or just learn something new, consider buying me a coffee!

<a href="https://buymeacoffee.com/lmf5000" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

Your support helps keep the tool free, ad-free, and funds the development of new features (like the new Physics Engine!).

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features or bug fixes:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes.
4.  Open a Pull Request.

## 📄 License

This project is licensed under the **GNU General Public License v3.0**.
You are free to use, modify, and distribute this software, provided that any derivative works are also open-source and licensed under the GPL v3.0. See the `LICENSE` file for details.

---
*Designed by Luke Formosa*
