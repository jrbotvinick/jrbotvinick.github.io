---
permalink: /
title: "Introduction"
excerpt: "Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

(Website under construction)


I am a Ph.D. student at the Center for Applied Mathematics at Cornell University advised by [Professor Yunan Yang](https://as.cornell.edu/people/yunan-yang). My research is supported by an [NDSEG Fellowship](https://ndseg.sysplus.com/) and broadly focuses on inverse problems for dynamical systems, such as parameter estimation, state reconstruction, and the interpolation of stochastic processes. Before arriving at Cornell, I previously earned B.A.s in Mathematics and Physics at Amherst College, where I was advised by [Professor Ryan J. Alvarado](https://www.amherst.edu/people/facstaff/rjalvarado).

Research Interests
====
My research interests are in dynamical systems, ergodic theory, optimal transport, numerical analysis, inverse problems, and machine learning. 

Research Projects
====

**Title:** Generative Modeling of Time-Dependent Densities via Optimal Transport and Projection Pursuit

**Collaborators:** Yunan Yang (Cornell University) and Romit Maulik (Pennsylvania State University & Argonne National Laboratory)

**Abstract:** Motivated by the computational difficulties incurred by popular deep learning algorithms for the
generative modeling of temporal densities, we propose a cheap alternative which requires minimal
hyperparameter tuning and scales favorably to high dimensional problems. In particular, we use
a projection-based optimal transport solver [Meng et al., 2019] to join successive samples and
subsequently use transport splines [Chewi et al., 2020] to interpolate the evolving density. When
the sampling frequency is sufficiently high, the optimal maps are close to the identity and are thus
computationally efficient to compute. Moreover, the training process is highly parallelizable as all
optimal maps are independent and can thus be learned simultaneously. Finally, the approach is based
solely on numerical linear algebra rather than minimizing a nonconvex objective function, allowing
us to easily analyze and control the algorithm. We present several numerical experiments on both
synthetic and real-world datasets to demonstrate the efficiency of our method. In particular, these
experiments show that the proposed approach is highly competitive compared with state-of-the-art
normalizing flows conditioned on time across a wide range of dimensionalities.

![OTNF](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/f7a5700f-16e7-4957-9aa3-daaea13f377e)

**Title:** Learning Dynamics on Invariant Measures Using PDE-Constrained Optimization

**Collaborators:** Robert S. Martin (DEVCOM Army Research Laboratory) and Yunan Yang (Cornell University)

**Abstract:** We extend the methodology in [Yang et al., 2023] to learn autonomous continuous-time dynamical systems from invariant measures. The highlight of our approach is to reformulate the inverse problem of learning ODEs or SDEs from data as a PDE-constrained optimization problem. This shift in perspective allows us to learn from slowly sampled inference trajectories and perform uncertainty quantification for the forecasted dynamics. Our approach also yields a forward model with better stability than direct trajectory simulation in certain situations. We present numerical results for the Van der Pol oscillator and the Lorenz-63 system, together with real-world applications to Hall-effect thruster dynamics and temperature prediction, to demonstrate the effectiveness of the proposed approach.

![Figure1 (5)](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/3307bc3f-0ae2-4402-9783-eff4e8ec3eb7)

**Title:** An Unstructured Mesh Approach to Nonlinear Noise Reduction for Coupled Systems

**Collaborators:** Aaron Kirtland (Brown University), Marianne DeBritto (University of Michigan), Megan Osborne (Rensselaer Polytechnic Institute), Casey Johnson (University of California, Los Angelos), Robert S. Martin (DEVCOM Army Research Laboratory), Samuel J. Araki (Jacobs Technology Inc., AFRL), Daniel Q. Eckhardt (In-Space Propulsion Branch, AFRL)*

**Abstract:** To address noise inherent in electronic data acquisition systems and real-world sources, Araki et al. [Phys. D, 417 (2021), 132819] demonstrated a grid-based nonlinear technique to remove noise from a chaotic signal, leveraging a clean high-fidelity signal from the same dynamical system and ensemble averaging in multidimensional phase space. This method achieved denoising of a time series data with 100% added noise but suffered in regions of low data density. To improve this grid-based method, here an unstructured mesh based on triangulations and Voronoi diagrams is used to accomplish the same task. The unstructured mesh more uniformly distributes data samples over mesh cells to improve the accuracy of the reconstructed signal. By empirically balancing bias and variance errors in selecting the number of unstructured cells as a function of the number of available samples, the method achieves asymptotic statistical convergence with known test data and reduces synthetic noise on experimental signals from Hall effect thrusters with greater success than the original grid-based strategy.

![afrl_fig](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/a6f045f6-c3be-4ea8-8216-de6e4964eb92)

