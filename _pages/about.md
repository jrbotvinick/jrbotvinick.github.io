---
permalink: /
excerpt: "Introduction"
title: "Introduction"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Postdoctoral Fellow in the [Institute for Foundations of Data Science](https://fds.yale.edu) at Yale University. My research interests lie at the intersection of data-driven dynamical systems, measure transport, scientific machine learning, numerical analysis and inverse problems. I completed my Ph.D. in Applied Mathematics at Cornell University, where I was advised by [Professor Yunan Yang](https://as.cornell.edu/people/yunan-yang).

<div style="margin: 1.5em 0; padding: 1em 1.2em; background: #edf7fd; border-left: 4px solid #1f4e79; border-radius: 7px; color: #253746; line-height: 1.55;">
  My research explores connections between dynamical systems and measure transport to develop theoretical and computational frameworks for modeling complex physical and biological processes from limited and corrupt data.
</div>

My dissertation, *Measure Transport for Data-Driven Dynamical Systems: Theory, Algorithms, and Applications,* focused on using global statistical features of dynamical systems to construct robust surrogate models from limited and corrupt data. During my Ph.D., I was an [NDSEG Fellow](https://ndseg.sysplus.com/) and completed research internships at Argonne National Laboratory and Mitsubishi Electric Research Laboratories. I previously earned B.A.s in Mathematics and Physics at Amherst College in 2021.

For more information, please navigate to any of the following pages: [Research](https://jrbotvinick.github.io/projects/), [Publications](https://jrbotvinick.github.io/publications/), [CV](https://jrbotvinick.github.io/CV/), [Talks](https://jrbotvinick.github.io/talks/), [Teaching](https://jrbotvinick.github.io/teaching/), [Awards](https://jrbotvinick.github.io/awards/), and [Outside of Research](https://jrbotvinick.github.io/Interests/). If you are interested in my research or have any questions, please feel free to reach out to me at [jonah.botvinick-greenhouse@yale.edu](mailto:jonah.botvinick-greenhouse@yale.edu).

<style>
.video-gallery {
  margin: 2.5em 0;
}

.video-gallery figure {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 0 0 2.5em;
}

.video-gallery video {
  display: block;
  width: auto;
  height: 360px;
  max-width: 100%;
}

.video-gallery figcaption {
  max-width: 720px;
  margin-top: 0.65em;
  color: #555;
  font-size: 0.94em;
  line-height: 1.45;
  text-align: center;
}

@media (max-width: 700px) {
  .video-gallery video {
    height: auto;
    width: 100%;
  }
}
</style>

<div class="video-gallery">

  <figure>
    <video controls preload="metadata" playsinline>
      <source src="{{ '/files/ppmm_fish.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>
      Projection-pursuit measure matching evolves a distribution toward a complex target geometry.
    </figcaption>
  </figure>

  <figure>
    <video controls preload="metadata" playsinline>
      <source src="{{ '/files/NOAA Reconstruction-2-2.mp4' | relative_url | replace: ' ', '%20' }}" type="video/mp4">
    </video>
    <figcaption>
      A reconstruction of global climate-state structure from partial NOAA observations.
    </figcaption>
  </figure>

  <figure>
    <video controls preload="metadata" playsinline>
      <source src="{{ '/files/helmholtz.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>
      A computational reconstruction for a Helmholtz inverse problem.
    </figcaption>
  </figure>

  <figure>
    <video controls preload="metadata" playsinline>
      <source src="{{ '/files/inversion.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>
      Recovering dynamical structure from finite measure-valued observations.
    </figcaption>
  </figure>

</div>
