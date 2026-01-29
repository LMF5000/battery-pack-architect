# 🔋 Battery Pack Architect

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow.svg)](https://buymeacoffee.com/lmf5000)

**Battery Pack Architect** is a free, open-source, browser-based tool for designing, visualizing, and estimating the specs of custom battery packs in 3D.

**[🚀 Try it Live Here](https://LMF5000.github.io/battery-pack-architect/)**

---

## 📖 About

I created **Battery Pack Architect** because I needed a better way to visualize custom battery configurations before committing to spot welding. As a mechanical engineer with a passion for sustainable tech, I often find myself with a pile of 18650 cells recovered from old devices, trying to figure out the most efficient way to repack them.

This tool allows DIYers and engineers to:
* Visualize packs in **3D** with realistic components (spacers, caps, busbars).
* Toggle between **Hexagonal** (honeycomb) and Rectangular nesting.
* Calculate **Nickel Strip requirements** instantly.
* Estimate **Cost, Weight, Volume, and Electrical Specs** (Voltage/Ah/Wh).
* **Compare** multiple configurations side-by-side to find the best fit.

## ✨ Features

* **Real-time 3D Rendering:** Built with [Three.js](https://threejs.org/). Rotate, pan, and zoom around your pack.
* **Custom Cell Specs:** Pre-loaded presets for 18650, 21700, LiFePO4, LTO, and more—or enter custom dimensions.
* **Smart Logic:**
  * Spacers automatically appear/disappear based on gap settings.
  * Nickel strip length is calculated based on busbar geometry.
* **Comparison Matrix:** Save snapshots of different builds and compare them in a table to optimize for density, cost, or power.
* **Privacy Focused:** Runs entirely in your browser. No data is sent to a server.

## 🎮 Controls

* **Left Click + Drag:** Rotate the view
* **Right Click + Drag:** Pan the view
* **Scroll Wheel:** Zoom in/out

## 🛠️ Installation / Running Locally

Since this tool is a standalone web application with no build steps required, running it is incredibly simple.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/battery-pack-architect.git](https://github.com/your-username/battery-pack-architect.git)
    ```
2.  **Open the file:**
    Navigate to the folder and double-click `index.html`. It will open in your default browser.

That's it! You do not need Node.js, Python, or a server to run this.

## ☕ Support the Project

Building and maintaining this tool takes many late nights of coding (and caffeine). If this tool helped you plan a build, save money on materials, or just learn something new, consider buying me a coffee!

<a href="https://buymeacoffee.com/lmf5000" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

Your support helps keep the tool free, ad-free, and funds the development of new features.

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
