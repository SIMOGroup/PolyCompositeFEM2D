# Introduction
We provided a Matlab-based polygonal composite finite elements for 2D solids. 
A computational approach based on arbitrary polygons and a polynomial projection of compatible strain fields through the least-squares approximation. 
For nearly incompressible problems, a pair of projection operators of volumetric and deviatoric strains was established. 
The present formulation satisfies the inf–sup stability and improved the accuracy of solutions.
Matlab codes may be extensively developed for a wide range of engineering problems.

Structure of PolyCompositeFEM2D package: 
1. PCEn_CantileverBeam & PCEn_CylinderHollowPlate & PCEn_CooksMembrane: main programs for running 2D solids. 
2. Other functions are given in subfolders. 
3. How to run PolyCompositeFEM2D 
  - Define a new problem following code structures 
  - Run PCEn_....m 
  - Use Paraview to show results in displacements and stresses. 
  - Get output

# Contributors
- Hung Nguyen-Xuan
- Khanh N. Chau
- Khai N. Chau

# References
H. Nguyen-Xuan, Khanh N. Chau, Khai N. Chau, Polytopal composite finite elements, Computer Methods in Applied Mechanics and Engineering, 355, 405-437, 2019 https://doi.org/10.1016/j.cma.2019.06.030.
