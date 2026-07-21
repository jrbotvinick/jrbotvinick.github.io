---
layout: page
title: Research
permalink: /projects/
---
<div style="max-width: 1100px; margin: 0 auto; padding: 0 32px; box-sizing: border-box;">

<p>Under construction</p>

<h2>Data-Driven Dynamical Systems</h2>

<h3>Data-Adaptive Learning of Dynamical Systems by Matching Transfer Operators and Invariant Measures</h3>

Yinong Huang, Jonah Botvinick-Greenhouse, and Yunan Yang

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="Data-adaptive learning of dynamical systems" src="https://github.com/user-attachments/assets/80677a74-573e-455c-aa91-ebffb7cbaf63">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      We introduce a transition-statistics approach to system identification that learns dynamics by
matching the induced motion of probability mass across a data-adaptive mesh. Given
trajectory data, we build an unstructured partition of state space and approximate the
Perron–Frobenius operator with a regularized Ulam transition matrix. We replace hard
cell indicators with continuous, piecewise-smooth partition-of-unity weights, yielding a
Markov matrix supporting gradient-based optimization with respect to the parameters of
a learned vector field. 
      <br><br>
      <a href="https://arxiv.org/abs/2607.00391">[arXiv]</a>
      <!-- <a href="JOURNAL-LINK">[journal]</a> -->
      <a href="https://github.com/Yinonghyn/Parameter-Identification-with-Data-Driven-Cells">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h3>Measure-Theoretic Time-Delay Embedding</h3>

Jonah Botvinick-Greenhouse, Maria Oprea, Romit Maulik, and Yunan Yang

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/193168e4-0f04-4691-998d-5f3248d79ee3">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      The celebrated Takens' embedding theorem provides a theoretical foundation for reconstructing the full state of a dynamical system from partial observations. However, the classical theorem assumes that the underlying system is deterministic and that observations are noise-free, limiting its applicability in real-world scenarios. Motivated by these limitations, we formulate a measure-theoretic generalization that adopts an Eulerian description of the dynamics and recasts the embedding as a pushforward map between spaces of probability measures. 
      <br><br>
      <a href="https://arxiv.org/abs/2409.08768">[arXiv]</a>
      <a href="https://link.springer.com/article/10.1007/s10955-025-03555-1">[journal]</a>
      <a href="https://github.com/jrbotvinick/Measure-Theoretic-Time-Delay-Embedding">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h3>Invariant Measures in Time-Delay Coordinates for Unique Dynamical System Identification</h3>

Jonah Botvinick-Greenhouse, Robert Martin, and Yunan Yang

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/d2d92d64-6a8a-4103-8cc8-0871a5c707f1">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      Invariant measures are widely used to compare chaotic dynamical systems, as they offer robustness to noisy data, uncertain initial conditions, and irregular sampling. However, large classes of systems with distinct transient dynamics can still exhibit the same asymptotic statistical behavior, which poses challenges when invariant measures alone are used to perform system identification. Motivated by Takens’ seminal embedding theory, we propose studying invariant measures in time-delay coordinates, which exhibit enhanced sensitivity to the underlying dynamics.
      <br><br>
      <a href="https://arxiv.org/abs/2412.00589v2">[arXiv]</a>
      <a href="https://journals.aps.org/prl/abstract/10.1103/ppys-lx68">[journal]</a>
      <a href="https://github.com/jrbotvinick/Invariant-Measures-in-Time-Delay-Coordinates-for-Unique-Dynamical-System-Identification">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h3>Learning Dynamics on Invariant Measures Using PDE-Constrained Optimization</h3>

Jonah Botvinick-Greenhouse, Robert Martin, and Yunan Yang

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/86eb0490-e677-4bee-ab78-37fa9d6329bb">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      We extend the methodology in [Yang et al., 2023] to learn autonomous continuous-time dynamical systems from invariant measures. The highlight of our approach is to reformulate the inverse problem of learning ODEs or SDEs from data as a PDE-constrained optimization problem. This shift in perspective allows us to learn from slowly sampled inference trajectories and perform uncertainty quantification for the forecasted dynamics.
      <br><br>
      <a href="https://arxiv.org/abs/2301.05193">[arXiv]</a>
      <a href="https://pubs.aip.org/aip/cha/article/33/6/063152/2900453/Learning-dynamics-on-invariant-measures-using-PDE">[journal]</a>
      <a href="https://github.com/jrbotvinick/Learning-Dynamics-on-Invariant-Measures">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h3>An Unstructured Mesh Approach to Nonlinear Noise Reduction for Coupled Systems</h3>

