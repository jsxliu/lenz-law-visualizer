# Triple-tube simulation parameters and assumptions

The animation compares matching cylindrical magnets falling inside copper
and aluminum tubes with a nonmagnetic control in the clear center tube.
All three objects are released simultaneously from rest and travel the same
distance between stops.

## Simulation parameters

| Parameter | Value |
|---|---|
| Travel of each object's center | 303.42 mm (11.946″) |
| All modeled tube lengths | 304.8 mm (12″) |
| Copper outside × inside diameter | 15.90 × 13.82 mm (0.626″ × 0.544″) |
| Copper wall thickness | 1.04 mm (0.041″) |
| Copper conductivity | 49.3 MS/m |
| Aluminum outside × inside diameter | 16.00 × 13.56 mm (0.630″ × 0.534″) |
| Aluminum wall thickness | 1.22 mm (0.048″) |
| Aluminum conductivity | 25.0 MS/m (nominal 6061-T6) |
| Clear tube outside × inside diameter | 15.875 × 12.700 mm (⅝″ × ½″) |
| Clear tube wall thickness | 1.5875 mm (1/16″) |
| Each magnet and control diameter × height | 12.64 × 25.38 mm (0.498″ × 0.999″) |
| Each magnet mass | 25 g |
| Each magnet nominal remanence | 1.18 T |
| Stop extension beyond each tube end | 12 mm (0.472″) |
| Gravity | 9.80665 m/s² |
| Initial velocity, all three objects | 0 m/s |

The metric dimensions are the simulation inputs; inch equivalents are rounded.
The simulated aluminum wall is thicker than the build guide's 0.035″ stock.
See [credits](credits.md) for the geometry and material sources.

## Predicted timing and presentation

Predicted arrival times after release are **2.738122 s** for the copper magnet,
**1.673317 s** for the aluminum magnet, and **0.248758 s** for the control.
These are numerical predictions using the specified geometry and nominal
material properties. The two magnet times reflect both conductivity and tube geometry.

The animation is presented at 60 fps and 1440 × 900 pixels, with real-time
motion, a quarter-speed replay of the same trajectories, and a three-second
closing hold. Landing sounds mark each arrival; they are illustrative cues,
not simulated impact acoustics.

## Basic assumptions

- All objects remain centered in upright tubes.
- Each magnet is a finite cylinder, uniformly magnetized along its axis.
  Braking uses the
  [Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010)
  with finite tube length and a quasistatic, mean-wall-radius approximation:
  wall resistance uses the specified thickness and conductivity, and the field
  is evaluated at the wall's mean radius.
- The magnet paths are calculated independently; mutual magnet forces and
  magnetic coupling between tubes are neglected because of large spacing and insignificant induced friction.
- The control follows ideal free fall, independent of its mass. Its nominal
  radial clearance is 0.03 mm; rubbing, airflow, and pressure buildup are neglected.
- Material properties are constant. Tilt, rubbing, air resistance, eddy-current
  inductance, induced-field feedback, and magnet recoil permeability are neglected.
- All objects stop without bouncing at stops inferred from the cap geometry.
- Both metal cutaways are visual only; the modeled walls remain electrically intact.
