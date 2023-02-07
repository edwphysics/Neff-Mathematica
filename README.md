# Neff-Mathematica
Calculation of the effective number of neutrino species Neff within the Standard Model of particle physics and the Hot Big-Bang Model, using Mathematica. It uses three differential equation numerical methods: Euler, Implicit Euler and fourth-order Runge-Kutta to evolve the system in time. 

The collision integrals are solvel with the discretization of momentum method. It solves numerically four systems of equations for different physical phenomena: 
1. Instantaneous Decoupling Limit (ID) 
2. ID + FTQED corrections (QED)
3. Non-instantaneous decoupling (NID)
4. NID+QED

Compared to the others, the ID case is solved using the scheme NDSolve instead of the mentioned numerical methods for differential equations.
The folders refer to each of the numerical methods used to solve the QED, NID and NID+QED systems. The notebook ID.nb shows the instantaneous decoupling limit solution.

You can find the complete report and the slides of the defense presentation (in Spanish) of the project at https://edwinperez.super.site/neffmathematica