Aaron Kirtland, Jonah Botvinick-Greenhouse, Marianne DeBrito, Megan Osborne, Casey Johnson, Robert S. Martin, Samuel J. Araki, Daniel Q. Eckhardt

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/c61a70ed-a9b1-4dba-802c-91ed26f00919">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      To address noise inherent in electronic data acquisition systems and real world sources, Araki et al. [Physica D: Nonlinear Phenomena, 417 (2021) 132819] demonstrated a grid based nonlinear technique to remove noise from a chaotic signal, leveraging a clean high-fidelity signal from the same dynamical system and ensemble averaging in multidimensional phase space. This method achieved denoising of a time-series data with 100% added noise but suffered in regions of low data density. To improve this grid-based method, here an unstructured mesh based on triangulations and Voronoi diagrams is used to accomplish the same task.
      <br><br>
      <a href="https://arxiv.org/abs/2209.05944">[arXiv]</a>
      <a href="https://epubs.siam.org/doi/10.1137/22M152092X">[journal]</a>
      <a href="https://github.com/atkirtland/denoising-clean">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>


<h2>Measure Transport</h2>

<h3>On the Unique Recovery of Transport Maps and Vector Fields from Finite Measure-Valued Data</h3>

Jonah Botvinick-Greenhouse and Yunan Yang

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/fa1f832e-25df-4399-a749-41b88bbf2230">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      We establish guarantees for the unique recovery of vector fields and transport maps from finite measure-valued data, yielding new insights into generative models, data-driven dynamical systems, and PDE inverse problems. In particular, we provide general conditions under which a diffeomorphism can be uniquely identified from its pushforward action on finitely many densities, i.e., when the data $\{(ρ_j,f\#ρ_j)\}_{j=1}^m$ uniquely determines $f$. As a corollary, we introduce a new metric which compares diffeomorphisms by measuring the discrepancy between finitely many pushforward densities in the space of probability measures.
      <br><br>
      <a href="https://arxiv.org/abs/2604.07671">[arXiv]</a>
      <a href="https://github.com/jrbotvinick/Transport-Map-and-Vector-Field-Recovery">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h3>Generative modeling of time-dependent densities via optimal transport and projection pursuit</h3>

Jonah Botvinick-Greenhouse, Yunan Yang, and Romit Maulik

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/37398c1c-09b7-45f0-88af-fa94e8ea88f5">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
     Motivated by the computational difficulties incurred by popular deep learning algorithms for the generative modeling of temporal densities, we propose a cheap alternative that requires minimal hyperparameter tuning and scales favorably to high-dimensional problems. In particular, we use a projection-based optimal transport solver [Meng et al., Advances in Neural Information Processing Systems (Curran Associates, 2019), Vol. 32] to join successive samples and, subsequently, use transport splines (Chewi et al., 2020) to interpolate the evolving density.
      <br><br>
      <a href="https://arxiv.org/abs/2304.09663">[arXiv]</a>
      <a href="https://pubs.aip.org/aip/cha/article/33/10/103108/2915710/Generative-modeling-of-time-dependent-densities">[journal]</a>
      <a href="https://github.com/jrbotvinick/Dynamic-PPMM">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>


<h2>Scientific Machine Learning</h2>

<h3>Operator Learning Surrogate Modeling of Hydraulically Fractured Geothermal Injection-Production Systems: A Cornell Case Study</h3>

Yulong Liu,  Jonah Botvinick-Greenhouse,  Yunan Yang, and  Chloé Arson

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/27ee111f-ad00-4350-b504-d811c31411d4">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      Through its Climate Action Plan, Cornell University has committed to achieving carbon neutrality by 2035 and has supported the Earth Source Heat (ESH) project to demonstrate the viability of direct-use deep geothermal energy for district heating on its main campus in Ithaca, NY. To enable rapid inference and optimization of fracture-dominated doublet designs under CUBO site constraints, an operator learning surrogate model is trained on 5,500 finite-element (FE) simulations and evaluated on 498 unseen cases.
      <br><br>
      <a href="https://onepetro.org/ARMAUSRMS/proceedings/ARMA26/ARMA26/D022S043R004/801293">[conference]</a>
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h3>AB-PINNs: Adaptive-Basis Physics-Informed Neural Networks for Residual-Driven Domain Decomposition</h3>

Jonah Botvinick-Greenhouse, Wael H. Ali, Mouhacine Benosman, Saviz Mowlavi

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="MTDE" src="https://github.com/user-attachments/assets/27ee111f-ad00-4350-b504-d811c31411d4">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
     We introduce adaptive-basis physics-informed neural networks (AB-PINNs), a novel approach to domain decomposition for training PINNs in which existing subdomains dynamically adapt to the intrinsic features of the unknown solution. Drawing inspiration from classical mesh refinement techniques, we also modify the domain decomposition on-the-fly throughout training by introducing new subdomains in regions of high residual loss, thereby providing additional expressive power where the solution of the differential equation is challenging to represent.
      <br><br>
      <a href="https://arxiv.org/abs/2510.08924">[arXiv]</a>
      <a href="https://iopscience.iop.org/article/10.1088/2632-2153/ae8638">[journal]</a>
      <a href="https://github.com/merlresearch/ab-pinns">[code]</a> 
    </td>
  </tr>
</table>

<!-- Add paper entries here using the same table structure. -->

</div>
