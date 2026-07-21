---
layout: archive
title: Research
permalink: /projects/
author_profile: true
---

<style>
  .research-page {
    width: 100%;
    font-size: 1em;
  }

  .research-status {
    margin: 0 0 2.25em;
    color: #666;
    font-style: italic;
  }

  .research-section-title {
    margin: 0 0 0.4em;
    font-size: 2em;
    line-height: 1.2;
  }

  .research-section-intro {
    max-width: 52rem;
    margin: 0 0 2.25em;
    font-size: 1.04em;
    line-height: 1.65;
  }

  .research-section-divider {
    margin: 3.5em 0;
    border: 0;
    border-top: 1px solid #d8d8d8;
  }

  .research-paper {
    margin: 0 0 3.25em;
  }

  .research-paper-title {
    margin: 0 0 0.35em;
    font-size: 1.4em;
    line-height: 1.3;
  }

  .research-authors {
    margin: 0 0 1em;
    font-style: italic;
  }

  .research-paper-body {
    display: grid;
    grid-template-columns: minmax(220px, 38%) minmax(0, 1fr);
    gap: 2em;
    align-items: start;
  }

  .research-paper-image {
    display: block;
    width: 100%;
    height: auto;
    margin: 0;
    border-radius: 3px;
  }

  .research-summary {
    line-height: 1.65;
  }

  .research-summary > p:first-child {
    margin-top: 0;
  }

  .research-links {
    margin: 1em 0 0;
  }

  .research-links a {
    display: inline-block;
    margin-right: 0.65em;
    font-weight: 600;
    white-space: nowrap;
  }

  @media (max-width: 700px) {
    .research-section-title {
      font-size: 1.7em;
    }

    .research-paper-title {
      font-size: 1.25em;
    }

    .research-paper-body {
      grid-template-columns: 1fr;
      gap: 1.25em;
    }

    .research-paper-image {
      max-width: 32rem;
    }
  }
</style>

<div class="research-page">

<p class="research-status">This page is under construction; additional projects and materials will be added.</p>

