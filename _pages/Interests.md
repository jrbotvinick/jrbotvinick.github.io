---
layout: archive
permalink: /Interests/
title: "Interests"
author_profile: true
redirect_from:
  - /md/
  - /markdown.html
---


<p class="interests-intro">
  Outside of research, I enjoy juggling, playing the cello, and playing ultimate.
  I have been juggling since I was ten years old, and have traveled internationally
  for festivals and competitions. I also hold various world records and have won several
  international competitions.
</p>

<div class="interests-grid">

  <a class="interest-card article-card cornell-card"
     href="https://news.cornell.edu/stories/2024/06/going-paris-gold-math-scholar-aids-jugglings-olympic-bid#:~:text=Jonah%20Botvinick%2DGreenhouse%2C%20a%20doctoral,2."
     target="_blank" rel="noopener"
style="background-image: url('https://news.cornell.edu/sites/default/files/styles/full_size/public/2024-06/0625_juggling_004_0.jpg?itok=DQ5N-gqS');">    <div class="card-content">
      <span class="card-tag">Cornell Chronicle</span>
      <h2>Going for Paris Gold</h2>
    </div>
  </a>

  <a class="interest-card video-card"
     href="https://www.youtube.com/watch?v=zc1ub9FYRJk"
     target="_blank" rel="noopener"
     style="background-image: url('https://i.ytimg.com/vi/zc1ub9FYRJk/maxresdefault.jpg');">
    <div class="card-overlay"></div>
    <div class="card-content">
      <span class="card-tag">Chronicle Video</span>
      <span class="play-button">▶</span>
    </div>
  </a>

  <a class="interest-card article-card amherst-card"
     href="https://www.amherst.edu/news/magazine/issues/2025-spring/up-in-the-air"
     target="_blank" rel="noopener"
     style="background-image: url('{{ '/files/siteswap.png' | relative_url }}');">
    <div class="card-overlay"></div>
    <div class="card-content">
      <span class="card-tag">Amherst Magazine</span>
      <h2>Up in the Air</h2>
    </div>
  </a>

  <a class="interest-card video-card"
     href="https://www.youtube.com/watch?v=-8yZ23_1drA"
     target="_blank" rel="noopener"
     style="background-image: url('https://i.ytimg.com/vi/-8yZ23_1drA/maxresdefault.jpg');">
    <div class="card-overlay"></div>
    <div class="card-content">
      <span class="card-tag">Halos Juggling Video</span>
      <span class="play-button">▶</span>
    </div>
  </a>

  <a class="interest-card video-card"
     href="https://www.youtube.com/shorts/aAzgaujC2zA"
     target="_blank" rel="noopener"
     style="background-image: url('https://i.ytimg.com/vi/aAzgaujC2zA/maxresdefault.jpg');">
    <div class="card-overlay"></div>
    <div class="card-content">
      <span class="card-tag">Top 40 Ranking</span>
      <span class="play-button">▶</span>
    </div>
  </a>

  <a class="interest-card video-card"
     href="https://www.youtube.com/shorts/wr7pLOrZ-c4"
     target="_blank" rel="noopener"
     style="background-image: url('https://i.ytimg.com/vi/wr7pLOrZ-c4/maxresdefault.jpg');">
    <div class="card-overlay"></div>
    <div class="card-content">
      <span class="card-tag">WJF Competition Routine</span>
      <span class="play-button">▶</span>
    </div>
  </a>

</div>

<style>
  .interests-intro {
    max-width: 850px;
    margin: 0 0 2.25rem;
    font-size: 1.06em;
    line-height: 1.7;
  }

  
  
  .interests-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 18px;
  }

  .interest-card {
    position: relative;
    display: flex;
    min-height: 270px;
    overflow: hidden;
    border-radius: 12px;
    background-color: #15354f;
    background-position: center;
    background-size: cover;
    color: white !important;
    text-decoration: none !important;
    box-shadow: 0 5px 16px rgba(10, 30, 45, 0.16);
    transition: transform 0.18s ease, box-shadow 0.18s ease;
  }

  .interest-card:hover,
  .interest-card:focus {
    transform: translateY(-5px);
    color: white !important;
    box-shadow: 0 12px 28px rgba(10, 30, 45, 0.25);
  }

  .interest-card:focus {
    outline: 3px solid #5ba7d1;
    outline-offset: 3px;
  }

  .cornell-card {
    background: linear-gradient(135deg, #671c22 0%, #b31b1b 48%, #e0a28d 100%);
  }

  .amherst-card {
    background: linear-gradient(135deg, #361b57 0%, #71529b 53%, #bf9d5c 100%);
  }

  .cornell-card,
  .amherst-card {
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
  }

  .card-overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(180deg, rgba(4, 15, 25, 0.08) 0%, rgba(4, 15, 25, 0.82) 100%);
  }

  .article-card .card-overlay {
    background: linear-gradient(180deg, rgba(0, 0, 0, 0.02) 0%, rgba(0, 0, 0, 0.55) 100%);
  }

  .card-content {
    position: relative;
    z-index: 1;
    display: flex;
    flex: 1;
    flex-direction: column;
    justify-content: flex-end;
    padding: 22px;
  }

  .card-tag {
    align-self: flex-start;
    margin-bottom: 9px;
    padding: 4px 8px;
    border-radius: 5px;
    background: rgba(255, 255, 255, 0.2);
    font-size: 0.72em;
    font-weight: 700;
    letter-spacing: 0.07em;
    text-transform: uppercase;
  }

  .card-content h2 {
    margin: 0;
    color: white;
    font-size: 1.45em;
    line-height: 1.15;
  }

  .play-button {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 44px;
    height: 44px;
    margin-top: 7px;
    border-radius: 50%;
    background: #e6342a;
    color: white;
    font-size: 1em;
    padding-left: 2px;
  }

  @media (max-width: 900px) {
    .interests-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 580px) {
    .interests-grid {
      grid-template-columns: 1fr;
    }

    .interest-card {
      min-height: 240px;
    }
  }
</style>
