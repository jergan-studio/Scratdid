# 🚀 scratdid

**scratdid** is a custom TurboWarp-powered Scratch wrapper and editor mod interface. It allows users to instantly load Scratch projects, run them at high performance (60+ FPS), enable custom interpolation, and utilize modded features—all inside a dark-themed custom UI.

---

## ✨ Features

- **⚡ High-FPS Performance:** Choose between **30, 60, 120, or 240 FPS** mode.
- **🎨 Custom Dark Theme:** Built-in dark UI for an optimized editor experience.
- **✨ Motion Interpolation:** Enable sub-frame movement for smooth 60fps+ animations.
- **✏️ High-Quality Pen:** Crisp, high-resolution rendering for pen projects.
- **🔗 Flexible URL / ID Parser:** Paste standard Scratch links (`https://scratch.mit.edu/projects/1234567`), TurboWarp links, or raw project IDs directly into the search bar.

---

## 🛠️ How It Works

`scratdid` uses TurboWarp's embedding protocol to safely wrap project assets and settings inside an optimized UI frame, avoiding browser security restrictions while dynamically passing engine options via URL query parameters:

```text
[https://turbowarp.org/](https://turbowarp.org/)[PROJECT_ID]/embed?fps=[30|60|120|240]&interpolate=true&hqpen=true
