# VS2DT Version 3.3

[![vs2dt compiler checks](https://github.com/MODFLOW-ORG/vs2dt/actions/workflows/cicd.yml/badge.svg)](https://github.com/MODFLOW-ORG/vs2dt/actions/workflows/cicd.yml)

## Overview of VS2DT

Computer program VS2DT solves problems of water and solute movement
in variably saturated porous media.  The finite difference method is
used to approximate the flow equation, which is developed by
combining the law of conservation of fluid mass with a nonlinear
form of Darcy's equation, and the advection-dispersion equation.
The model can analyze problems in one and two dimensions with planar
or cylindrical geometries.  There are several options for using
boundary conditions that are specific to flow under unsaturated
conditions: infiltration with ponding, evaporation, plant
transpiration, and seepage faces.  Solute transport options include
first-order decay, adsorption, and ion exchange.  The program is
written in standard Fortran 77.  Extensive use of subroutines and
functions subprograms provides a modular code that can be easily
modified for particular applications.

## How to Cite VS2DT

### Report Citations

Healy, R.W., and Ronan, A.D., 1996, Documentation of computer program VS2DH for simulation of energy transport in variably saturated porous media -- modification of the U.S. Geological Survey's computer program VS2DT: U.S. Geological Survey Water-Resources Investigations Report 96-4230, 36 p., https://doi.org/10.3133/wri964230

Healy, R.W., 1990, Simulation of solute transport in variably saturated porous media with supplemental information on modifications to the U.S. Geological Survey's Computer Program VS2D: U.S. Geological Survey Water-Resources Investigations Report 90-4025, 125 p., https://doi.org/10.3133/wri904025

Lappala, E.G., Healy, R.W., and Weeks, E.P., 1987, Documentation of computer program VS2D to solve the equations of fluid flow in variably saturated porous media: U.S. Geological Survey Water-Resources Investigations Report 83-4099, 184 p., [https://doi.org/10.3133/WRI834099](https://doi.org/10.3133/WRI834099) (https://pubs.usgs.gov/publication/wri834099)

### Disclaimer

This software is preliminary or provisional and is subject to revision. It is being provided to meet the need for timely best science. The software has not received final approval by the U.S. Geological Survey (USGS). No warranty, expressed or implied, is made by the USGS or the U.S. Government as to the functionality of the software and related material nor shall the fact of release constitute any such warranty. The software is provided on the condition that neither the USGS nor the U.S. Government shall be held liable for any damages resulting from the authorized or unauthorized use of the software.