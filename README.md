# Stacked-Dielectric-Tubular-Actuator

## Scope
Develop an methodlogy to determine the onset of stacked tubes's instability. This project involves solving loads of system of algebraic equations and differential equations using python and mathematica. 

## Method
* A systematic study on prismatic bifurcation of stacked dielectric cylinders is performed under coupled mechanical and electrical loading conditions. The system consists of two stacked cylindrical layers, each modeled as a homogeneous, isotropic dielectric solid.

The cylinders are subjected to:
* Uniform internal pressure applied on the inner surface of the inner cylinder
* Electric loading across the thickness of the cylinder

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
