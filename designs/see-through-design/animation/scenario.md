# See-through simulation parameters and assumptions

The animation compares a ring magnet falling around the outside of a copper
tube with a matching nonmagnetic control ring. Both paths have identical copper
tubes and clear outer sleeves. The rings are released simultaneously from rest
and travel the same distance between stops.

## Simulation parameters

| Parameter | Value |
|---|---|
| Travel of each ring's center | 274.375 mm (10.802″) |
| Copper and clear tube lengths | 304.8 mm (12″) |
| Copper outside × inside diameter | 12.00 × 10.00 mm (0.472″ × 0.394″) |
| Copper wall thickness | 1.00 mm (0.039″) |
| Copper conductivity | 49.3 MS/m |
| Clear sleeve outside × inside diameter | 25.4 × 22.098 mm (1″ × 0.870″) |
| Magnet and control outside diameter × inside diameter × height | 19.05 × 12.70 × 9.525 mm (¾″ × ½″ × ⅜″) |
| Magnet density | 7850 kg/m³ |
| Magnet mass, from ring volume and density | 11.840 g |
| Magnet nominal remanence | 1.18 T |
| Stop contact plane inside each tube end | 10.45 mm (0.411″) |
| Gravity | 9.80665 m/s² |
| Initial velocity, both rings | 0 m/s |

The metric dimensions are the simulation inputs; inch equivalents are rounded.

## Predicted timing and presentation

Predicted arrival times after release are **1.004343 s** for the magnet and
**0.236552 s** for the control. These are numerical predictions using the
specified geometry and nominal material properties.

The animation is presented at 60 fps and 1440 × 900 pixels, with real-time
motion, a quarter-speed replay of the same trajectories, and a three-second
closing hold. Landing sounds mark each arrival; they are illustrative cues,
not simulated impact acoustics.

## Basic assumptions

- Both rings remain centered in upright tubes. Copper and clear tube ends
  are aligned, and the tubes remain fixed.
- The magnet is uniformly magnetized along its axis. Braking adapts the
  [Derby–Olbert reproduction](https://github.com/jsxliu/derby-olbert-2010)
  to the ring by subtracting the inner cylinder's field from the outer
  cylinder's field. The quasistatic calculation integrates over the finite
  copper length and through the full wall thickness.
- The control has the magnet's ring geometry and follows ideal free fall,
  independent of its mass. Airflow and pressure buildup are neglected.
- Material properties are constant. Rubbing, tilt, air resistance, eddy-current
  inductance, induced-field feedback, and magnet recoil permeability are neglected.
- Both rings stop without bouncing at stops inferred from the cap geometry.
  Actual assembled stop positions may differ.
