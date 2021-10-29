# Awesome Physics Based Animation 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)

> A collection of papers about physically  based animation for deformable bodies

## Contents

- [Optimization](#optimization)
- [Character Simulation](#character-simulation)
- [Subspace](#subspace)
- [Domain-Specific Language](#domain-specific-language)
- [Courses](#courses)
- [Others](#others)


## Optimization

A list of papers about time integrations as an optimization problem (Newton methods, Quasi-Newton, Coordinate descent ...).

**Stabilizing Integrators for Real-Time Physics.**<br>
*Dinev, Dimitar, Tiantian Liu, and Ladislav Kavan.*<br>
2018. [[PDF](https://www.cs.utah.edu/~ladislav/dinev18stabilizing/dinev18stabilizing.pdf)]

**Quasi-Newton Methods for Real-Time Simulation of Hyperelastic Materials.**<br>
*Liu, Tiantian, Sofien Bouaziz, and Ladislav Kavan.*<br>
2017. [[PDF](https://www.cs.utah.edu/~ladislav/liu17towards/liu17towards.pdf)]

**ADMM ⊇ Projective Dynamics: Fast Simulation of General Constitutive Models.**<br>
*Narain, Rahul, Matthew Overby, and George E. Brown.*<br>
2016. [[PDF](https://www-users.cse.umn.edu/~narain/files/admm-pd.pdf)]

**Towards Real-time Simulation of Hyperelastic Materials.**<br>
*Liu, Tiantian, Sofien Bouaziz, and Ladislav Kavan.*<br>
2016. [[PDF](https://arxiv.org/pdf/1604.07378.pdf)]

**Descent Methods for Elastic Body Simulation on the GPU.**<br>
*Wang, Huamin, and Yin Yang.*<br>
2016. [[PDF](https://web.cse.ohio-state.edu/~wang.3602/Wang-2016-DME/Wang-2016-DME.pdf)]

**Optimization Integrator for Large Time Steps.**<br>
*Gast, Theodore F., Craig Schroeder, Alexey Stomakhin, Chenfanfu Jiang, and Joseph M.*<br>
2015. [[PDF](https://www.math.ucla.edu/~jteran/papers/GSSJT15.pdf)]

**Projective Dynamics: Fusing Constraint Projections for Fast Simulation.**<br>
*Bouaziz, Sofien, Sebastian Martin, Tiantian Liu, Ladislav Kavan, and Mark Pauly.*<br>
2014. [[PDF](https://www.cs.utah.edu/~ladislav/bouaziz14projective/bouaziz14projective.pdf)]

**Fast Simulation of Mass-Spring Systems.**<br>
*Liu, Tiantian, Adam W. Bargteil, James F. O'Brien, and Ladislav Kavan.*<br>
2013. [[PDF](http://graphics.berkeley.edu/papers/Liu-FSM-2013-11/Liu-FSM-2013-11.pdf)]

**Example-Based Elastic Materials.**<br>
*Martin, Sebastian, Bernhard Thomaszewski, Eitan Grinspun, and Markus Gross.*<br>
SIGGRAPH 2011. [[PDF](https://graphics.ethz.ch/Downloads/Publications/Papers/2011/Mar11/Mar11.pdf)]


## Character Simulation

**DiffCloth: Differentiable Cloth Simulation with Dry.**<br>
*Li, Yifei, Tao Du, Kui Wu, Jie Xu, and Wojciech Matusik.*<br>
2021. [[PDF](https://arxiv.org/pdf/2106.05306.pdf)]

**A Finite Element Formulation of Baraff-Witkin Cloth.**<br>
*Kim, Theodore.*<br>
2020. [[PDF](http://www.tkim.graphics/FEMBW/tkim_sca2020.pdf)]

**Stable Neo-Hookean Flesh Simulation.**<br>
*Smith, Breannan, Fernando De Goes, and Theodore Kim.*<br>
2018. [[PDF](https://graphics.pixar.com/library/StableElasticity/paper.pdf)]

**Enriching Facial Blendshape Rigs with Physical Simulation.**<br>
*Kozlov, Yeara, Derek Bradley, Moritz Bächer, Bernhard Thomaszewski, Thabo Beeler, and Markus Gross.*<br>
2017. [[PDF](http://disneyresearch.s3.amazonaws.com/wp-content/uploads/20170425165601/Enriching-Facial-Blendshape-Rigs-with-Physical-Simulation-Paper2.pdf)]

**BlendForces A Dynamic Framework for Facial Animation.**<br>
*Barrielle, Vincent, Nicolas Stoiber, and Cédric Cagniart.*<br>
2016. [[Website](https://www.researchgate.net/publication/303597948_BlendForces_A_Dynamic_Framework_for_Facial_Animation)]

**Rig-Space Physics.**<br>
*Hahn, Fabian, Sebastian Martin, Bernhard Thomaszewski, Robert Sumner, Stelian Coros, and Markus Gross.*<br>
2012. [[PDF](http://crl.ethz.ch/papers/RigSpacePhysics.pdf)]

**A Simple Approach to Nonlinear Tensile Stiffness for Accurate Cloth Simulation.**<br>
*Volino, Pascal, Nadia Magnenat-Thalmann, and Francois Faure.*<br>
2009. [[PDF](https://hal.inria.fr/inria-00394466/document)]

**Fast and Stable Animation of Cloth with an Approximated Implicit Method.**<br>
*Kang, Young-Min, Jeong-Hyeon Choi, Hwan-Gue Cho, and Chan-Jong Park.*<br>
2000. [[PDF](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.81.6949&rep=rep1&type=pdf)]

**Large Steps in Cloth Simulation.**<br>
*Baraff, David, and Andrew Witkin.*<br>
SIGGRAPH 98. [[PDF](https://www.cs.cmu.edu/~baraff/papers/sig98.pdf)]

## Subspace

**Pose-Space Subspace Dynamics.**<br>
*Xu, Hongyi, and Jernej Barbič.*<br>
SIGGRAPH 2016. [[PDF](http://barbic.usc.edu/multiModal/XuBarbic-SIGGRAPH2016.pdf)]

**Efficient Simulation of Secondary Motion in Rig-Space.**<br>
*Hahn, Fabian, Bernhard Thomaszewski, Stelian Coros, Robert W. Sumner, and Markus Gross.*<br>
2013. [[PDF](https://studios.disneyresearch.com/wp-content/uploads/2019/03/Efficient-Simulation-of-Secondary-Motion-in-Rig-Space.pdf)]

**Subspace Self-Collision Culling.**<br>
*Barbič, Jernej, and Doug L. James.*<br>
SIGGRAPH 2010. [[PDF](http://barbic.usc.edu/selfCD/BarbicJames-SIGGRAPH2010.pdf)]

**Hyper-Reduced Projective Dynamics.**<br>
*Brandt, Christopher, Elmar Eisemann, and Klaus Hildebrandt.*<br>
2018. [[PDF](https://graphics.tudelft.nl/~klaus/papers/hrpd.pdf)]


## Domain-Specific Language

Domain-specific language (DSL) simplify the development help to separate the data structures from the algorithms allowing to run on different platforms without changing code.

**Taichi: A Language for High-Performance Computation on Spatially Sparse Data Structures.**<br>
*Hu, Yuanming, Tzu-Mao Li, Luke Anderson, Jonathan Ragan-Kelley, and Frédo Durand.*<br>
2019. [[PDF](https://yuanming.taichi.graphics/publication/2019-taichi/taichi-lang-supp.pdf)]

**Simit: A Language for Physical Simulation.**<br>
*Kjolstad, Fredrik, Shoaib Kamil, Jonathan Ragan-Kelley, David IW Levin, Shinjiro Sueda, Desai Chen, Etienne Vouga et al.*<br>
2016. [[PDF](http://fredrikbk.com/publications/simit.pdf)]

## Courses

**Dynamic Deformables: Implementation and Production Practicalities.**<br>
*Kim, Theodore, and David Eberle.*<br>
2020. [[PDF](https://graphics.pixar.com/library/DynamicDeformablesSiggraph2020/paper.pdf)]

**Practical Course on Computing Derivatives in Code.**<br>
*Schroeder, Craig.*<br>
2019. [[PDF](https://www.cs.ucr.edu/~craigs/papers/2019-derivatives/talk.pdf)]

**FEM Simulation of 3D Deformable Solids: A practitioner’s guide to theory, discretization and model reduction.**<br>
*Sifakis, Eftychios, and Jernej Barbic.*<br>
SIGGRAPH 2012. [[PDF](http://barbic.usc.edu/femdefo/model-reduction-SIGGRAPH2012.pdf)]

## Others 

**Accelerated Complex Step Finite Difference for Expedient Deformable Simulation.**<br>
*Luo, Ran, Weiwei Xu, Tianjia Shao, Hongyi Xu, and Yin Yang.*<br>
2019. [[Website](https://dl.acm.org/doi/10.1145/3355089.3356493)]

**Generalized Drag Force for Particle-Based Simulations.**<br>
*Gissler, Christoph, Stefan Band, Andreas Peer, Markus Ihmsen, and Matthias Teschner.*<br>
2017. [[PDF](https://cg.informatik.uni-freiburg.de/publications/2017_CAG_generalizedDragForce_v2.pdf)]

**Stable Constrained Dynamics.**<br>
*Tournier, Maxime, Matthieu Nesme, Benjamin Gilles, and François Faure.*<br>
2015. [[PDF](https://hal.inria.fr/hal-01157835v2/document)]

**A Versatile and Robust Model for Geometrically Complex Deformable Solids.**<br>
*Teschner, Matthias, Bruno Heidelberger, Matthias Muller, and Markus Gross.*<br>
2004. [[PDF](https://cg.informatik.uni-freiburg.de/publications/2004_CGI_deformation.pdf)]

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

