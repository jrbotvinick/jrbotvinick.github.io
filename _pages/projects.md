---
layout: page
title: Research
permalink: /projects/
---
<div style="max-width: 1100px; margin: 0 auto; padding: 0 32px; box-sizing: border-box;">

<p>Under construction</p>

<h2>Data-Driven Dynamical Systems</h2>

<h3>Data-Adaptive Learning of Dynamical Systems by Matching Transfer Operators and Invariant Measures</h3>

<table border="0" cellpadding="12" cellspacing="0" style="border: none; border-collapse: collapse; width: 100%; font-size: inherit;">
  <tr>
    <td width="38%" valign="top" style="border: none; padding: 12px 20px 12px 0; font-size: inherit;">
      <a href="https://arxiv.org/abs/2607.00391">
        <img width="431" alt="Data-adaptive learning of dynamical systems" src="https://github.com/user-attachments/assets/80677a74-573e-455c-aa91-ebffb7cbaf63">
      </a>
    </td>
    <td width="62%" valign="top" style="border: none; padding: 12px 0 12px 20px; font-size: inherit; line-height: inherit;">
      Trajectory-based learning of dynamical systems is often fragile in the presence of noise,
chaos, or sparse observations, as small pointwise errors can rapidly amplify. We intro-
duce a transition-statistics approach to system identification that learns dynamics by
matching the induced motion of probability mass across a data-adaptive mesh. Given
trajectory data, we build an unstructured partition of state space and approximate the
Perron–Frobenius operator with a regularized Ulam transition matrix. We replace hard
cell indicators with continuous, piecewise-smooth partition-of-unity weights, yielding a
Markov matrix supporting gradient-based optimization with respect to the parameters of
a learned vector field. This enables two related training objectives: matching invariant
measures through the stationary eigenvectors of the transition matrices, and matching the
full transition matrices to capture transport between regions of state space. Numerical
experiments on Lorenz-63, Lorenz-96, and a reduced-order NOAA sea surface temper-
ature forecasting problem show that transition-statistics matching gives more reliable
long-time dynamics than pointwise trajectory matching, particularly under measurement
noise and sparse sampling. The approach provides a robust operator-theoretic alternative
to trajectory-level losses for learning chaotic and partially observed dynamical systems.
      <br><br>
      <a href="https://arxiv.org/abs/2607.00391">[arXiv]</a>
      <!-- <a href="JOURNAL-LINK">[journal]</a> -->
      <!-- <a href="CODE-LINK">[code]</a> -->
      <!-- <a href="SLIDES-LINK">[slides]</a> -->
    </td>
  </tr>
</table>

<h2>Measure Transport</h2>

<!-- Add paper entries here using the same table structure. -->

<h2>Scientific Machine Learning</h2>

<!-- Add paper entries here using the same table structure. -->

</div>
