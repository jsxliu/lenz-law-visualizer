# Dual-tube simulation parameters and assumptions

## Simulation parameters

| Parameter | Value |
|---|---|
| Travel of each object's center | 303.4 mm (11.945″) |
| Both modeled tube lengths | 304.78 mm (11.999″; nominal 12″) |
| Copper and clear tube outside diameter | 15.9 mm (0.626″) |
| Copper and clear tube inside diameter | 13.82 mm (0.544″) |
| Copper wall thickness | 1.04 mm (0.041″) |
| Copper conductivity | 49.3 MS/m |
| Magnet and control diameter × height | 12.64 × 25.38 mm (0.498″ × 0.999″) |
| Magnet mass | 25 g |
| Magnet nominal remanence | 1.18 T |
| Stop extension beyond each tube end | 12 mm (0.472″) |
| Gravity | 9.80665 m/s² |
| Initial velocity | 0 m/s |

The metric dimensions are the simulation inputs; inch equivalents are rounded.
The nominal 12-inch tube description retains the modeled 304.78 mm length.
Predicted arrivals are **2.737922 s** for the magnet and **0.248750 s** for the
control, using the specified geometry and nominal material properties.

The visual refresh preserves the original trajectories and timing. The video
contains 1,348 frames at 60 fps and 1440 × 900 pixels: **22.467 seconds**, with
real-time motion, a quarter-speed replay, and a three-second closing hold.

## Basic assumptions

- Both objects are released simultaneously from rest in upright tubes and remain centered.
- The magnet is uniformly magnetized. Braking uses the Derby–Olbert reproduction's
  quasistatic model: wall thickness sets resistance, with the field evaluated at
  the wall's mean radius.
- The clear tube has the same geometry as the copper tube; the nonmagnetic
  control has the same geometry as the magnet.
- The control falls freely under gravity, independent of mass; the clear tube vents freely.
- Material properties are constant. Rubbing, tilt, air resistance, eddy-current
  inductance, and induced-field feedback are neglected.
- Both objects stop without bouncing at lower stops inferred from the cap geometry.
- The copper cutaway is visual only; the modeled wall remains electrically intact.
