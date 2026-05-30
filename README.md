# Color Blind Test & Vision Simulator

A lightweight, privacy-focused, single-page web application that allows users to screen for color vision deficiencies using official Ishihara plates and simulate color blindness on uploaded images.

🚀 **Live Demo:** [https://heretool.com/color-blind-test](https://heretool.com/color-blind-test)

## 🛠️ Features

- **Ishihara Plate Test:** Covers 10 standard test groups (plates 1-10) to screen for red-green and total color blindness.
- **Real-time Color Blindness Simulator:** Allows users to upload any image locally and view it through the eyes of someone with *Deuteranopia*, *Protanopia*, or *Achromatopsia*.
- **100% Privacy & Local Processing:** No database, no backend. Image processing and simulation are performed purely client-side using the HTML5 Canvas API and SVG filters.
- **High Performance:** Built with pure static HTML, modern CSS grid layout, and vanilla JavaScript. Zero dependencies.

## 📦 File Structure

```text
├── index.html          # Main application file (HTML, CSS, and JS combined)
├── LICENSE             # MIT Open Source License
├── README.md           # Project documentation
└── ishihara/           # (Required) Directory for Ishihara test plates (1.webp - 10.webp)