# Introduction
We provided a Matlab-based polygonal composite finite elements for 2D solids. 
A computational approach based on arbitrary polygons and a polynomial projection of compatible strain fields through the least-squares approximation. 
For nearly incompressible problems, a pair of projection operators of volumetric and deviatoric strains was established. 
The present formulation satisfies the inf–sup stability and improved the accuracy of solutions.
Matlab codes may be extensively developed for a wide range of engineering problems.

Structure of PolyCompositeFEM2D package: 
1. PCEn_CantileverBeam & PCEn_CylinderHollowPlate & PCEn_CooksMembrane: main functions for running 2D solids. 
2. Other functions are given in subfolders. How to run PolyCompositeFEM2D: You need to define input of new problem following code structures. 
3. Run main....m and then use Paraview to show results in displacements and stresses. 
4. Get output
