# nmm-week7

Going up in scale, this week we look at macroscale mechanical properties of different materials from metals to polymer composites. Extracting such large-scale properties from MD simulations can be very tricky and requires care, but it can still be a very powerful approach! So have fun, and be mindful of the model simplifications.

## Assignment 1 - Back to Silicon

Welcoming back the familiar Silicon crystal at T=0K, let's keep ignoring electrons and calculate mechanical properties instead. Starting with the elastic constants, following the LAMMPS tutorial [ELASTIC](https://docs.lammps.org/Howto_elastic.html) and a [little piece of history](https://abrams-teaching.github.io/msim/node41.html).

### Instructions

1a. The simulation in.elastic will run almost instantaneously, but relies on several scripts contained in the folder ELASTIC provided. Describe the workflow of the simulation used to obtain the elastic constants of Silicon, and then report the values obtained after running the simulation.

1b. To show the enthalpic nature of elasticity, artificially vary the interaction strength epsilon in the force field file and plot how the elastic modulus of the material changes with changing interaction strength.

1c (OPTIONAL). There is more to the periodic table than Silicon, and many interatomic potentials have been devised since 1985 to predict the mechanical properties of solid materials! Feel free to explore the [NIST repository](https://www.ctcms.nist.gov/potentials/) and update your script/force field to calculate the elastic constants of other elements or alloys. The Stillinger-Weber potential for Silicon you just used is also [there](https://www.ctcms.nist.gov/potentials/entry/1985--Stillinger-F-H-Weber-T-A--Si/).

## Assignment 2 - Not Everything is a Spring

Let's go beyond the elastic limit and see how different materials are affected by large deformations. In this assignment, you will look at the brittle behavior of atomic crystals and the ductile behavior of polymers.

### Instructions

2a. Run the in.crack script that performs a 3D notch fracture simulation of crystalline Silicon. 

(i) How is the notch deformation protocol implemented within the script? 

(ii) Looking at Ovito, run the simulation multiple times to discuss how the fracture behavior is affected by the pulling speed.

Hint: for lower pulling speeds, remember to increase the simulation length to ensure that the fracture event is completed.

2b. Now uniaxial deformation and crazing of polymer films! 

(i) Open the three data files film1.data, film2.data, film3.data. How do they differ?

(ii) Run the simulation in.deformFilm three times, using separately the three film_i.data files as the starting configuration. Compare and discuss the mechanical behavior of the three films, observing the simulation in Ovito and the stress curves produced by the script. 

Hint: the simulation is not super long (~30min or less), but it is large. Plan the requested resources accordingly.

## Assignment 3 - Bound to Succeed

The reinforcement of polymer nanocomposites often comes from the modified behavior of the polymer matrix itself at the surface of the fillers, the so-called bound layer. Let's see this in action.

### Instructions

3a. bound layer analysis

3b. (Optional) repeat for varying epsilon
