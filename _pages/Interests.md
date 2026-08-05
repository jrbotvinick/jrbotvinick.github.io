---
permalink: /Interests/
title: "Interests"
author_profile: true
redirect_from:
  - /md/
  - /markdown.html
---

<style>
.interests-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
  margin: 1.4em 0 2em;
}

.interest-card {
  display: flex;
  flex-direction: column;
  overflow: hidden;
  min-height: 295px;
  border: 1px solid #d8e5ee;
  border-radius: 13px;
  background: #fff;
  color: inherit !important;
  text-decoration: none !important;
  box-shadow: 0 3px 10px rgba(31, 78, 121, 0.08);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.interest-card:hover,
.interest-card:focus {
  color: inherit !important;
  transform: translateY(-4px);
  box-shadow: 0 9px 20px rgba(31, 78, 121, 0.17);
}

.interest-card-image {
  width: 100%;
  height: 170px;
  display: block;
  object-fit: cover;
  background: #edf7fd;
}

.amherst-card .interest-card-image {
  object-position: center;
}

.interest-card-body {
  display: flex;
  flex: 1;
  flex-direction: column;
  padding: 15px 16px 16px;
}

.interest-card-tag {
  margin-bottom: 6px;
  color: #517b99;
  font-size: 0.77em;
  font-weight: 700;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}

.interest-card h2 {
  margin: 0 0 7px;
  color: #1f4e79;
  font-size: 1.1em;
  line-height: 1.22;
}

.interest-card p {
  margin: 0;
  color: #4b5963;
  font-size: 0.91em;
  line-height: 1.4;
}

@media (max-width: 900px) {
  .interests-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 560px) {
  .interests-grid {
    grid-template-columns: 1fr;
  }
}
</style>

Outside of research, I enjoy juggling, playing the cello, and playing ultimate. I have been juggling since I was ten years old, love traveling to festivals and competitions around the world to train with and meet other jugglers, hold several world records, and have won several international competitions.

<div class="interests-grid">

  <a class="interest-card cornell-card"
     href="https://news.cornell.edu/stories/2024/06/going-paris-gold-math-scholar-aids-jugglings-olympic-bid"
     target="_blank"
     rel="noopener noreferrer">
    <img class="interest-card-image"
         src="https://news.cornell.edu/sites/default/files/styles/full_width/public/2024-06/0625_juggling_022_0.jpg?itok=NlkjHjDb"
         alt="Jonah juggling outside Gates Hall at Cornell">
    <div class="interest-card-body">
      <div class="interest-card-tag">Cornell Chronicle</div>
      <h2>Going for Paris Gold</h2>
      <p>Juggling, mathematics, and the World Juggling Federation’s Ultimate Overall Championship.</p>
    </div>
  </a>

  <a class="interest-card"
     href="https://www.youtube.com/watch?v=zc1ub9FYRJk"
     target="_blank"
     rel="noopener noreferrer">
    <img class="interest-card-image"
         src="https://img.youtube.com/vi/zc1ub9FYRJk/maxresdefault.jpg"
         alt="Video thumbnail">
    <div class="interest-card-body">
      <div class="interest-card-tag">Video</div>
      <h2>Juggling Performance</h2>
      <p>A juggling performance video.</p>
    </div>
  </a>

  <a class="interest-card amherst-card"
     href="https://www.amherst.edu/news/magazine/issues/2025-spring/up-in-the-air"
     target="_blank"
     rel="noopener noreferrer">
    <img class="interest-card-image"
         src="{{ '/assets/images/interests/up-in-the-air.png' | relative_url }}"
         alt="Illustration of a juggler among planets">
    <div class="interest-card-body">
      <div class="interest-card-tag">Amherst Magazine</div>
      <h2>Up in the Air</h2>
      <p>On juggling, mathematics, and finding patterns in motion.</p>
    </div>
  </a>

  <a class="interest-card"
     href="https://www.youtube.com/watch?v=-8yZ23_1drA"
     target="_blank"
     rel="noopener noreferrer">
    <img class="interest-card-image"
         src="https://img.youtube.com/vi/-8yZ23_1drA/maxresdefault.jpg"
         alt="Video thumbnail">
    <div class="interest-card-body">
      <div class="interest-card-tag">Video</div>
      <h2>Juggling</h2>
      <p>A short performance video.</p>
    </div>
  </a>

  <a class="interest-card"
     href="https://www.youtube.com/shorts/aAzgaujC2zA"
     target="_blank"
     rel="noopener noreferrer">
    <img class="interest-card-image"
         src="https://img.youtube.com/vi/aAzgaujC2zA/maxresdefault.jpg"
         alt="YouTube Shorts thumbnail">
    <div class="interest-card-body">
      <div class="interest-card-tag">YouTube Short</div>
      <h2>Juggling Clip</h2>
      <p>A brief juggling clip.</p>
    </div>
  </a>

  <a class="interest-card"
     href="https://www.youtube.com/shorts/wr7pLOrZ-c4"
     target="_blank"
     rel="noopener noreferrer">
    <img class="interest-card-image"
         src="https://img.youtube.com/vi/wr7pLOrZ-c4/maxresdefault.jpg"
         alt="YouTube Shorts thumbnail">
    <div class="interest-card-body">
      <div class="interest-card-tag">YouTube Short</div>
      <h2>Juggling Clip</h2>
      <p>A brief juggling clip.</p>
    </div>
  </a>

</div>
