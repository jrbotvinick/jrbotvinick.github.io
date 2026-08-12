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
  width: 100%;
  box-sizing: border-box;
  margin: 1.2em 0 1.6em;
  padding: 0.8em 1.1em;
  background: #edf7fd;
  border: 2px solid #1f4e79;
  border-radius: 7px;
  color: #254b67;
  font-size: 1em;
  font-weight: 500;
  line-height: 1.45;
  text-align: left;
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

.news-bubble {
  width: 100%;
  box-sizing: border-box;
  margin: 1.8em 0 1.6em;
  padding: 0.55em 1.1em 0.65em;
  background: #f2f2f2;
  border: 1px solid #111;
  border-radius: 7px;
  color: #111;
  font-size: 0.9em;
  font-weight: 300;
  line-height: 1.45;
}

.news-bubble-title {
  margin: 0 0 0.35em;
  font-weight: 500;
}

.news-list {
  margin: 0;
  padding-left: 1.3em;
}

.news-list li {
  margin-bottom: 0.5em;
}

.news-list li:last-child {
  margin-bottom: 0;
}

.home-news .news-list li:nth-child(n + 8) {
  display: none;
}

.news-archive-link {
  display: inline-block;
  margin-top: 0.55em;
  color: #1f4e79 !important;
  font-weight: 300;
  text-decoration: none;
}

.news-archive-link:hover {
  color: #1f4e79 !important;
  text-decoration: underline;
}

.research-video-carousel {
  margin: 1.8em 0 1.6em;
}

.research-video-carousel-title {
  margin: 0 0 0.65em;
  color: #254b67;
  font-size: 1.1em;
  font-weight: 500;
}

.video-carousel-frame {
  position: relative;
  overflow: hidden;
  border: 1px solid #c9dfea;
  border-radius: 7px;
  background: #111;
}

.video-carousel-slide {
  display: none;
}

.video-carousel-slide.active {
  display: block;
}

.video-carousel-slide video {
  display: block;
  width: 100%;
  max-height: 430px;
  background: #111;
}

.video-carousel-caption {
  margin: 0;
  padding: 0.6em 0.8em;
  background: #edf7fd;
  color: #254b67;
  font-size: 0.9em;
  line-height: 1.4;
}

.video-carousel-controls {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 0.7em;
  margin-top: 0.55em;
}

.video-carousel-button {
  width: 2.25em;
  height: 2.25em;
  padding: 0;
  border: 1px solid #1f4e79;
  border-radius: 50%;
  background: white;
  color: #1f4e79;
  font-size: 1em;
  line-height: 1;
  cursor: pointer;
}

.video-carousel-button:hover {
  background: #edf7fd;
}

.video-carousel-count {
  color: #254b67;
  font-size: 0.9em;
  text-align: center;
}
</style>

I am a Postdoctoral Fellow in the [Institute for Foundations of Data Science](https://fds.yale.edu) at Yale University. I completed my Ph.D. in [Applied Mathematics](https://cam.cornell.edu) at Cornell University, where I was advised by [Professor Yunan Yang](https://as.cornell.edu/people/yunan-yang). During my Ph.D., I was an [NDSEG Fellow](https://ndseg.sysplus.com/) and completed research internships at [Mitsubishi Electric Research Laboratories](https://www.merl.com) and [Argonne National Laboratory](https://www.anl.gov). I previously earned B.A.s in Mathematics and Physics at [Amherst College](https://www.amherst.edu) in 2021.

My research interests lie at the intersection of data-driven dynamical systems, measure transport, scientific machine learning, numerical analysis and inverse problems. In particular, my work explores connections between dynamical systems and measure transport, spanning theory, algorithms, and applications for learning and reconstructing complex systems from noisy, partially observed, or distributional data.

For more information, please navigate to any of the following pages: [Research](https://jrbotvinick.github.io/projects/), [Publications](https://jrbotvinick.github.io/publications/), [CV](https://jrbotvinick.github.io/CV/), [Talks](https://jrbotvinick.github.io/talks/), [Teaching](https://jrbotvinick.github.io/teaching/), [Awards](https://jrbotvinick.github.io/awards/), and [Outside of Research](https://jrbotvinick.github.io/Interests/). If you are interested in my work or have any questions, please feel free to reach out to me at [jonah.botvinick-greenhouse@yale.edu](mailto:jonah.botvinick-greenhouse@yale.edu).

<div class="news-bubble home-news">
  <p class="news-bubble-title">Recent News</p>

  {% include news-list.md %}

  <a class="news-archive-link" href="{{ '/news/' | relative_url }}">News archive</a>
</div>

<div class="research-keywords">
  <p>Research keywords:</p>
  <div class="keyword-list">
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

<div class="research-video-carousel">
  <p class="research-video-carousel-title">Research videos</p>

  <div class="video-carousel-frame">
    <div class="video-carousel-slide active">
      <video controls playsinline preload="auto">
        <source src="{{ '/files/ppmm_fish.mp4' | relative_url }}" type="video/mp4">
      </video>
      <p class="video-carousel-caption">Learning dynamical systems from evolving probability measures.</p>
    </div>

   <div class="video-carousel-slide">
      <video controls playsinline preload="auto">
        <source src="{{ '/files/NOAA%20Reconstruction-2-2.mp4' | relative_url }}" type="video/mp4">
      </video>
      <p class="video-carousel-caption">Reconstructing dynamics from partially observed climate data.</p>
    </div>

   <div class="video-carousel-slide">
      <video controls playsinline preload="auto">
        <source src="{{ '/files/inversion.mp4' | relative_url }}" type="video/mp4">
      </video>
      <p class="video-carousel-caption">Recovering transport maps and vector fields from measure-valued data.</p>
    </div>

  <div class="video-carousel-slide">
      <video controls playsinline preload="auto">
        <source src="{{ '/files/helmholtz.mp4' | relative_url }}" type="video/mp4">
      </video>
      <p class="video-carousel-caption">Inverse problems and scientific machine learning for complex systems.</p>
    </div>
  </div>

  <div class="video-carousel-controls">
    <button class="video-carousel-button video-carousel-prev" type="button" aria-label="Previous video">&#10094;</button>
    <span class="video-carousel-count">1 / 4</span>
    <button class="video-carousel-button video-carousel-next" type="button" aria-label="Next video">&#10095;</button>
  </div>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const slides = Array.from(document.querySelectorAll(".video-carousel-slide"));
  const previousButton = document.querySelector(".video-carousel-prev");
  const nextButton = document.querySelector(".video-carousel-next");
  const count = document.querySelector(".video-carousel-count");
  let currentSlide = 0;

  function showSlide(index, shouldPlay) {
    slides.forEach(function (slide, i) {
      const video = slide.querySelector("video");

      slide.classList.toggle("active", i === index);

      if (i !== index) {
        video.pause();
        video.currentTime = 0;
      }
    });

    currentSlide = (index + slides.length) % slides.length;
    count.textContent = (currentSlide + 1) + " / " + slides.length;

    if (shouldPlay) {
      const activeVideo = slides[currentSlide].querySelector("video");
      activeVideo.play().catch(function () {});
    }
  }

  previousButton.addEventListener("click", function () {
    showSlide(currentSlide - 1, false);
  });

  nextButton.addEventListener("click", function () {
    showSlide(currentSlide + 1, false);
  });

  slides.forEach(function (slide, index) {
    const video = slide.querySelector("video");

    video.addEventListener("ended", function () {
      if (index === currentSlide) {
        showSlide(currentSlide + 1, true);
      }
    });
  });
});
</script>
