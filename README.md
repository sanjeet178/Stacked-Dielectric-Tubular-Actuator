# Stacked-Dielectric-Tubular-Actuator

## Scope
Develop an methodlogy to determine the onset of stacked tubes's instability. This project involves solving loads of system of algebraic equations and differential equations using python and mathematica. 

## Method
* A systematic study on prismatic bifurcation of stacked dielectric cylinders is performed under coupled mechanical and electrical loading conditions. The system consists of two stacked cylindrical layers, each modeled as a homogeneous, isotropic dielectric solid.
  
<img width="433" height="236" alt="image" src="https://github.com/user-attachments/assets/23810f5a-80a2-42f4-bf7b-25dc514f123d" />

The cylinders are subjected to:
* Uniform internal pressure applied on the inner surface of the inner cylinder
* Electric loading across the thickness of the cylinder
  
<img width="475" height="526" alt="image" src="https://github.com/user-attachments/assets/82dcc321-cda6-4014-bcfa-e649c2c006a6" />

Two axial constraints are considered:
* Axially free cylinders
* Axially stretched cylinders

## Material and Constitutive Modeling
* Both cylinders are assumed to have identical material properties
* The material behavior is described using a isotropic and homogenous neo-Hookean electro-elastic model
* Large deformations and nonlinear electromechanical coupling are accounted for

## Stability and Bifurcation Analysis
* The equilibrium configuration of the stacked cylinders is first computed
* Linearized incremental equations are derived about the equilibrium state
* These equations lead to a system of coupled first-order linear differential equations
* The onset of prismatic diffuse modes is determined by solving the incremental boundary value problem

## Key Findings
* Electrical actuation applied to different cylinders in the stack produces distinct prismatic bifurcation patterns, even for identical geometries
* Stacked cylinders can enter diffuse instability states before the Hessian-based stability criterion fails
* Higher total thickness of stacked cylinders requires higher critical voltage to trigger prismatic bifurcation
* The effect of internal pressure on the critical voltage is negligible
* For axially free tubes at higher pressurization, the system undergoes a snap-through transition instead of prismatic bifurcation

## References
* Patra, S., & Roychowdhury, S. (2025). Prismatic bifurcation of electro-mechanically loaded stacked di-electric cylinders. International Journal of Non-Linear Mechanics, 175, 105119. https://doi.org/10.1016/j.ijnonlinmec.2025.105119
