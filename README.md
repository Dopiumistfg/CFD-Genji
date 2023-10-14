# CFD-Genji
A 3-d Incompressible fluid flow simulation of Genji, A popular character from the game Overwatch

[Video Demonstration](case/output.gif)

# How it works
To run this you will need

## OpenFOAM: Opensource CFD software available on linux and WSL. ([Link](https://www.openfoam.com))

## ParaView: Software to visualise the simulation as well as extract data. ([Link](https://www.paraview.org))

This simulation is an example of an incompressible heat transfer where the inlet is to the left with a constant velocity and the other walls function on a no slip condition

# How to run it

On downloading this file and all prerequisistes, ([See OpenFOAM prerequisites](https://www.openfoam.com/documentation/system-requirements)), you can open the case folder in a terminal window and run the following commands:

```
  openfoam2306 (or your openfoam version)
  blockMesh
  snappyHexMesh -overwrite
  checkMesh
  icoFoam
  paraFoam
```
