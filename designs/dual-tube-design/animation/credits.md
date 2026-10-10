# Animation credits and licenses

© 2026 Jonathan Liu / OpenApparatus.

See the project-wide [AI assistance](../../../README.md#ai-assistance).

## Presentation

Original text, video, poster, and synthesized landing sounds:
[CC BY 4.0](LICENSE-media). Viewer HTML/CSS:
[MIT](LICENSE-viewer). The sounds are illustrative contact cues, not measured acoustics.

Suggested attribution:

> “Dual-tube animation” by Jonathan Liu / OpenApparatus (2026), CC BY 4.0.

## Hardware

The OpenApparatus hardware retains its [CERN-OHL-W-2.0 license](https://github.com/jsxliu/lenz-law-visualizer/blob/main/LICENSE).
The animation uses the original end-cap mesh at millimeter scale.

- [Dual-tube design and build guide](https://github.com/jsxliu/lenz-law-visualizer/tree/main/designs/dual-tube-design)
- [Original end-cap mesh](https://github.com/jsxliu/lenz-law-visualizer/blob/main/designs/dual-tube-design/parts/cap_lenz_visualizer_v2.stl)

## Physics

Field and fall calculations use the
[Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010).
Apparatus geometry, cap stops, and the free-fall control are additions for this animation.

Derby, Norman, and Stanislaw Olbert (2010). “Cylindrical magnets and ideal
solenoids.” *American Journal of Physics*, 78(3), 229–235.
[DOI: 10.1119/1.3256157](https://doi.org/10.1119/1.3256157).

Copper and magnet inputs are adapted from Jonathan Liu's physics-class report,
“A Review and Independent Study of Magnetic Braking in Conducting Tubes.”
See [simulation parameters and assumptions](scenario.md) for this animation's configuration.

## Tools

Rendering: Three.js 0.169.0 and its STL loader
([MIT](https://github.com/mrdoob/three.js/blob/r169/LICENSE)).
Numerical computation: NumPy and SciPy.
