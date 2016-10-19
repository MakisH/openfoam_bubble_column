# Simulation of a bubble column in OpenFOAM

Final project for the course "Simulation of thermo-fluid dynamics with open
source means" (summer semester 2016), Technische Universität München.

Authors: Gerasimos Chourdakis, Vasileios Magioglou.

Repository: https://github.com/MakisH/openfoam_bubble_column

*OpenFOAM v.2.0.1 with groovyBC is required.*

The following cases are included:

1. column_bubbleFoam_da3_Ua02
   Main case, full-size column (0.5m, 200 cells per z),
   3mm bubbles, 0.2m/s air velocity at the inlet.
   Solver: bubbleFoam.

2. column_bubbleFoam_da1_Ua02
   Variation of the main case with 1mm bubbles.

3. column_bubbleFoam_da9_Ua02
   Variation of the main case with 9mm bubbles.

4. column_bubbleFoam_da3_Ua007
   Variation of the main case with 0.07m/s inlet velocity.

5. column_bubbleFoam_da3_Ua06
   Variation of the main case with 0.6m/s inlet velocity.

6. column_bubbleFoam_da3_Ua02_obstacle
   Spherical obstacle case, shorter column (0.2m, 80 cells per z),
   3mm bubbles, 0.2m/s air velocity at the inlet.
   Solver: bubbleFoam.

7. short_bubbleFoam_da3_Ua02
   Very short column/tank (0.05m, 20 cells per z),
   3mm bubbles, 0.2m/s air velocity at the inlet.
   Solver: bubbleFoam.

8. short_twoPhaseEulerFoam_da3_Ua02
   Very short column/tank (0.05m, 20 cells per z),
   3mm bubbles, 0.2m/s air velocity at the inlet.
   Solver: twoPhaseEulerFoam.
