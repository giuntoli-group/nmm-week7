# nmm-week7

Going up in scale, this week we look at macroscale mechanical properties of different materials from metals to polymer composites. Extracting such large-scale properties from MD simulations can be very tricky and requires care, but it can still be a very powerful approach! So have fun, and be mindful of the model simplifications.

## Assignment 1 - Back to Silicon

Welcoming back the familiar Silicon crystal at T=0K, let's keep ignoring electrons and calculate mechanical properties instead. Starting with the elastic constants, following the LAMMPS tutorial [ELASTIC](https://docs.lammps.org/Howto_elastic.html) 

At least in the athermal limit, it is straightforward to calculate the elastic constants of different materials based on the interatomic interactions. Let's do that first!

### Instructions

1a. FOLLOW LAMMPS EXAMPLE/ELASTIC https://docs.lammps.org/Howto_elastic.html, VARY POTENTIAL FOR DIFFERENT METALLIC (AND NON-METALLIC?) ELEMENTS.

1b. ALLOYS, OPTIMIZE SOMETHING

## Assignment 2

Let's go beyond the elastic limit and see how different materials are affected by large deformations. In this assignment you will look at the brittle behavior of metals and the ductile behavior of polymers.

### Instructions

2a. METALS, DISCLOCATION/BRITTLE

2b. POLYMERS, CRAZING/DUCTILE

## Assignment 3

Glassy polymer matrixes can be filled with all sorts of fillers to enhance mechanical properties or to introduce conductivity, self-healing, or other properties. Let's see their effect on the polymer matrix and on the overall material in terms of mechanical properties.

### Instructions

3a. bound layer analysis

3b. (Optional) repeat for varying epsilon
