---
layout: archive
title: "Research Projects"
permalink: /portfolio/
author_profile: true
---

**Title:** [Generative Modeling of Time-Dependent Densities via Optimal Transport and Projection Pursuit](https://pubs.aip.org/aip/cha/article-abstract/33/10/103108/2915710/Generative-modeling-of-time-dependent-densities?redirectedFrom=fulltext)

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

![Figure2](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/bf44f0ee-dab8-476f-a709-ab622197ee7a)

----

**Title:** [Learning Dynamics on Invariant Measures Using PDE-Constrained Optimization](https://pubs.aip.org/aip/cha/article-abstract/33/6/063152/2900453/Learning-dynamics-on-invariant-measures-using-PDE?redirectedFrom=fulltext)

**Collaborators:** Robert S. Martin (DEVCOM Army Research Laboratory) and Yunan Yang (Cornell University)

**Abstract:** We extend the methodology in [[Yang et al., 2023]](https://epubs.siam.org/doi/10.1137/21M1421337) to learn autonomous continuous-time dynamical systems from invariant measures. The highlight of our approach is to reformulate the inverse problem of learning ODEs or SDEs from data as a PDE-constrained optimization problem. This shift in perspective allows us to learn from slowly sampled inference trajectories and perform uncertainty quantification for the forecasted dynamics. Our approach also yields a forward model with better stability than direct trajectory simulation in certain situations. We present numerical results for the Van der Pol oscillator and the Lorenz-63 system, together with real-world applications to Hall-effect thruster dynamics and temperature prediction, to demonstrate the effectiveness of the proposed approach.

![Figure1 (5)](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/3307bc3f-0ae2-4402-9783-eff4e8ec3eb7)

----

**Title:** [An Unstructured Mesh Approach to Nonlinear Noise Reduction for Coupled Systems](https://epubs.siam.org/doi/10.1137/22M152092X)

**Collaborators:** Aaron Kirtland (Brown University), Marianne DeBritto (University of Michigan), Megan Osborne (Rensselaer Polytechnic Institute), Casey Johnson (University of California, Los Angelos), Robert S. Martin (DEVCOM Army Research Laboratory), Samuel J. Araki (Jacobs Technology Inc., AFRL), Daniel Q. Eckhardt (In-Space Propulsion Branch, AFRL)

**Abstract:** To address noise inherent in electronic data acquisition systems and real-world sources, Araki et al. [Phys. D, 417 (2021), 132819] demonstrated a grid-based nonlinear technique to remove noise from a chaotic signal, leveraging a clean high-fidelity signal from the same dynamical system and ensemble averaging in multidimensional phase space. This method achieved denoising of a time series data with 100% added noise but suffered in regions of low data density. To improve this grid-based method, here an unstructured mesh based on triangulations and Voronoi diagrams is used to accomplish the same task. The unstructured mesh more uniformly distributes data samples over mesh cells to improve the accuracy of the reconstructed signal. By empirically balancing bias and variance errors in selecting the number of unstructured cells as a function of the number of available samples, the method achieves asymptotic statistical convergence with known test data and reduces synthetic noise on experimental signals from Hall effect thrusters with greater success than the original grid-based strategy.

![afrl_fig](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/a6f045f6-c3be-4ea8-8216-de6e4964eb92)

----

**Title:** [Juggling Dynamics](https://pubs.aip.org/physicstoday/article/73/2/62/914452/Juggling-dynamicsWith-complex-throwing-patterns-of)

**Collaborator:** Troy Shinbrot (Rutgers University) 

**Excerpt:** How do jugglers with reaction times no better than
200 ms catch balls every 120 ms? In part, multitasking
may allow multiple balls to be processed simultaneously,
though how that is done with 11 balls—the Guinness world
record—is far from clear. And in part, balls are not thrown
to random locations, so each ball need not be tracked and
caught independently. Indeed, up to five balls can be juggled
while the juggler is blindfolded. Jugglers rely on making accurate throws and predictions of where the balls will travel.
The accuracy required is a measure of how unstable and
thus how difficult a particular juggling pattern is.

![juggling_picture](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/ea33a26f-3d5f-471b-95ed-494688a9eeaf)

----

