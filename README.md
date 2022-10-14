# Awesome-FEM4CFD

This is a curated list of resources on Finite Element Methods (FEM) for Computational Fluid Dynamics (CFD) and Heat Transfer (HT).

*If you know of any other resourses that belong in the list, then please open an issue or send a pull request*.

**Note:** For software repositories, there must be some considerable amount of material/tutorials on CFD to be included in the list.


## Opensource CFD simulation libraries
These can be used as blackbox simulation software. The user needs to prepare the input file (with mesh, BCs, properties etc.) and then execture the program.
* [NEKTAR++](https://www.nektar.info/)
* [PyFR](https://www.pyfr.org/)
* [SimVascular](https://simvascular.github.io/)
* [ElmerFEM](http://www.elmerfem.org/blog/)
* [FEATool](https://www.featool.com/)
* [KRATOS](https://kratosmultiphysics.github.io/Kratos/)
* [Fluidity](http://fluidityproject.github.io/)
* [HDGlab](https://git.lacan.upc.edu/hybridLab/HDGlab)     [Paper](https://arxiv.org/abs/2009.08805)

## Opensource core FEM libraries for CFD
These libraries are not exactly like blackbox simulation software but they provide all the necessary ingredients for the FEM so that the users can develop their own solvers for solving Physics. Consider these libraries only if you know the basics (formulations) of FEM and have done some implementation of your own at least for 2D problems.
* [deal.ii](https://www.dealii.org/)
* [FreeFEM](https://freefem.org/)
* [MFEM](https://mfem.org/)
* [NGSolve](https://docu.ngsolve.org/latest/index.html)
* [GetFEM](https://getfem.org/)
* [FEniCS](https://fenicsproject.org/)
* [Gridap](https://gridap.github.io/Gridap.jl/stable/)



## Textbooks - non maths intensive
* **Finite Element Methods for Flow Problems** Jean Donea and Antonio Huerta, Wiley
* **The Finite Element Method for Fluid Dynamics** O C Zienkiewicz, R L Taylor and P Nithiarasu
* **Computational Fluid Dynamics** T J Chung, Cambridge University Press
* **Finite Element Methods for Computational Fluid Dynamics: A Practical Guide** Dmitri Kuzmin and Jari Hämäläinen, SIAM
* **Discontinuous Finite Elements in Fluid Dynamics and Heat Transfer**, B Q Li, Springer
* **Applied Computational Fluid Dynamics Techniques: An Introduction Based on Finite Element Methods** Rainard Lohner, Springer
* **Finite Element Methods and Their Applications** Zhangxin Chen, Springer
* **Incompressible Flow and the Finite Element Method, Volume 1: Advection-Diffusion and Isothermal Laminar Flow** P M Gresho and R L Sani, Wiley
* **Incompressible Flow and the Finite Element Method, Volume 2: Isothermal Laminar Flow** P M Gresho and R L Sani, Wiley
* **Spectral/hp Element Methods for Computational Fluid Dynamics** George EM Karniadakis and Spencer Sherwin, Oxford Science Publications
* **The Finite Element Method in Heat Transfer and Fluid Dynamics** J N Reddy and D K Gartling, CRC Press




## Textbooks - maths intensive
Only consider these books if you want to know the rigorous mathematics behind FEM.
* **Finite Elements and Fast Iterative Solvers** Howard Elman, David Silvester and Andy Wathen, Oxford University Press
* **Finite Element Methods for Incompressible Flow Problems** Volker John, Springer
* **Finite Element Methods for Navier-Stokes Equations: Theory and Algorithms** Vivette Girault and Pierre-Arnaud Raviart
* **Finite Element Methods for Incompressible Viscous Flow** Roland Glowinski
* **Numerical Solution of the Incompressible Navier-Stokes Equations** L. Quartapelle, Springer Basel AG
* **Projection and Quasi-Compressibility Methods for Solving the Incompressible Navier-Stokes Equations** Andreas Prohl, Springer Fachmedien Wiesbaden GmbH
* **Finite Element Methods in Incompressible, Adiabatic and Compressible Flows: From Fundamental Concepts to Applications** Mutsuto Kawahara, Springer



## Papers/Thesis/Reports - Continuous Galerkin

* **Stabilized Finite Elements in FUN3D**  W. Kyle Anderson, James C. Newman, and Steve L. Karman 
[Link](https://ntrs.nasa.gov/api/citations/20170001235/downloads/20170001235.pdf)


## Papers/Thesis/Reports - Discontinuous Galerkin

