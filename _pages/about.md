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
  padding: 0.9em 1.1em 1em;
  background: #f2f2f2;
  border: 2px solid #111;
  border-radius: 7px;
  color: #111;
  font-size: 0.96em;
  font-weight: 600;
  line-height: 1.45;
}

.news-bubble-title {
  margin: 0 0 0.55em;
  color: #111;
  font-size: 1.12em;
  font-weight: 700;
}

.news-list {
  margin: 0;
  padding-left: 1.25em;
}

.news-list li {
  margin: 0 0 0.42em;
  padding-left: 0.1em;
}

.news-list li:last-child {
  margin-bottom: 0;
}

.news-list a {
  color: #111;
  text-decoration: underline;
  text-decoration-thickness: 1px;
  text-underline-offset: 2px;
}

.news-date {
  color: #333;
  font-weight: 500;
}

.news-archive-link {
  display: inline-block;
  margin-top: 0.85em;
  padding: 0.35em 0.7em;
  border: 1px solid #111;
  border-radius: 4px;
  color: #111 !important;
  font-weight: 600;
  line-height: 1.2;
  text-decoration: none !important;
}

.news-archive-link:hover {
  background: #e2e2e2;
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

I am a Postdoctoral Fellow in the [Institute for Foundations of Data Science](https://fds.yale.edu) at Yale University. I completed my Ph.D. in [Applied Mathematics](https://cam.cornell.edu) at Cornell University, where I was advised by [Professor Yunan Yang](https://as.cornell.edu/people/yunan-yang). During my Ph.D., I was an [NDSEG Fellow](https://ndseg.sysplus.com/) and completed research internships at [Mitsubishi Electric Research Laboratories](https://www.merl.com) and [Argonne National Laboratory](https://www.anl.gov). I previously earned B.A.s in Mathematics and Physics at [Amherst College](https://www.amherst.edu) in 2021. 

My research interests lie at the intersection of data-driven dynamical systems, measure transport, scientific machine learning, numerical analysis and inverse problems. In particular, my work explores connections between dynamical systems and measure transport, spanning theory, algorithms, and applications for learning and reconstructing complex systems from noisy, partially observed, or distributional data.  

For more information, please navigate to any of the following pages: [Research](https://jrbotvinick.github.io/projects/), [Publications](https://jrbotvinick.github.io/publications/), [CV](https://jrbotvinick.github.io/CV/), [Talks](https://jrbotvinick.github.io/talks/), [Teaching](https://jrbotvinick.github.io/teaching/), [Awards](https://jrbotvinick.github.io/awards/), and [Outside of Research](https://jrbotvinick.github.io/Interests/). If you are interested in my work or have any questions, please feel free to reach out to me at [jonah.botvinick-greenhouse@yale.edu](mailto:jonah.botvinick-greenhouse@yale.edu).

<div class="news-bubble home-news">
  <p class="news-bubble-title">News</p>

  {% include news-list.md %}

  <a class="news-archive-link" href="{{ '/news/' | relative_url }}">
    View all news
  </a>
</div>
