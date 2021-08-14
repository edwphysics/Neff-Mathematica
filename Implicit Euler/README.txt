NEUTRINO DECOUPLING SOLVER - MATHEMATICA - IMPLICIT EULER METHOD

The NIDBasicModules.nb (NIDQEDBasicModules.nb) contains the constants, parameters and the definition of the functions and derivatives for the NID (NID+QED) case. 

The files with extension .m are packages created by the Basic Modules notebooks automatically and used by the numerical methods codes.

The notebook ImplicitEuler.nb contains the implemented Euler method to the neutrinos decoupling solution. If there is a crash, the BackUp.nb notebook runs the code Euler.nb starting where it failed.

The folder QED contains the program that solves the continuity equation considering the QED corrections alone (QED) with the differential equations numerical method.

To run the program just do
1. Open ImplicitEuler.nb
2. Run the Notebook
3. Allow to run the initialization cells
4. Run the Results.nb notebook to obtain the results
