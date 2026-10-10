# Animation credits and licenses

© 2026 Jonathan Liu / OpenApparatus.

See the project-wide
[AI assistance](https://github.com/jsxliu/lenz-law-visualizer#ai-assistance).

## Presentation

Original text, video, poster, and synthesized landing sounds:
[CC BY 4.0](LICENSE-media). Viewer HTML/CSS:
[MIT](LICENSE-viewer). The sounds are illustrative contact cues, not measured acoustics.

Suggested attribution:

> “See-through animation” by Jonathan Liu / OpenApparatus (2026), CC BY 4.0.

## Hardware

The OpenApparatus hardware retains its
[CERN-OHL-W-2.0 license](https://github.com/jsxliu/lenz-law-visualizer/blob/main/LICENSE).
The animation depicts the prototype dimensions and uses its end-cap mesh at
millimeter scale. Stop planes for timing are specified separately in
[scenario.md](scenario.md).

- [See-through design and build guide](https://github.com/jsxliu/lenz-law-visualizer/tree/main/designs/see-through-design)
- [Original end-cap mesh](https://github.com/jsxliu/lenz-law-visualizer/blob/main/designs/see-through-design/parts/see_through_design_end_cap_v1.stl)
- [Original control-ring print file](https://github.com/jsxliu/lenz-law-visualizer/blob/main/designs/see-through-design/parts/free_fall_ring_v1.stl)

## Physics

The cylindrical-magnet field calculation is based on the MIT-licensed
[Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010).
The simulation adapts this field to the annular geometry and includes the
finite copper length and full radial wall integral to determine the magnet
trajectory. The matching nonmagnetic control uses analytic free fall.

Derby, Norman, and Stanislaw Olbert (2010). “Cylindrical magnets and ideal
solenoids.” *American Journal of Physics*, 78(3), 229–235.
[DOI: 10.1119/1.3256157](https://doi.org/10.1119/1.3256157).

Material inputs use conductivity and nominal remanence from the
[dual-tube scenario](https://github.com/jsxliu/lenz-law-visualizer/blob/main/designs/dual-tube-design/animation/scenario.md)
and magnet density 7850 kg/m³. See [simulation parameters and assumptions](scenario.md).

## Tools

Rendering: Three.js 0.169.0 and its STL loader
([MIT](https://github.com/mrdoob/three.js/blob/r169/LICENSE)).
Numerical computation: NumPy and SciPy.
