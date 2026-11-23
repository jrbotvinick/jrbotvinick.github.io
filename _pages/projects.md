---
layout: archive
title: Research
permalink: /projects/
author_profile: true
---

<style>
#main > .archive:has(> .research-page) {
  padding-right: 0;
}

.research-page {
  --research-blue: #234f75;
  --research-rule: rgba(97, 113, 129, 0.27);
}

.research-page .research-description {
  margin: 0;
  font-size: 0.95rem;
  line-height: 1.65;
}

.research-page .research-index {
  display: flex;
  flex-wrap: wrap;
  gap: 0.25rem 1rem;
  margin: 0.9rem 0 2rem;
  font-size: 0.9rem;
}

.research-page .research-index a {
  color: var(--research-blue);
  text-decoration: underline;
  text-underline-offset: 0.15em;
}

.research-page a:focus-visible {
  outline: 2px solid currentColor;
  outline-offset: 3px;
}

.research-page .research-section + .research-section {
  margin-top: clamp(2.25rem, 5vw, 3.25rem);
}

.research-page .research-section-title,
.research-page .research-project-title {
  margin: 0;
  padding: 0;
  border: 0;
  font-family: inherit;
  font-weight: 600;
}

.research-page .research-section-title {
  font-size: clamp(1.25rem, 1.13rem + 0.5vw, 1.5rem);
  line-height: 1.3;
  scroll-margin-top: 4rem;
}

.research-page .research-section > .research-description {
  margin-top: 0.6rem;
}

.research-page .research-project {
  display: grid;
  grid-template-columns: min(29%, 11rem) minmax(0, 1fr);
  column-gap: clamp(0.85rem, 3vw, 1.75rem);
  align-items: start;
}

.research-page .research-section-title + .research-project,
.research-page .research-description + .research-project {
  margin-top: 1.125rem;
}

.research-page .research-project + .research-project {
  margin-top: 1rem;
  padding-top: 1rem;
  border-top: 1px solid var(--research-rule);
}

.research-page .research-image,
.research-page .research-image img {
  display: block;
}

.research-page .research-image img {
  width: 100%;
  height: auto;
  max-height: 9rem;
  margin: 0;
  object-fit: contain;
  object-position: left top;
}

.research-page .research-project-title {
  font-size: 1rem;
  line-height: 1.4;
  overflow-wrap: anywhere;
}

.research-page .research-authors {
  margin: 0.35rem 0 0;
  font-size: 0.9rem;
  line-height: 1.5;
  overflow-wrap: anywhere;
}

.research-page .research-publication {
  margin: 0.2rem 0 0;
  font-size: 0.85rem;
  line-height: 1.45;
  overflow-wrap: anywhere;
}

.research-page .research-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.2rem 0.9rem;
  margin: 0.35rem 0 0;
  font-size: 0.82rem;
  line-height: 1.3;
}

.research-page .research-links a {
  display: inline-flex;
  align-items: center;
  min-height: 24px;
  font-weight: 500;
}

.research-page .research-links a,
.research-page .research-publication a {
  color: var(--research-blue);
  text-decoration: none;
}

.research-page .research-links a:hover,
.research-page .research-links a:focus-visible,
.research-page .research-publication a:hover,
.research-page .research-publication a:focus-visible {
  text-decoration: underline;
  text-underline-offset: 0.15em;
}
</style>

