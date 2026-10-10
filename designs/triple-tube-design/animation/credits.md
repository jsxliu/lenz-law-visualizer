# Animation credits and licenses

© 2026 Jonathan Liu / OpenApparatus.

See the project-wide
[AI assistance](https://github.com/jsxliu/lenz-law-visualizer#ai-assistance).

## Presentation

Original text, video, poster, and synthesized landing sounds:
[CC BY 4.0](LICENSE-media). Viewer HTML/CSS:
[MIT](LICENSE-viewer). The sounds are illustrative contact cues, not measured acoustics.

Suggested attribution:

> “Triple-tube animation” by Jonathan Liu / OpenApparatus (2026), CC BY 4.0.

## Hardware

The OpenApparatus hardware retains its
[CERN-OHL-W-2.0 license](https://github.com/jsxliu/lenz-law-visualizer/blob/main/LICENSE).
The animation depicts the triple-tube design and uses its original end-cap
mesh at millimeter scale. Stop positions and modeled dimensions are specified
in [scenario.md](scenario.md).

- [Triple-tube design and build guide](https://github.com/jsxliu/lenz-law-visualizer/tree/main/designs/triple-tube-design)
- [Original end-cap mesh](https://github.com/jsxliu/lenz-law-visualizer/blob/main/designs/triple-tube-design/parts/cap_triple_tube_design_v1.stl)
- [Optional control-cylinder print file](https://github.com/jsxliu/lenz-law-visualizer/blob/main/designs/triple-tube-design/parts/control_weight_cylinder_3D_print_v1.stl)

## Physics

Field and fall calculations use the MIT-licensed
[Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010).
Both magnets use its finite-length, mean-wall-radius braking model. Apparatus
geometry, cap stops, and the analytic free-fall control are additions for the
animation.

Derby, Norman, and Stanislaw Olbert (2010). “Cylindrical magnets and ideal
solenoids.” *American Journal of Physics*, 78(3), 229–235.
[DOI: 10.1119/1.3256157](https://doi.org/10.1119/1.3256157).

Copper and magnet inputs follow the existing
[dual-tube scenario](https://github.com/jsxliu/lenz-law-visualizer/blob/main/designs/dual-tube-design/animation/scenario.md).
Aluminum geometry (6.78 mm inner radius and 1.22 mm wall) follows J Liu,
*A Review and Independent Study of Magnetic Braking in Conducting Tubes*
(September 29, 2026), §4.3, Table 3, page 4. The animation retains its
12-inch tube length and 25 MS/m aluminum conductivity; it does not adopt
the report's five-foot length or 24 MS/m conductivity.

Aluminum conductivity follows Kaiser Aluminum's typical **6061-T6** value in
[Soft Alloy Tube & Pipe, Alloy 6061 physical properties, PDF page 13](https://online.kaiseraluminum.com/depot/PublicProductInformation/Document/1011/Kaiser_Aluminum_Soft_Alloy_Tube.pdf#page=13).
See [simulation parameters and assumptions](scenario.md) for the inputs and
the three-path configuration.

## Tools

Rendering: Three.js 0.169.0 and its STL loader
([MIT](https://github.com/mrdoob/three.js/blob/r169/LICENSE)).
Numerical computation: NumPy and SciPy.
