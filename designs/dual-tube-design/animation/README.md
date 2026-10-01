# Dual-tube animation

[← Dual-tube design and build guide](https://github.com/jsxliu/lenz-law-visualizer/tree/main/designs/dual-tube-design)

**[Open animation (MP4 · 22.5 seconds)](assets/OpenApparatus-dual-tube-digital-twin.mp4)**

To save the MP4 from GitHub, click **Download raw file** (↓) on its file page.

The magnet and control are released together, shown at real time and replayed at
quarter speed. Predicted arrivals are **2.738 s** for the magnet and **0.249 s**
for the control. Landing sounds mark each arrival; the control weight landing is louder.

This fixed simulation uses the
[Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010).

- [Simulation parameters and assumptions](scenario.md)
- [Credits and licenses](credits.md)

## Publishing the web player

Set GitHub Pages to **GitHub Actions**, then run **Publish fixed animation**
on `main`. The workflow publishes only this folder.
