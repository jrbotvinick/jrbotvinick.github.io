---
permalink: /
title: "Introduction"
excerpt: "Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Postdoctoral Fellow in the [Institute for Foundations of Data Science](https://fds.yale.edu) at Yale University. My research interests lie at the intersection of dynamical systems, optimal transport, scientific machine learning, and inverse problems. I completed my Ph.D. in Applied Mathematics at Cornell University, where I was advised by [Professor Yunan Yang](https://as.cornell.edu/people/yunan-yang). 

My dissertation, *Measure Transport for Data-Driven Dynamical Systems: Theory, Algorithms, and Applications,* focused on using global statistical features of dynamical systems to construct robust surrogate models from limited and corrupt data. During my Ph.D., I was an [NDSEG Fellow](https://ndseg.sysplus.com/) (Sep. 2022 - Aug. 2025) and completed research internships at Argonne National Laboratory and Mitsubishi Electric Research Laboratories. I previously earned B.A.s in Mathematics and Physics at Amherst College in 2021. 

For more information, please navigate to any of the following pages: [Research](https://jrbotvinick.github.io/projects/), [Publications](https://jrbotvinick.github.io/publications/),  [CV](https://jrbotvinick.github.io/CV/), [Talks](https://jrbotvinick.github.io/talks/), [Teaching](https://jrbotvinick.github.io/teaching/), [Awards](https://jrbotvinick.github.io/awards/), and [Outside of Research](https://jrbotvinick.github.io/Interests/). If you are interested in my research or have any questions, please feel free to reach out to me at <code>jonah.botvinick-greenhouse@yale.edu</code>.

<style>
.research-videos {
  margin: 2.25em 0 0;
}

.research-videos h2 {
  margin-bottom: 0.35em;
}

.research-videos > p {
  margin-top: 0;
  color: #555;
}

.research-video-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  margin-top: 1.25em;
}

.research-video-card {
  overflow: hidden;
  background: #f7fbfe;
  border: 1px solid #d9e8f2;
  border-radius: 12px;
  box-shadow: 0 3px 12px rgba(31, 78, 121, 0.08);
}

.research-video-frame {
  aspect-ratio: 16 / 9;
  background: #101820;
}

.research-video-frame video {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.research-video-text {
  padding: 15px 17px 17px;
}

.research-video-text h3 {
  margin: 0 0 0.35em;
  color: #1f4e79;
  font-size: 1.05em;
}

.research-video-text p {
  margin: 0;
  font-size: 0.94em;
  line-height: 1.5;
}

@media (max-width: 700px) {
  .research-video-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<section class="research-videos" aria-labelledby="research-videos-heading">
  <h2 id="research-videos-heading">Research Visualizations</h2>
  <p>A selection of computational demonstrations from my work in scientific machine learning and dynamical systems.</p>

  <div class="research-video-grid">

  <article class="research-video-card">
      <div class="research-video-frame">
        <video controls preload="metadata" playsinline>
          <source src="{{ '/files/ppmm_fish.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support embedded video.
        </video>
      </div>
      <div class="research-video-text">
        <h3>Projection-Pursuit Measure Matching</h3>
        <p>A generative evolution of a distribution toward a complex target geometry.</p>
      </div>
    </article>

  <article class="research-video-card">
      <div class="research-video-frame">
        <video controls preload="metadata" playsinline>
          <source src="{{ '/files/NOAA Reconstruction-2-2.mp4' | relative_url | replace: ' ', '%20' }}" type="video/mp4">
          Your browser does not support embedded video.
        </video>
      </div>
      <div class="research-video-text">
        <h3>NOAA Climate-State Reconstruction</h3>
        <p>Reconstructing global structure from partial observations of climate data.</p>
      </div>
    </article>

  <article class="research-video-card">
      <div class="research-video-frame">
        <video controls preload="metadata" playsinline>
          <source src="{{ '/files/helmholtz.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support embedded video.
        </video>
      </div>
      <div class="research-video-text">
        <h3>Helmholtz Inverse Problem</h3>
        <p>A visualization of computational recovery in a wave-based inverse problem.</p>
      </div>
    </article>

  <article class="research-video-card">
      <div class="research-video-frame">
        <video controls preload="metadata" playsinline>
          <source src="{{ '/files/inversion.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support embedded video.
        </video>
      </div>
      <div class="research-video-text">
        <h3>Measure-Based Inversion</h3>
        <p>Recovering dynamical structure from finite measure-valued observations.</p>
      </div>
    </article>

  </div>
</section>
