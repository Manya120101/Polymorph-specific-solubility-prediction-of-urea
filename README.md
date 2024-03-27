# Polymorph-specific-solubility-prediction-of-urea
The following input files are present in this repository:
1. minimisation of system---> minimisation.mdp
2. NVT equilibrate ---> nvt.mdp
3. NPT equilibrate ---> npt_equilibrate.mdp
4. NPT production run ---> npt_production_run.mdp

For implementing Constant chemical potential during the simulations, input files compatible with plumed were made. They have been included in this repo for all the three polymorphs.
Plumed file pertaining to a given concentration for a polymorph can be found with the name: 'polymorph(#polymorph no.#)_target(#number density in contro region#)_plumed.dat

   
