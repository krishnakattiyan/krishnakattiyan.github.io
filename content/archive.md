---
title: "Archive"
description: "All the books, papers, courses, and data on this website—listed in reverse-chronological order."
layout: "archives"
---

<style>
.showcase-section {
  margin: 28px 0 44px;
}

.showcase-heading {
  font-size: var(--h1size);
  font-weight: var(--semibold);
  color: var(--primary);
  margin: 0 0 4px;
}

.showcase-meta {
  font-size: 13px;
  color: var(--secondary);
  margin: 0 0 18px;
  letter-spacing: 0.01em;
}

.showcase-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px;
}

.showcase-card {
  border-radius: 10px;
  overflow: hidden;
  border: 1px solid var(--border);
  background: var(--entry);
  cursor: zoom-in;
  position: relative;
  transition: transform 0.22s ease, box-shadow 0.22s ease;
}

.showcase-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 26px rgba(0, 0, 0, 0.1);
}

.showcase-card img {
  width: 100%;
  height: auto;
  display: block;
}

@media (max-width: 580px) {
  .showcase-grid {
    grid-template-columns: 1fr;
  }
}

/* Lightbox */
.sc-lb {
  position: fixed;
  inset: 0;
  z-index: 9999;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.18s ease;
}

.sc-lb.open {
  opacity: 1;
  pointer-events: auto;
}

.sc-lb-backdrop {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.78);
}

.sc-lb-box {
  position: relative;
  z-index: 1;
  width: min(820px, 92vw);
  max-height: 90vh;
  border-radius: 12px;
  background: var(--entry);
  border: 1px solid var(--border);
  box-shadow: 0 24px 64px rgba(0, 0, 0, 0.45);
  overflow: hidden;
  transform: scale(0.97) translateY(6px);
  transition: transform 0.18s ease;
}

.sc-lb.open .sc-lb-box {
  transform: scale(1) translateY(0);
}

.sc-lb-box img {
  width: 100%;
  max-height: 86vh;
  object-fit: contain;
  display: block;
}

.sc-lb-close {
  position: absolute;
  top: 9px;
  right: 9px;
  z-index: 10;
  width: 30px;
  height: 30px;
  border-radius: 7px;
  border: 1px solid var(--border);
  background: var(--theme);
  color: var(--content);
  font-size: 19px;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  line-height: 1;
  transition: background 0.15s;
}

.sc-lb-close:hover {
  background: var(--code-bg);
}
</style>

<div class="showcase-section">
  <h2 class="showcase-heading">School of Engineering Research Showcase</h2>
  <p class="showcase-meta">Winter 2026 &nbsp;&middot;&nbsp; Santa Clara University</p>
  <div class="showcase-grid">
    <div class="showcase-card" data-src="/showcase1.webp">
      <img src="/showcase1.webp" alt="QoE-Aware RL for HEVC Video Delivery over Wi-Fi 7 Multi-Link Networks" loading="lazy" />
    </div>
    <div class="showcase-card" data-src="/showcase2.webp">
      <img src="/showcase2.webp" alt="Deep RL for Intelligent Traffic Distribution in IEEE 802.11be Multi-Link Operation" loading="lazy" />
    </div>
    <div class="showcase-card" data-src="/showcase3.webp">
      <img src="/showcase3.webp" alt="Semantic Aware User Grouping for 6G NOMA Networks using Q-Learning" loading="lazy" />
    </div>
    <div class="showcase-card" data-src="/showcase4.webp">
      <img src="/showcase4.webp" alt="WIN Lab posters — Semantic NOMA and QoE-Aware RL" loading="lazy" />
    </div>
    <div class="showcase-card" data-src="/showcase5.webp">
      <img src="/showcase5.webp" alt="Derek Chui presenting Semantic Aware User Grouping for 6G NOMA Networks poster" loading="lazy" />
    </div>
    <div class="showcase-card" data-src="/showcase6.webp">
      <img src="/showcase6.webp" alt="WIN Lab team at the School of Engineering Research Showcase" loading="lazy" />
    </div>
  </div>
</div>

<div id="sc-lb" class="sc-lb" aria-hidden="true">
  <div class="sc-lb-backdrop" id="sc-lb-bd"></div>
  <div class="sc-lb-box">
    <button class="sc-lb-close" id="sc-lb-x" aria-label="Close">&times;</button>
    <img id="sc-lb-img" src="" alt="" />
  </div>
</div>

<script>
(function () {
  var lb = document.getElementById('sc-lb');
  var img = document.getElementById('sc-lb-img');

  function open(src, alt) {
    img.src = src;
    img.alt = alt || '';
    lb.classList.add('open');
    lb.setAttribute('aria-hidden', 'false');
    document.body.style.overflow = 'hidden';
  }

  function close() {
    lb.classList.remove('open');
    lb.setAttribute('aria-hidden', 'true');
    document.body.style.overflow = '';
    setTimeout(function () { img.src = ''; }, 200);
  }

  document.querySelectorAll('.showcase-card').forEach(function (card) {
    card.addEventListener('click', function () {
      open(card.dataset.src, card.querySelector('img').alt);
    });
  });

  document.getElementById('sc-lb-x').addEventListener('click', close);
  document.getElementById('sc-lb-bd').addEventListener('click', close);
  document.addEventListener('keydown', function (e) {
    if (e.key === 'Escape') close();
  });
}());
</script>