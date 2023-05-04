## Final project scope and ideas

### Scope
Your project should be a deep exploration of a physics topic of your choosing. If it is something you are already doing as poart of your research that is ok as long as you dive deep to develop the numerical techniques, visualizzation, analysis etc. significantly further building on what we learnt in class. The *three* deliverables will be 
- reproducible code that we can use to recreate your results.  It should be extensively commented and described. 
- A written summary [1-2 pages] of your investigation. that references all source materials used. If you use large language models to help you describe how you used them and how helpful they have been. Also describe lessons learned. 
- A 15-20 minute minute video of a presentation describing the project, your implementation, the results, and what you conclude from your work. 

### Examples
Here is a list of some topics students have worked on in previous years and also some links to other online resources that could help you in formulating your own final project. 
If at all look for things that interest you. You will find many things online that will help you get started on even complicated sounding topics. The more interesting you find a topic the higher the chance of a successful final project you'll be proud of at the end. 

-  **Quantum Circuit Simulation and Error Models using Qiskit** 
  [Qiskit](https://qiskit.org) is an open source toolkit to express quantum computing ideas. It allows you to wirte programs for quantum computers and run it on existing hardware. The give a number of [tutorials](https://qiskit.org/documentation/tutorials.html) work through some of them and explore one of them more deeply by modifying the approaches and give detailed explanations of your findings and your experience learning the material. 
- **Exploration of a large number of solutions to the 2 dimensional Poisson equation for different boundary conditions** 
- Write a 2D Eulerian hydrodynamics code
  Start with [this notebook](https://github.com/python-hydro/how_to_write_a_hydro_code/blob/master/write_a_hydrocode.ipynb) to learn about how this is done in 1 dimensions. Generalize it to two dimensions and explore some of the test problems as described [here](https://www.astro.princeton.edu/~jstone/Athena/tests/index.html) 
- **Finding the Ground State of a Quantum System in 2D and 3D using Relaxation Method** 
  Solve Schrödinger's equation as described in the paper published by Daniel V. Schroeder located [here](https://aapt.scitation.org/doi/10.1119/1.4997165). He outlines a relaxation algorithm that relies only on the known boundary conditions, but unlike the Poisson equation, we also have an unknown eigenvalue problem.
- **Cellular Automata** 
  Cellular automata are graphs where each vertex of the lattice has some discrete state space (e.g. could be colored black or white). There are discrete time steps where vertices are updated according to some local update rule. That is, a vertex is updated according to its value and the values of some of the surrounding vertices. Give some canonical examples of cellular automata and links to active areas of research involving them, ***such as classical and quantum integrability, the emergence of hydrodynamics*** from microscopic dynamics, and quantum error correction.
- **Bifurcation Theory** 
  Explore [Bifurcation Theory](https://en.wikipedia.org/wiki/Bifurcation_theory) coding up different non-linear systems showing examples of local bifurcations, period-doubling bifurcations and Hopf bifurcations among others. 
- [**Finite-Difference Time-domain method**](https://en.wikipedia.org/wiki/Finite-difference_time-domain_method)
  Explore the FDTD methods to solve the time dependent Maxwell's equations. This is a standard tool in computational electrodynamics used in a very large range of applications including device design. 
- **Quantum and classical estimators of Pi**
  Explore and code up different ways to estimate pi including using quantum estimators as described [here](https://arxiv.org/abs/2008.02623) 
- [Explore Stochastic Differential Equations](https://github.com/nordam/ComputationalPhysics/blob/master/Notebooks/13%20-%20Stochastic%20Differential%20Equations.ipynb) as given in the notebook in the link. Use this as a jumping off point to devise your own problem setup and study a specific physical situation modelled via a stochastic differential equation. Desribe the physics and what yuou have learned. 