<section class="research-section" aria-labelledby="data-driven-dynamical-systems">
  <h2 id="data-driven-dynamical-systems" class="research-section-title">Data-Driven Dynamical Systems</h2>
  <p class="research-section-intro">This work develops measure-theoretic and operator-based methods for learning nonlinear dynamics from sparse, noisy, or partial observations. A recurring goal is to recover models that reproduce both transient evolution and long-time statistical behavior.</p>

  <article class="research-paper">
    <h3 class="research-paper-title">Data-Adaptive Learning of Dynamical Systems by Matching Transfer Operators and Invariant Measures</h3>
    <p class="research-authors">Yinong Huang, Jonah Botvinick-Greenhouse, and Yunan Yang</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Data-adaptive mesh and transition-operator results" src="https://github.com/user-attachments/assets/80677a74-573e-455c-aa91-ebffb7cbaf63">
      </div>
      <div class="research-summary">
        <p>We introduce a transition-statistics approach to system identification that learns dynamics by matching the induced motion of probability mass across a data-adaptive mesh. Given trajectory data, we build an unstructured partition of state space and approximate the Perron–Frobenius operator with a regularized Ulam transition matrix. We replace hard cell indicators with continuous, piecewise-smooth partition-of-unity weights, yielding a Markov matrix that supports gradient-based optimization with respect to the parameters of a learned vector field.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2607.00391">[arXiv]</a>
          <!-- <a href="JOURNAL-LINK">[journal]</a> -->
          <a href="https://github.com/Yinonghyn/Parameter-Identification-with-Data-Driven-Cells">[code]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>

  <article class="research-paper">
    <h3 class="research-paper-title">Measure-Theoretic Time-Delay Embedding</h3>
    <p class="research-authors">Jonah Botvinick-Greenhouse, Maria Oprea, Romit Maulik, and Yunan Yang</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Measure-theoretic time-delay embedding results" src="https://github.com/user-attachments/assets/193168e4-0f04-4691-998d-5f3248d79ee3">
      </div>
      <div class="research-summary">
        <p>The celebrated Takens' embedding theorem provides a theoretical foundation for reconstructing the full state of a dynamical system from partial observations. However, the classical theorem assumes that the underlying system is deterministic and that observations are noise-free, limiting its applicability in real-world scenarios. Motivated by these limitations, we formulate a measure-theoretic generalization that adopts an Eulerian description of the dynamics and recasts the embedding as a pushforward map between spaces of probability measures.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2409.08768">[arXiv]</a>
          <a href="https://link.springer.com/article/10.1007/s10955-025-03555-1">[journal]</a>
          <a href="https://github.com/jrbotvinick/Measure-Theoretic-Time-Delay-Embedding">[code]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>

  <article class="research-paper">
    <h3 class="research-paper-title">Invariant Measures in Time-Delay Coordinates for Unique Dynamical System Identification</h3>
    <p class="research-authors">Jonah Botvinick-Greenhouse, Robert Martin, and Yunan Yang</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Invariant measures in time-delay coordinates" src="https://github.com/user-attachments/assets/d2d92d64-6a8a-4103-8cc8-0871a5c707f1">
      </div>
      <div class="research-summary">
        <p>Invariant measures are widely used to compare chaotic dynamical systems, as they offer robustness to noisy data, uncertain initial conditions, and irregular sampling. However, large classes of systems with distinct transient dynamics can still exhibit the same asymptotic statistical behavior, which poses challenges when invariant measures alone are used for system identification. Motivated by Takens' seminal embedding theory, we propose studying invariant measures in time-delay coordinates, which exhibit enhanced sensitivity to the underlying dynamics.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2412.00589v2">[arXiv]</a>
          <a href="https://journals.aps.org/prl/abstract/10.1103/ppys-lx68">[journal]</a>
          <a href="https://github.com/jrbotvinick/Invariant-Measures-in-Time-Delay-Coordinates-for-Unique-Dynamical-System-Identification">[code]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>

  <article class="research-paper">
    <h3 class="research-paper-title">Learning Dynamics on Invariant Measures Using PDE-Constrained Optimization</h3>
    <p class="research-authors">Jonah Botvinick-Greenhouse, Robert Martin, and Yunan Yang</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="PDE-constrained learning on invariant measures" src="https://github.com/user-attachments/assets/86eb0490-e677-4bee-ab78-37fa9d6329bb">
      </div>
      <div class="research-summary">
        <p>We extend the methodology in Yang et al. (2023) to learn autonomous continuous-time dynamical systems from invariant measures. The central idea is to reformulate the inverse problem of learning ODEs or SDEs from data as a PDE-constrained optimization problem. This shift in perspective allows us to learn from slowly sampled inference trajectories and perform uncertainty quantification for the forecasted dynamics.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2301.05193">[arXiv]</a>
          <a href="https://pubs.aip.org/aip/cha/article/33/6/063152/2900453/Learning-dynamics-on-invariant-measures-using-PDE">[journal]</a>
          <a href="https://github.com/jrbotvinick/Learning-Dynamics-on-Invariant-Measures">[code]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>

  <article class="research-paper">
    <h3 class="research-paper-title">An Unstructured Mesh Approach to Nonlinear Noise Reduction for Coupled Systems</h3>
    <p class="research-authors">Aaron Kirtland, Jonah Botvinick-Greenhouse, Marianne DeBrito, Megan Osborne, Casey Johnson, Robert S. Martin, Samuel J. Araki, and Daniel Q. Eckhardt</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Unstructured-mesh nonlinear noise reduction" src="https://github.com/user-attachments/assets/c61a70ed-a9b1-4dba-802c-91ed26f00919">
      </div>
      <div class="research-summary">
        <p>To address noise inherent in electronic data-acquisition systems and real-world sources, Araki et al. (Physica D, 2021) developed a grid-based nonlinear technique that removes noise from a chaotic signal by leveraging a clean, high-fidelity signal from the same dynamical system and ensemble averaging in multidimensional phase space. Although the method denoised time-series data with 100% added noise, it suffered in regions of low data density. Here, an unstructured mesh based on triangulations and Voronoi diagrams is used to improve the method.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2209.05944">[arXiv]</a>
          <a href="https://epubs.siam.org/doi/10.1137/22M152092X">[journal]</a>
          <a href="https://github.com/atkirtland/denoising-clean">[code]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>
</section>

<hr class="research-section-divider">

