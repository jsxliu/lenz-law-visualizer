# Dual-tube simulation parameters and assumptions

The animation compares a cylindrical magnet falling inside a copper tube with
a matching nonmagnetic control falling inside a clear tube. Both objects are
released simultaneously from rest and travel the same distance between stops.

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
| Initial velocity, both objects | 0 m/s |

The metric dimensions are the simulation inputs; inch equivalents are rounded.

## Predicted timing and presentation

Predicted arrival times after release are **2.737922 s** for the magnet and
**0.248750 s** for the control. These are numerical predictions using the
specified geometry and nominal material properties.

The animation is presented at 60 fps and 1440 × 900 pixels, with real-time
motion, a quarter-speed replay of the same trajectories, and a three-second
closing hold. Landing sounds mark each arrival; they are illustrative cues,
not simulated impact acoustics.

## Basic assumptions

- Both objects are released simultaneously from rest in upright tubes and remain centered.
- The magnet is a finite cylinder, uniformly magnetized along its axis.
  Braking uses the
  [Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010)
  with finite tube length and a quasistatic, mean-wall-radius approximation:
  wall resistance uses the specified thickness and conductivity, and the field
  is evaluated at the wall's mean radius.
- For this ideal comparison, the clear tube is assigned the copper tube's
  dimensions, and the nonmagnetic control is assigned the magnet's dimensions.
- The control follows ideal free fall under gravity, independent of its mass.
  Airflow and pressure buildup in the clear tube are neglected.
- Material properties are constant. Rubbing, tilt, air resistance, eddy-current
  inductance, and induced-field feedback are neglected.
- Both objects stop without bouncing at lower stops inferred from the cap geometry.
- The copper cutaway is visual only; the modeled wall remains electrically intact.
