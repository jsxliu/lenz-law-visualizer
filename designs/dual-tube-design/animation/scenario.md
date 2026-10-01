# Dual-tube simulation parameters and assumptions

## Simulation parameters

| Parameter | Value |
|---|---|
| Travel of each object's center | 303.4 mm |
| Both modeled tube lengths | 304.78 mm |
| Copper tube outside diameter | 15.9 mm |
| Copper tube inside diameter | 13.82 mm |
| Copper wall thickness | 1.04 mm |
| Copper conductivity | 49.3 MS/m |
| Magnet diameter × height | 12.64 × 25.38 mm |
| Magnet mass | 25 g |
| Magnet nominal remanence | 1.18 T |
| Stop extension beyond each tube end | 12 mm |
| Gravity | 9.80665 m/s² |
| Initial velocity | 0 m/s |

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
