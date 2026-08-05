---
layout: archive
permalink: /CV/
author_profile: true
---

<div class="cv-preview">
  <iframe
    src="{{ '/files/CV.pdf' | relative_url }}#view=FitH"
    title="Curriculum Vitae">
  </iframe>

  <p>
    <a class="cv-open-button"
       href="{{ '/files/CV.pdf' | relative_url }}"
       target="_blank"
       rel="noopener">
      Open CV in a new tab
    </a>
  </p>
</div>

<style>
  .cv-preview {
    margin-top: 1.5em;
  }

  .cv-preview iframe {
    display: block;
    width: 100%;
    height: 1000px;
    border: 1px solid #d1d5db;
    border-radius: 10px;
    box-shadow: 0 5px 18px rgba(0, 0, 0, 0.12);
  }

  .cv-open-button {
    display: inline-block;
    padding: 9px 14px;
    background: #edf7fd;
    border-radius: 8px;
    color: #1f4e79;
    text-decoration: none !important;
    font-weight: 600;
  }
</style>
