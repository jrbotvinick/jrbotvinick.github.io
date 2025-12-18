---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
**Title:** [AB-PINNs: Adaptive-Basis Physics-Informed Neural Networks for Residual-Driven Domain Decomposition](https://arxiv.org/abs/2510.08924)

**Collaborators:**  Wael H. Ali (MERL), Mouhacine Benosman (Amazon Robotics), and Saviz Mowlavi (MERL) 

**Abstract:** We introduce adaptive-basis physics-informed neural networks (AB-PINNs), a novel approach to domain decomposition for training PINNs in which existing subdomains dynamically adapt to the intrinsic features of the unknown solution. Drawing inspiration from classical mesh refinement techniques, we also modify the domain decomposition on-the-fly throughout training by introducing new subdomains in regions of high residual loss, thereby providing additional expressive power where the solution of the differential equation is challenging to represent. Our flexible approach to domain decomposition is well-suited for multiscale problems, as different subdomains can learn to capture different scales of the underlying solution. Moreover, the ability to introduce new subdomains during training helps prevent convergence to unwanted local minima and can reduce the need for extensive hyperparameter tuning compared to static domain decomposition approaches. Throughout, we present comprehensive numerical results which demonstrate the effectiveness of AB-PINNs at solving a variety of complex multiscale partial differential equations.

<img width="1210" height="356" alt="AB-PINN" src="https://github.com/user-attachments/assets/dc83f458-781d-4ffa-88a6-7e2117914589" />

--- 
**Title:** [Invariant Measures in Time-Delay Coordinates for Unique Dynamical System Identification](https://arxiv.org/abs/2412.00589#:~:text=Invariant%20Measures%20in%20Time%2DDelay%20Coordinates%20for%20Unique%20Dynamical%20System%20Identification,-Jonah%20Botvinick%2DGreenhouse&text=Invariant%20measures%20are%20widely%20used,initial%20conditions%2C%20and%20irregular%20sampling.)

**Collaborators:** Robert Martin (DEVCOM Army Research Laboratory) and Yunan Yang (Cornell University) 

**Abstract:** Invariant measures are widely used to compare chaotic dynamical systems, as they offer robustness to noisy data, uncertain initial conditions, and irregular sampling. However, large classes of systems with distinct transient dynamics can still exhibit the same asymptotic statistical behavior, which poses challenges when invariant measures alone are used to perform system identification. Motivated by Takens' seminal embedding theory, we propose studying invariant measures in time-delay coordinates, which exhibit enhanced sensitivity to the underlying dynamics. Our first result demonstrates that a single invariant measure in time-delay coordinates can be used to perform system identification up to a topological conjugacy. This result already surpasses the capabilities of invariant measures in the original state coordinate. Continuing to explore the power of delay-coordinates, we eliminate all ambiguity from the conjugacy relation by showing that unique system identification can be achieved using additional invariant measures in time-delay coordinates constructed from different observables. Our findings improve the effectiveness of invariant measures in system identification and broaden the scope of measure-theoretic approaches to modeling dynamical systems.

<img width="926" alt="Screenshot 2025-02-02 at 11 59 41 AM" src="https://github.com/user-attachments/assets/bda751e0-657b-4be1-8917-5686f5f0881b" />

----

**Title:** [Measure-Theoretic Time-Delay Embedding](https://arxiv.org/abs/2409.08768)

**Collaborators:** Maria Oprea (Cornell University), Romit Maulik (Pennsylvania State University), and Yunan Yang (Cornell University)

**Abstract:** The celebrated Takens’ embedding theorem provides a theoretical foundation for reconstruct-
ing the full state of a dynamical system from partial observations. However, the classical the-
orem assumes that the underlying system is deterministic and that observations are noise-free,
limiting its applicability in real-world scenarios. Motivated by these limitations, we rigorously
establish a measure-theoretic generalization that adopts an Eulerian description of the dynamics
and recasts the embedding as a pushforward map between probability spaces. Our mathemat-
ical results leverage recent advances in optimal transportation theory. Building on our novel
measure-theoretic time-delay embedding theory, we have developed a new computational frame-
work that forecasts the full state of a dynamical system from time-lagged partial observations,
engineered with better robustness to handle sparse and noisy data. We showcase the efficacy
and versatility of our approach through several numerical examples, ranging from the classic
Lorenz-63 system to large-scale, real-world applications such as NOAA sea surface temperature
forecasting and ERA5 wind field reconstruction.

<img width="1342" alt="Screenshot 2025-02-02 at 11 55 47 AM" src="https://github.com/user-attachments/assets/4275ecb4-a167-46cc-8233-6f2ef605c30c" />


----

**Title:** [Learning Dynamics on Invariant Measures Using PDE-Constrained Optimization](https://pubs.aip.org/aip/cha/article-abstract/33/6/063152/2900453/Learning-dynamics-on-invariant-measures-using-PDE?redirectedFrom=fulltext)

**Collaborators:** Robert S. Martin (DEVCOM Army Research Laboratory) and Yunan Yang (Cornell University)

**Abstract:** We extend the methodology in [[Yang et al., 2023]](https://epubs.siam.org/doi/10.1137/21M1421337) to learn autonomous continuous-time dynamical systems from invariant measures. The highlight of our approach is to reformulate the inverse problem of learning ODEs or SDEs from data as a PDE-constrained optimization problem. This shift in perspective allows us to learn from slowly sampled inference trajectories and perform uncertainty quantification for the forecasted dynamics. Our approach also yields a forward model with better stability than direct trajectory simulation in certain situations. We present numerical results for the Van der Pol oscillator and the Lorenz-63 system, together with real-world applications to Hall-effect thruster dynamics and temperature prediction, to demonstrate the effectiveness of the proposed approach.

![Figure1 (5)](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/3307bc3f-0ae2-4402-9783-eff4e8ec3eb7)

----

**Title:** [An Unstructured Mesh Approach to Nonlinear Noise Reduction for Coupled Systems](https://epubs.siam.org/doi/10.1137/22M152092X)

**Collaborators:** Aaron Kirtland (Brown University), Marianne DeBritto (University of Michigan), Megan Osborne (Rensselaer Polytechnic Institute), Casey Johnson (University of California, Los Angelos), Robert S. Martin (DEVCOM Army Research Laboratory), Samuel J. Araki (Jacobs Technology Inc., AFRL), Daniel Q. Eckhardt (In-Space Propulsion Branch, AFRL)

**Abstract:** To address noise inherent in electronic data acquisition systems and real-world sources, [[Araki et al., 2021]](https://www.sciencedirect.com/science/article/pii/S0167278920308204) demonstrated a grid-based nonlinear technique to remove noise from a chaotic signal, leveraging a clean high-fidelity signal from the same dynamical system and ensemble averaging in multidimensional phase space. This method achieved denoising of a time series data with 100% added noise but suffered in regions of low data density. To improve this grid-based method, here an unstructured mesh based on triangulations and Voronoi diagrams is used to accomplish the same task. The unstructured mesh more uniformly distributes data samples over mesh cells to improve the accuracy of the reconstructed signal. By empirically balancing bias and variance errors in selecting the number of unstructured cells as a function of the number of available samples, the method achieves asymptotic statistical convergence with known test data and reduces synthetic noise on experimental signals from Hall effect thrusters with greater success than the original grid-based strategy.

![afrl_fig](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/a6f045f6-c3be-4ea8-8216-de6e4964eb92)

----

**Title:** [Generative Modeling of Time-Dependent Densities via Optimal Transport and Projection Pursuit](https://pubs.aip.org/aip/cha/article-abstract/33/10/103108/2915710/Generative-modeling-of-time-dependent-densities?redirectedFrom=fulltext)

**Collaborators:** Yunan Yang (Cornell University) and Romit Maulik (Pennsylvania State University & Argonne National Laboratory)

**Abstract:** Motivated by the computational difficulties incurred by popular deep learning algorithms for the
generative modeling of temporal densities, we propose a cheap alternative which requires minimal
hyperparameter tuning and scales favorably to high dimensional problems. In particular, we use
a projection-based optimal transport solver [[Meng et al., 2019]](https://arxiv.org/abs/2106.05838) to join successive samples and
subsequently use transport splines [[Chewi et al., 2020]](https://proceedings.mlr.press/v130/chewi21a/chewi21a.pdf) to interpolate the evolving density. When
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

**Title:** [An Introduction to the Theory of the Ergodic Partition (Undergraduate Honors Thesis)](https://drive.google.com/file/d/1xlYZ3xDFNHVAsjyuq--A6h3ydFW5D2AS/view?usp=drive_link)

**Advisor:** Ryan J. Alvarado (Amherst College)

**Abstract:** Evolving systems can rarely be studied through direct observation of their underlying
state. More commonly, one is restricted to analyzing partial measurements of the system,
known as observables. It is therefore important to determine the extent to which such
observables recover useful information about the system in question. Towards this, we draw
from techniques in ergodic theory, functional analysis, and probability theory to rigorously
develop tools for identifying invariant regions in dynamical systems through the analysis of
observables. We conclude by studying a computational approach to this problem, informed
by the theory developed throughout the body of the thesis.

![MSP](https://github.com/jrbotvinick/jrbotvinick.github.io/assets/100333155/a943a12e-fc4f-4547-aabb-92bf77365578)

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
