## Description of Mission Analysis

Satellite orbital lifecycle assessment serves to inform the satellite mission preparation, operational cycle, and post-operational analysis. Determining orbit parameters in Low Earth Orbit (LEO) and examining orbital perturbation factors for the decay of the satellite orbit ensures a greater accuracy of the predicted orbit and lifespan of the satellite. The orbit analysis and determination ensures the accurate tracking of the satellite, confirmed by observational data upon deployment.

## Background

Satellite orbit factors of consideration:
* Gravitational effect between the satellite orbiting body and the primary body

* Orbit perturbations:
* Gravitation effects of the non-uniform mass distribution of the Earth
* Atmospheric air drag in LEO
* Solar radiation pressure emitted as delayed infrared radiation (IR)
* Solar radiation emitted by albedo reflected from the Earth

## Computational Methodologies

1. Encke’s formulation: Uses osculating orbit to integrate the difference between two-body acceleration and perturbed acceleration.
 
2. Cowell’s formulation: Uses perturbing acceleration factors for numerical integration using the equations of motion.
* Runge-Batta technique for the single-step method: Evaluates the system of equations at several intermediate steps similarly to fourth-order Taylor series.
* Adams-Bashforth-Moulton and Shampine-Gordon fourth-order method: Multi-step predictor-corrector methods.

3. General Perturbation Techniques: Uses analytical approximations of the satellite motion over a time interval with initial condition data.
* Variation of Parameters (VOP): Uses the generalized Lagrange planetary equations of motion for non-linear integral systems and changing orbital parameters in the two-body equations.
* Gaussian VOP: Shows the rate of change of the non-conservative forces expressed directly by the perturbing acceleration.