<section class="research-section" aria-labelledby="measure-transport">
  <h2 id="measure-transport" class="research-section-title">Measure Transport</h2>
  <p class="research-section-intro">This work studies how maps, vector fields, and evolving probability distributions can be recovered or constructed through their action on measures. The emphasis is on identifiability, efficient computation, and generative modeling.</p>

  <article class="research-paper">
    <h3 class="research-paper-title">On the Unique Recovery of Transport Maps and Vector Fields from Finite Measure-Valued Data</h3>
    <p class="research-authors">Jonah Botvinick-Greenhouse and Yunan Yang</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Recovery of transport maps and vector fields from measure-valued data" src="https://github.com/user-attachments/assets/fa1f832e-25df-4399-a749-41b88bbf2230">
      </div>
      <div class="research-summary">
        <p>We establish guarantees for the unique recovery of vector fields and transport maps from finite measure-valued data, yielding new insights into generative models, data-driven dynamical systems, and PDE inverse problems. In particular, we provide general conditions under which a diffeomorphism can be uniquely identified from its pushforward action on finitely many densities—that is, when the data $\{(\rho_j,f\#\rho_j)\}_{j=1}^m$ uniquely determine $f$. As a corollary, we introduce a new metric that compares diffeomorphisms by measuring the discrepancy between finitely many pushforward densities.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2604.07671">[arXiv]</a>
          <a href="https://github.com/jrbotvinick/Transport-Map-and-Vector-Field-Recovery">[code]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>

  <article class="research-paper">
    <h3 class="research-paper-title">Generative Modeling of Time-Dependent Densities via Optimal Transport and Projection Pursuit</h3>
    <p class="research-authors">Jonah Botvinick-Greenhouse, Yunan Yang, and Romit Maulik</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Generative modeling of time-dependent densities" src="https://github.com/user-attachments/assets/37398c1c-09b7-45f0-88af-fa94e8ea88f5">
      </div>
      <div class="research-summary">
        <p>Motivated by the computational difficulties of popular deep-learning algorithms for generative modeling of temporal densities, we propose an inexpensive alternative that requires minimal hyperparameter tuning and scales favorably to high-dimensional problems. We use a projection-based optimal transport solver to join successive samples and transport splines to interpolate the evolving density.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2304.09663">[arXiv]</a>
          <a href="https://pubs.aip.org/aip/cha/article/33/10/103108/2915710/Generative-modeling-of-time-dependent-densities">[journal]</a>
          <a href="https://github.com/jrbotvinick/Dynamic-PPMM">[code]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>
</section>

<hr class="research-section-divider">

<section class="research-section" aria-labelledby="scientific-machine-learning">
  <h2 id="scientific-machine-learning" class="research-section-title">Scientific Machine Learning</h2>
  <p class="research-section-intro">These projects develop learning-based surrogates and numerical methods for challenging scientific models. They combine physical structure, adaptive representations, and large-scale simulation data to improve accuracy and computational efficiency.</p>

  <article class="research-paper">
    <h3 class="research-paper-title">Operator Learning Surrogate Modeling of Hydraulically Fractured Geothermal Injection-Production Systems: A Cornell Case Study</h3>
    <p class="research-authors">Yulong Liu, Jonah Botvinick-Greenhouse, Yunan Yang, and Chloé Arson</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Operator-learning surrogate for geothermal systems" src="https://github.com/user-attachments/assets/27ee111f-ad00-4350-b504-d811c31411d4">
      </div>
      <div class="research-summary">
        <p>Through its Climate Action Plan, Cornell University has committed to achieving carbon neutrality by 2035 and has supported the Earth Source Heat project to demonstrate the viability of direct-use deep geothermal energy for district heating on its Ithaca campus. To enable rapid inference and optimization of fracture-dominated doublet designs under site constraints, we train an operator-learning surrogate on 5,500 finite-element simulations and evaluate it on 498 unseen cases.</p>
        <p class="research-links">
          <a href="https://onepetro.org/ARMAUSRMS/proceedings/ARMA26/ARMA26/D022S043R004/801293">[conference]</a>
          <!-- <a href="SLIDES-LINK">[slides]</a> -->
        </p>
      </div>
    </div>
  </article>

  <article class="research-paper">
    <h3 class="research-paper-title">AB-PINNs: Adaptive-Basis Physics-Informed Neural Networks for Residual-Driven Domain Decomposition</h3>
    <p class="research-authors">Jonah Botvinick-Greenhouse, Wael H. Ali, Mouhacine Benosman, and Saviz Mowlavi</p>
    <div class="research-paper-body">
      <div>
        <img class="research-paper-image" alt="Adaptive-basis physics-informed neural networks" src="https://github.com/user-attachments/assets/923e6bb6-918f-4563-90c0-2eb559e070f7">
      </div>
      <div class="research-summary">
        <p>We introduce adaptive-basis physics-informed neural networks (AB-PINNs), a domain-decomposition approach in which existing subdomains dynamically adapt to the intrinsic features of the unknown solution. Drawing inspiration from classical mesh-refinement techniques, we also modify the decomposition during training by introducing new subdomains in regions of high residual loss, providing additional expressive power where the solution is challenging to represent.</p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2510.08924">[arXiv]</a>
          <a href="https://iopscience.iop.org/article/10.1088/2632-2153/ae8638">[journal]</a>
          <a href="https://github.com/merlresearch/ab-pinns">[code]</a>
        </p>
      </div>
    </div>
  </article>
</section>

<!-- Add paper entries here using the same article structure. -->

</div>
