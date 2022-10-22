# Awesome-FEM4CFD

This is a curated list of resources on Finite Element Methods (FEM) for Computational Fluid Dynamics (CFD) and Heat Transfer (HT).
The resources are categorised as follows:
- [Open source libraries](#open-source-libraries)
- [Textbooks](#textbooks)
- [Papers/Thesis/Reports](#papersthesisreports)

*If you know of any other resourses that belong in the list, then please open an issue or send a pull request*.

**Note 1:** For software repositories, there must be some considerable amount of material/tutorials on CFD to be included in the list.

**Note 2:** Discontinuous Galerkin (DG) method is relatively more complicated than the Continuous Galerkin (CG) method. So, if you are new to FEM, it is recommended that you learn the CG method first before learning the DG method.

# Open source libraries

### Opensource CFD simulation libraries
These can be used as blackbox simulation software. The user needs to prepare the input file (with mesh, BCs, properties etc.) and then execture the program.
* [NEKTAR++](https://www.nektar.info/)

* [Nek5000](https://github.com/Nek5000/Nek5000/)

* [Neko](https://github.com/ExtremeFLOW/neko/)

* [nekRS](https://github.com/Nek5000/nekRS)

* [PyFR](https://www.pyfr.org/)

* [SimVascular](https://simvascular.github.io/)

* [ElmerFEM](http://www.elmerfem.org/blog/)

* [FEATool](https://www.featool.com/)

* [KRATOS](https://kratosmultiphysics.github.io/Kratos/)

* [Fluidity](http://fluidityproject.github.io/)

* [HDGlab](https://git.lacan.upc.edu/hybridLab/HDGlab)     [Paper](https://arxiv.org/abs/2009.08805)

* [Lethe](https://lethe-cfd.github.io/lethe/index.html)

### Opensource core FEM libraries for CFD 
These libraries are not exactly like blackbox simulation software but they provide all the necessary ingredients for the FEM so that the users can develop their own solvers for solving Physics. Consider these libraries only if you know the basics (formulations) of FEM and have done some implementation of your own at least for 2D problems.
* [deal.ii](https://www.dealii.org/)

* [FreeFEM](https://freefem.org/)

* [MFEM](https://mfem.org/)

* [NGSolve](https://docu.ngsolve.org/latest/index.html)

* [GetFEM](https://getfem.org/)

* [FEniCS](https://fenicsproject.org/)

* [Gridap](https://gridap.github.io/Gridap.jl/stable/)

* [Dedalus Project](https://dedalus-project.org/)

# Textbooks
## Textbooks - non maths intensive
* [*Finite Element Methods for Flow Problems*](https://onlinelibrary.wiley.com/doi/book/10.1002/0470013826) Jean Donea and Antonio Huerta, Wiley

* [*The Finite Element Method for Fluid Dynamics*](https://www.sciencedirect.com/book/9781856176354/the-finite-element-method-for-fluid-dynamics) O C Zienkiewicz, R L Taylor and P Nithiarasu

* [*Computational Fluid Dynamics*](https://www.cambridge.org/core/books/computational-fluid-dynamics/5C396317EE111C5ED1192FA7F8853944) T J Chung, Cambridge University Press

* [*Finite Element Methods for Computational Fluid Dynamics: A Practical Guide*](https://epubs.siam.org/doi/book/10.1137/1.9781611973617) Dmitri Kuzmin and Jari Hämäläinen, SIAM

* [*Discontinuous Finite Elements in Fluid Dynamics and Heat Transfer*](https://link.springer.com/book/10.1007/1-84628-205-5), B Q Li, Springer

* [*Applied Computational Fluid Dynamics Techniques: An Introduction Based on Finite Element Methods*](https://www.wiley.com/en-us/Applied+Computational+Fluid+Dynamics+Techniques%3A+An+Introduction+Based+on+Finite+Element+Methods%2C+2nd+Edition-p-9780470519073) Rainard Lohner, Springer

* [*Finite Element Methods and Their Applications*](https://link.springer.com/book/10.1007/3-540-28078-2?gclid=CjwKCAjwkaSaBhA4EiwALBgQaAeVix769JTifRwX5UfkxyR2lzyo1AkKy9Vhy3XSPLpGP5hWQpa_vhoCgPYQAvD_BwE) Zhangxin Chen, Springer

* [*Spectral/hp Element Methods for Computational Fluid Dynamics*](https://academic.oup.com/book/7538) George EM Karniadakis and Spencer Sherwin, Oxford Science Publications

* [*The Finite Element Method in Heat Transfer and Fluid Dynamics*](http://ftp.demec.ufpr.br/disciplinas/TM144/Aulas-e-mat-apoio/3rd-Edition-J.N-Reddy-The%20finite%20element%20method%20in%20heat%20transfer%20and%20fluid%20dynamics.pdf) J N Reddy and D K Gartling, CRC Press




## Textbooks - maths intensive
Only consider these books if you want to know the rigorous mathematics behind FEM.
* [*Finite Elements and Fast Iterative Solvers*](https://academic.oup.com/book/27915) Howard Elman, David Silvester and Andy Wathen, Oxford University Press

* [*Finite Element Methods for Incompressible Flow Problems*](https://link.springer.com/book/10.1007/978-3-319-45750-5) Volker John, Springer

* [*Finite Element Methods for Navier-Stokes Equations: Theory and Algorithms*](https://link.springer.com/book/10.1007/978-3-642-61623-5) Vivette Girault and Pierre-Arnaud Raviart

* [*Finite Element Methods for Incompressible Viscous Flow*](https://www.sciencedirect.com/science/article/abs/pii/S1570865903090033) Roland Glowinski

* [*Numerical Solution of the Incompressible Navier-Stokes Equations*](https://link.springer.com/book/10.1007/978-3-0348-8579-9) L. Quartapelle, Springer Basel AG

* [*Projection and Quasi-Compressibility Methods for Solving the Incompressible Navier-Stokes Equations*](https://link.springer.com/book/10.1007/978-3-663-11171-9) Andreas Prohl, Springer Fachmedien Wiesbaden GmbH

* [*Finite Element Methods in Incompressible, Adiabatic and Compressible Flows: From Fundamental Concepts to Applications*](https://link.springer.com/book/10.1007/978-4-431-55450-9) Mutsuto Kawahara, Springer

* [*Numerical Analysis and Optimisation*](https://global.oup.com/academic/product/numerical-analysis-and-optimization-9780199205226?cc=us&lang=en&) Gregoire Allaire, OUP Oxford

* [*Discontinuous Galerkin methods: theory, computation and applications*](https://link.springer.com/book/10.1007/978-3-642-59721-3) B Cockburn, GE Karniadakis, CW Shu, Springer

# Papers/Thesis/Reports
## Continuous Galerkin

### Projection or Fractional-Step methods

* [*The Characteristic-Based Split (CBS) Algorithm: A General Procedure for Compressible and Incompressible Flow*](https://www.sciencedirect.com/science/article/pii/B9781856176354000030?via%3Dihub) O C Zienkiewicz, R L Taylor and P Nithiarasu


* [*A fractional-step method for the incompressible Navier–Stokes equations related to a predictor–multicorrector algorithm*](https://core.ac.uk/download/pdf/296524171.pdf) J Blasco, R Codina and A Huerta

* [*A new family of projection schemes for the incompressible Navier-Stokes equations with control of high-frequency damping*](https://www.sciencedirect.com/science/article/pii/S0045782518302494?via%3Dihub) A Lovrić, W G Dettmer, C Kadapa and D Perić

* [*Algebraic pressure segregation methods for the incompressible Navier-Stokes equations*](https://link.springer.com/article/10.1007/BF03024946) S Badia and R Codina



### Stabilised methods

* [*Stabilized Finite Elements in FUN3D*](https://ntrs.nasa.gov/api/citations/20170001235/downloads/20170001235.pdf)  W. Kyle Anderson, James C. Newman, and Steve L. Karman

* [*Streamline upwind/Petrov-Galerkin formulations for convection dominated flows with particular emphasis on the incompressible Navier-Stokes equations*](https://doi.org/10.1016/0045-7825(82)90071-8) N A Brooks and T J R Hughes

* [*Stabilized finite element methods: II. The incompressible Navier-Stokes equations*](https://www.sciencedirect.com/science/article/pii/004578259290041H) L P Franca and S L Frey

* [*Stabilized finite element formulations for incompressible flow computations*](https://www.sciencedirect.com/science/article/abs/pii/S0065215608701534) T E Tezduyar

* [*Incompressible flow computations with stabilized bilinear and linear equal-order-interpolation velocity-pressure elements*](https://www.sciencedirect.com/science/article/pii/0045782592901416) T E Tezduyar, S Mittal, S E Ray and R Shih


* [*The Variational Multiscale Method for Laminar and Turbulent Incompressible Flow*](https://d-nb.info/970314418/34) V Gravemeier


### Time integration schemes

* [*A generalized-α method for integrating the filtered Navier–Stokes equations with a stabilized finite element method*](https://www.sciencedirect.com/science/article/pii/S0045782500002036) K E Jansen, C H Whitinga and G M Hulbert

* [*Accurate iteration-free mixed-stabilised formulation for laminar incompressible Navier-Stokes: Applications to fluid–structure interaction*](https://www.sciencedirect.com/science/article/pii/S0889974619309612) C Kadapa, W G Dettmer and D Peric



## Discontinuous Galerkin

* [*A discontinuous Galerkin method for the Navier–Stokes equations*](https://onlinelibrary.wiley.com/doi/abs/10.1002/%28SICI%291097-0363%2819990315%2929%3A5%3C587%3A%3AAID-FLD805%3E3.0.CO%3B2-K) I Lomtev and G E Karniadakis

* [*Hybridisable Discontinuous Galerkin Formulation of Compressible Flows*](https://link.springer.com/article/10.1007/s11831-020-09508-z) J Vila-Pérez, M Giacomini, R Sevilla and A Huerta


* [*To CG or to HDG: A Comparative Study*](https://link.springer.com/article/10.1007/s10915-011-9501-7) R M Kirby, S J Sherwin and B Cockburn 
