# Triple-tube animation

[← Triple-tube design and build guide](https://github.com/jsxliu/lenz-law-visualizer/tree/main/designs/triple-tube-design)

**[Watch the animation (20.72 seconds)](https://jsxliu.github.io/lenz-law-visualizer/designs/triple-tube-design/animation/)**

The player includes a **Download video (MP4)** link.

Two matching cylindrical magnets fall inside **copper and aluminum tubes**,
beside a matching nonmagnetic control in a clear tube. All three objects are
released together. The descent is shown at real time and replayed at quarter
speed; landing sounds are illustrative contact cues.

Predicted arrivals are **0.249 s** for the control, **1.673 s** for the
aluminum magnet, and **2.738 s** for the copper magnet.

The apparatus view shows yellow upper and lower caps, a clear center tube,
and dimensions in inches and millimeters.

This fixed simulation uses the existing design's nominal **½″ diameter × 1″
long magnets** and **12″ tubes**. Copper uses the dual-tube film's specified
dimensions. Aluminum uses the physics report's **16.00 mm OD × 1.22 mm wall**
(**0.62992″ OD × 0.04803″ wall**), with a 13.56 mm bore. This simulation
overrides the build guide's ⅝″ OD × 0.035″ wall aluminum stock; nominal
conductivity remains 25 MS/m. The
[Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010)
calculates both magnet trajectories with a finite tube length and the field
evaluated at the mean wall radius. The control follows analytic free fall.

The metal cutaways reveal the magnets; the physics assumes continuous,
electrically intact tube walls. These are predictions using nominal material
properties and centered motion, rather than measurements of the assembled kit.

- [Simulation parameters and assumptions](scenario.md)
- [Credits and licenses](credits.md)
