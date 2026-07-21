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
      <a href="https://arxiv.org/abs/2412.00589v2">[arXiv]</a>
      <a href="https://journals.aps.org/prl/abstract/10.1103/ppys-lx68">[journal]</a>
      <a href="https://github.com/jrbotvinick/Invariant-Measures-in-Time-Delay-Coordinates-for-Unique-Dynamical-System-Identification">[code]</a> 
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h2>Measure Transport</h2>

<!-- Add paper entries here using the same table structure. -->

<h2>Scientific Machine Learning</h2>

<!-- Add paper entries here using the same table structure. -->

</div>
