---
permalink: /
excerpt: "Introduction"
title: "Introduction"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.research-focus {
  float: right;
  width: 300px;
  max-width: 40%;
  margin: 0.15em 0 0.8em 1.35em;
  padding: 0.65em 0.8em;
  background: #edf7fd;
  border: 2px solid #1f4e79;
  border-radius: 7px;
  color: #254b67;
  font-size: 1em;
  font-weight: 500;
  line-height: 1.45;
}

.research-keywords {
  margin: 1.35em 0 1.6em;
}

.research-keywords p {
  margin: 0 0 0.65em;
}

.keyword-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45em 0.5em;
}

.keyword-list span {
  display: inline-block;
  padding: 0.3em 0.6em;
  background: #edf7fd;
  border: 1px solid #c9dfea;
  border-radius: 5px;
  color: #254b67;
  font-size: 0.9em;
  line-height: 1.25;
}

@media (max-width: 600px) {
  .research-focus {
    float: none;
    width: auto;
    max-width: none;
    margin: 0 0 1em;
  }
}
</style>

<div class="research-focus">
  My research explores connections between dynamical systems and measure transport, spanning theory, algorithms, and applications for learning and reconstructing complex systems from noisy, partially observed, or distributional data.
</div>

Welcome! I am a Postdoctoral Fellow in the [Institute for Foundations of Data Science](https://fds.yale.edu) at Yale University. My research interests lie at the intersection of data-driven dynamical systems, measure transport, scientific machine learning, numerical analysis and inverse problems. I completed my Ph.D. in Applied Mathematics at Cornell University, where I was advised by [Professor Yunan Yang](https://as.cornell.edu/people/yunan-yang). My dissertation was titled *Measure Transport for Data-Driven Dynamical Systems: Theory, Algorithms, and Applications.* During my Ph.D., I was an [NDSEG Fellow](https://ndseg.sysplus.com/) and completed research internships at Mitsubishi Electric Research Laboratories and Argonne National Laboratory. I previously earned B.A.s in Mathematics and Physics at Amherst College in 2021.

<div style="clear: both;"></div>

<div class="research-keywords">
  <p>Here are some keywords that commonly arise in my work:</p>

  <div class="keyword-list" aria-label="Research keywords">
    <span>Data-driven dynamical systems</span>
    <span>Optimal transport</span>
    <span>Measure transport</span>
    <span>Inverse problems</span>
    <span>Ergodic theory</span>
    <span>Invariant measures</span>
    <span>Perron–Frobenius operators</span>
    <span>Koopman operators</span>
    <span>Time-delay embedding</span>
    <span>Finite-data identifiability</span>
    <span>PDE inverse problems</span>
    <span>Generative models</span>
    <span>System identification</span>
    <span>State reconstruction</span>
    <span>Fokker–Planck equations</span>
    <span>Operator learning</span>
  </div>
</div>

Here are some video illustrations from my computational work:

<style>
.video-carousel {
  margin: 1em 0 1.9em;
}

.video-carousel-stage {
  display: grid;
  grid-template-columns: auto minmax(0, 1fr) auto;
  align-items: center;
  gap: 0.7em;
}

.video-carousel-main {
  min-width: 0;
  text-align: center;
}

.video-carousel-main video {
  display: block;
  width: auto;
  max-width: 100%;
  max-height: 460px;
  margin: 0 auto;
  border-radius: 6px;
}

.video-carousel-arrow {
  width: 2.15em;
  height: 2.15em;
  padding: 0;
  border: 1px solid #c9dfea;
  border-radius: 50%;
  background: #edf7fd;
  color: #1f4e79;
  font-size: 1.3em;
  line-height: 1;
  cursor: pointer;
}

.video-carousel-arrow:hover,
.video-carousel-arrow:focus {
  background: #dceef8;
  border-color: #1f4e79;
}

.video-carousel-caption {
  margin: 0.7em auto 0;
  max-width: 720px;
  color: #4a4a4a;
  font-size: 0.95em;
  line-height: 1.45;
}

.video-carousel-count {
  margin-top: 0.65em;
  text-align: center;
  color: #707070;
  font-size: 0.82em;
}

@media (max-width: 600px) {
  .video-carousel-stage {
    gap: 0.35em;
  }

  .video-carousel-main video {
    width: 100%;
    max-height: none;
  }
}
</style>

<div class="video-carousel" aria-label="Research videos">
  <div class="video-carousel-stage">
    <button class="video-carousel-arrow" id="video-previous" type="button"
      aria-label="Show previous video">←</button>

    <div class="video-carousel-main">
      <video id="research-video" controls playsinline preload="metadata">
        Your browser does not support embedded videos.
      </video>
      <div class="video-carousel-caption" id="video-caption"></div>
      <div class="video-carousel-count" id="video-count"></div>
    </div>

    <button class="video-carousel-arrow" id="video-next" type="button"
      aria-label="Show next video">→</button>
  </div>
</div>

<script>
(function () {
  const videos = [
    {
      src: "/files/ppmm_fish.mp4",
      description: "Modeling fish schooling dynamics using projection pursuit optimal transport."
    },
    {
      src: "/files/NOAA%20Reconstruction-2-2.mp4",
      description: "Measure-based state reconstruction of the NOAA SST dataset is more robust to noise and data sparsity than standard pointwise reconstruction."
    },
    {
      src: "/files/inversion.mp4",
      description: "Learning the vector field of the van der Pol oscillator by aligning simulated and observed invariant measures in a PDE-constrained optimization framework."
    },
    {
      src: "/files/helmholtz.mp4",
      description: "Borrowing ideas from classical mesh refinement, Adaptive-Basis PINNs (AB-PINNs) provide localized and adaptive approximation capabilities for learning the solution of multiscale differential equations."
    }
  ];

  let current = 0;
  const mainVideo = document.getElementById("research-video");
  const caption = document.getElementById("video-caption");
  const count = document.getElementById("video-count");

  function showFirstFrame(video) {
    video.addEventListener("loadeddata", function () {
      video.currentTime = 0.01;
    }, { once: true });
  }

  function showVideo(index) {
    current = (index + videos.length) % videos.length;

    mainVideo.pause();
    mainVideo.src = videos[current].src;
    showFirstFrame(mainVideo);
    mainVideo.load();

    caption.textContent = videos[current].description;
    count.textContent = (current + 1) + " / " + videos.length;
  }

  document.getElementById("video-previous").addEventListener("click", function () {
    showVideo(current - 1);
  });

  document.getElementById("video-next").addEventListener("click", function () {
    showVideo(current + 1);
  });

  showVideo(0);
})();
</script>

For more information, please navigate to any of the following pages: [Research](https://jrbotvinick.github.io/projects/), [Publications](https://jrbotvinick.github.io/publications/), [CV](https://jrbotvinick.github.io/CV/), [Talks](https://jrbotvinick.github.io/talks/), [Teaching](https://jrbotvinick.github.io/teaching/), [Awards](https://jrbotvinick.github.io/awards/), and [Outside of Research](https://jrbotvinick.github.io/Interests/). If you are interested in my work or have any questions, please feel free to reach out to me at [jonah.botvinick-greenhouse@yale.edu](mailto:jonah.botvinick-greenhouse@yale.edu).