<div class="research-page">
  <p class="research-description">This page provides an overview of my research in the areas of data-driven dynamical systems, measure transport, and scientific machine learning. While most of my work lies at the intersection of these three fields, you can use the links below to explore projects organized by their primary focus.</p>
  <nav class="research-index" aria-label="Research sections">
    <a href="#data-driven-dynamical-systems">Data-Driven Dynamical Systems</a>
    <a href="#measure-transport">Measure Transport</a>
    <a href="#scientific-machine-learning">Scientific Machine Learning</a>
  </nav>
  <section class="research-section" aria-labelledby="data-driven-dynamical-systems">
    <h2 class="research-section-title" id="data-driven-dynamical-systems">Data-Driven Dynamical Systems</h2>
    <p class="research-description">The primary goal of data-driven dynamical systems involves reconstructing essential properties of complex physical processes from observed measurement data. Depending on the application, this may involve identifying the dynamical laws governing a system’s evolution, reconstructing its full state from partial observations, or estimating quantities such as invariant measures and Lyapunov exponents from data. These tasks are especially challenging when dynamics are chaotic and high-dimensional, and when data is subject to measurement noise, sparse sampling, and uncertainty. Common strategies that seek pointwise agreement between model simulations and the observed data are fragile in these situations. Rather than directly modeling trajectories, my recent work in this area uses global statistical quantities and tools from measure transport to develop robust strategies for learning, predicting, and reconstructing dynamical systems.</p>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2607.00391" aria-label="arXiv — Data-Adaptive Learning of Dynamical Systems by Matching Transfer Operators and Invariant Measures">
        <img src="https://github.com/user-attachments/assets/80028e0f-fbc1-4e70-a111-c56c9be018f2" alt="">
      </a>
      <div>
        <h3 class="research-project-title">Data-Adaptive Learning of Dynamical Systems by Matching Transfer Operators and Invariant Measures</h3>
        <p class="research-authors">Yinong Huang, Jonah Botvinick-Greenhouse, and Yunan Yang</p>
        <p class="research-publication">arXiv preprint (2026) · <a href="https://doi.org/10.48550/arXiv.2607.00391">DOI 10.48550/arXiv.2607.00391</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2607.00391">arXiv</a>
          <a href="https://github.com/Yinonghyn/Parameter-Identification-with-Data-Driven-Cells">Code</a>
        </p>
      </div>
    </article>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2409.08768" aria-label="arXiv — Measure-Theoretic Time-Delay Embedding">
        <img src="https://github.com/user-attachments/assets/1feb4f9d-177d-41f5-883c-480cd3cdb4bb" alt="">
      </a>
      <div>
        <h3 class="research-project-title">Measure-Theoretic Time-Delay Embedding</h3>
        <p class="research-authors">Jonah Botvinick-Greenhouse, Maria Oprea, Romit Maulik, and Yunan Yang</p>
        <p class="research-publication"><cite>Journal of Statistical Physics</cite> (2025) · <a href="https://doi.org/10.1007/s10955-025-03555-1">DOI 10.1007/s10955-025-03555-1</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2409.08768">arXiv</a>
          <a href="https://link.springer.com/article/10.1007/s10955-025-03555-1">Journal</a>
          <a href="https://github.com/jrbotvinick/Measure-Theoretic-Time-Delay-Embedding">Code</a>
          <a href="{{ '/files/MDS24_Slides_JBG.pdf' | relative_url }}" target="_blank" rel="noopener">Slides</a>
        </p>
      </div>
    </article>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2412.00589v2" aria-label="arXiv — Invariant Measures in Time-Delay Coordinates for Unique Dynamical System Identification">
        <img src="https://github.com/user-attachments/assets/d2d92d64-6a8a-4103-8cc8-0871a5c707f1" alt="">
      </a>
      <div>
        <h3 class="research-project-title">Invariant Measures in Time-Delay Coordinates for Unique Dynamical System Identification</h3>
        <p class="research-authors">Jonah Botvinick-Greenhouse, Robert Martin, and Yunan Yang</p>
        <p class="research-publication"><cite>Physical Review Letters</cite> (2025) · <a href="https://doi.org/10.1103/ppys-lx68">DOI 10.1103/ppys-lx68</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2412.00589v2">arXiv</a>
          <a href="https://journals.aps.org/prl/abstract/10.1103/ppys-lx68">Journal</a>
          <a href="https://github.com/jrbotvinick/Invariant-Measures-in-Time-Delay-Coordinates-for-Unique-Dynamical-System-Identification">Code</a>
          <a href="{{ '/files/CSE25_Slides_Botvinick.pdf' | relative_url }}" target="_blank" rel="noopener">Slides</a>
          <a href="{{ '/files/MDS24_Poster_Delay_Coordinate_Measures.pdf' | relative_url }}" target="_blank" rel="noopener">Poster</a>
        </p>
      </div>
    </article>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2301.05193" aria-label="arXiv — Learning Dynamics on Invariant Measures Using PDE-Constrained Optimization">
        <img src="https://github.com/user-attachments/assets/86eb0490-e677-4bee-ab78-37fa9d6329bb" alt="">
      </a>
      <div>
        <h3 class="research-project-title">Learning Dynamics on Invariant Measures Using PDE-Constrained Optimization</h3>
        <p class="research-authors">Jonah Botvinick-Greenhouse, Robert Martin, and Yunan Yang</p>
        <p class="research-publication"><cite>Chaos: An Interdisciplinary Journal of Nonlinear Science</cite> (2023) · <a href="https://doi.org/10.1063/5.0149673">DOI 10.1063/5.0149673</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2301.05193">arXiv</a>
          <a href="https://pubs.aip.org/aip/cha/article/33/6/063152/2900453/Learning-dynamics-on-invariant-measures-using-PDE">Journal</a>
          <a href="https://github.com/jrbotvinick/Learning-Dynamics-on-Invariant-Measures">Code</a>
          <a href="{{ '/files/Jonah.Botvinick-Greenhouse.NNP.Slides.pdf' | relative_url }}" target="_blank" rel="noopener">Slides</a>
          <a href="{{ '/files/Jonah_Botvinick_Learning_Dynamics_on_Invariant_Measures_IPAM_Poster (1).pdf' | relative_url }}" target="_blank" rel="noopener">Poster</a>
        </p>
      </div>
    </article>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2209.05944" aria-label="arXiv — An Unstructured Mesh Approach to Nonlinear Noise Reduction for Coupled Systems">
        <img src="https://github.com/user-attachments/assets/12ec6958-f5e9-49c9-b903-ce61d95d9078" alt="">
      </a>
      <div>
        <h3 class="research-project-title">An Unstructured Mesh Approach to Nonlinear Noise Reduction for Coupled Systems</h3>
        <p class="research-authors">Aaron Kirtland, Jonah Botvinick-Greenhouse, Marianne DeBrito, Megan Osborne, Casey Johnson, Robert S. Martin, Samuel J. Araki, Daniel Q. Eckhardt</p>
        <p class="research-publication"><cite>SIAM Journal on Applied Dynamical Systems</cite> (2023) · <a href="https://doi.org/10.1137/22M152092X">DOI 10.1137/22M152092X</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2209.05944">arXiv</a>
          <a href="https://epubs.siam.org/doi/10.1137/22M152092X">Journal</a>
          <a href="https://github.com/atkirtland/denoising-clean">Code</a>
          <a href="{{ '/files/RIPS_AFRL_poster.pdf' | relative_url }}" target="_blank" rel="noopener">Poster</a>
        </p>
      </div>
    </article>
  </section>
  <section class="research-section" aria-labelledby="measure-transport">
    <h2 class="research-section-title" id="measure-transport">Measure Transport</h2>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2604.07671" aria-label="arXiv — On the Unique Recovery of Transport Maps and Vector Fields from Finite Measure-Valued Data">
        <img src="https://github.com/user-attachments/assets/3359113a-28f3-4f4d-87f8-3c5bf481a391" alt="">
      </a>
      <div>
        <h3 class="research-project-title">On the Unique Recovery of Transport Maps and Vector Fields from Finite Measure-Valued Data</h3>
        <p class="research-authors">Jonah Botvinick-Greenhouse and Yunan Yang</p>
        <p class="research-publication">arXiv preprint (2026) · <a href="https://doi.org/10.48550/arXiv.2604.07671">DOI 10.48550/arXiv.2604.07671</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2604.07671">arXiv</a>
          <a href="https://github.com/jrbotvinick/Transport-Map-and-Vector-Field-Recovery">Code</a>
          <a href="{{ '/files/MSRNE_Slides_Botvinick.pdf' | relative_url }}" target="_blank" rel="noopener">Slides</a>
        </p>
      </div>
    </article>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2304.09663" aria-label="arXiv — Generative modeling of time-dependent densities via optimal transport and projection pursuit">
        <img src="https://github.com/user-attachments/assets/4c718d3b-989a-4270-a851-d1f816b8f68d" alt="">
      </a>
      <div>
        <h3 class="research-project-title">Generative modeling of time-dependent densities via optimal transport and projection pursuit</h3>
        <p class="research-authors">Jonah Botvinick-Greenhouse, Yunan Yang, and Romit Maulik</p>
        <p class="research-publication"><cite>Chaos: An Interdisciplinary Journal of Nonlinear Science</cite> (2023) · <a href="https://doi.org/10.1063/5.0155783">DOI 10.1063/5.0155783</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2304.09663">arXiv</a>
          <a href="https://pubs.aip.org/aip/cha/article/33/10/103108/2915710/Generative-modeling-of-time-dependent-densities">Journal</a>
          <a href="https://github.com/jrbotvinick/Dynamic-PPMM">Code</a>
          <a href="{{ '/files/SIAM_DS_2023.pdf' | relative_url }}" target="_blank" rel="noopener">Slides</a>
          <a href="{{ '/files/Dynamic_PPMM_Poster_Full.pdf' | relative_url }}" target="_blank" rel="noopener">Poster</a>
        </p>
      </div>
    </article>
  </section>
  <section class="research-section" aria-labelledby="scientific-machine-learning">
    <h2 class="research-section-title" id="scientific-machine-learning">Scientific Machine Learning</h2>
    <article class="research-project">
      <a class="research-image" href="https://onepetro.org/ARMAUSRMS/proceedings/ARMA26/ARMA26/D022S043R004/801293" aria-label="Conference — Operator Learning Surrogate Modeling of Hydraulically Fractured Geothermal Injection-Production Systems: A Cornell Case Study">
        <img src="https://github.com/user-attachments/assets/d06cdbfd-559b-48a2-98b9-5bb979a8d975" alt="">
      </a>
      <div>
        <h3 class="research-project-title">Operator Learning Surrogate Modeling of Hydraulically Fractured Geothermal Injection-Production Systems: A Cornell Case Study</h3>
        <p class="research-authors">Yulong Liu, Jonah Botvinick-Greenhouse, Yunan Yang, and Chloé Arson</p>
        <p class="research-publication"><cite>60th U.S. Rock Mechanics/Geomechanics Symposium</cite> (2026) · <a href="https://doi.org/10.56952/ARMA-2026-0354">DOI 10.56952/ARMA-2026-0354</a></p>
        <p class="research-links">
          <a href="https://onepetro.org/ARMAUSRMS/proceedings/ARMA26/ARMA26/D022S043R004/801293">Conference</a>
        </p>
      </div>
    </article>
    <article class="research-project">
      <a class="research-image" href="https://arxiv.org/abs/2510.08924" aria-label="arXiv — AB-PINNs: Adaptive-Basis Physics-Informed Neural Networks for Residual-Driven Domain Decomposition">
        <img src="https://github.com/user-attachments/assets/92c677ba-a197-441e-adf1-8b528bf4c7c6" alt="">
      </a>
      <div>
        <h3 class="research-project-title">AB-PINNs: Adaptive-Basis Physics-Informed Neural Networks for Residual-Driven Domain Decomposition</h3>
        <p class="research-authors">Jonah Botvinick-Greenhouse, Wael H. Ali, Mouhacine Benosman, Saviz Mowlavi</p>
        <p class="research-publication"><cite>Machine Learning: Science and Technology</cite> (2026) · <a href="https://doi.org/10.1088/2632-2153/ae8638">DOI 10.1088/2632-2153/ae8638</a></p>
        <p class="research-links">
          <a href="https://arxiv.org/abs/2510.08924">arXiv</a>
          <a href="https://iopscience.iop.org/article/10.1088/2632-2153/ae8638">Journal</a>
          <a href="https://github.com/merlresearch/ab-pinns">Code</a>
        </p>
      </div>
    </article>
  </section>
</div>
