# nmm-week7

Going up in scale, this week we look at macroscale mechanical properties of different materials from metals to polymer composites. Extracting such large-scale properties from MD simulations can be very tricky and requires care, but it can still be a very powerful approach! So have fun, and be mindful of the model simplifications.

## Assignment 1

At least in the athermal limit, it is straightforward to calculate the elastic constants of different materials based on the interatomic interactions. Let's do that first!

### Instructions

1a. FOLLOW LAMMPS EXAMPLE/ELASTIC https://docs.lammps.org/Howto_elastic.html, VARY POTENTIAL FOR DIFFERENT METALLIC (AND NON-METALLIC?) ELEMENTS.

1b. ALLOYS, OPTIMIZE SOMETHING

## Assignment 2

Let's go beyond the elastic limit and how different materials are affected by large deformations.

### Instructions

2a. METALS, DISCLOCATION/BRITTLE

2b. POLYMERS, CRAZING/DUCTILE

## Assignment 3

Deformation of complex polymeric melts is also fun! And at the base of 3D-printing. In this assignment, you will simulate the key mechanism behind the shear thinning of polymer melts.

### Instructions

3a. FIX MOLECULAR WEIGHT (10-20? TO TEST). RUN AT VARYING SHEAR RATE, MEASURE VISCOSITY(SHEAR RATE) AND FIND THE CRITICAL SHEAR RATE FOR NON-NEWTONIAN BEHAVIOR. COMPARE TO POLYMER RELAXATION TIME AT EQUILIBRIUM. STUDY CHAIN ALIGNMENT DURING SHEAR RATE.

3b. FANCIER POLYMER INTERACTIONS/FILLERS FOR 3D-PRINTING FOR SHEAR-INDUCED CRYSTALLIZATION OR OTHER FUN THINGS?

## Assignment 4

Glassy polymer matrixes can be filled with all sorts of fillers to enhance mechanical properties or to introduce conductivity, self-healing, or other properties. Let's see their effect on the polymer matrix and on the overall material in terms of mechanical properties.

### Instructions

4a. POLYMER MATRIX WITH VARYING FILLERS https://doi.org/10.1016/j.polymer.2019.122103. TEST MOBILITY AT THE INTERFACE, OVERALL MOBILITY BASED ON CONCENTRATION, THEN SHEAR RATE AND STRESS CURVES. CHECK HOW THE POLYMER-FILLER INTERFACES CHANGE UNDER DEFORMATION.

4b. THE EFFECT IS PROPORTIONAL TO FILLER SURFACE, NOT VOLUME. PROVE IT BY FIXING FILLER VOLUME (WITH SPHERES), BUT CHANGE SURFACE. SCALE G WITH SURFACE AND VOLUME. TO TEST!!
