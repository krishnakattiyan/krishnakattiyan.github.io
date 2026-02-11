---
title: "Senior Design Projects"
description: ""
---
<p style="font-size: 16px; line-height: 1.6; margin-bottom: 20px;">
  I have advised the following Senior Design projects as part of my mentorship at Santa Clara University.
</p>

<style>
.gallery-wrapper {
  position: relative;
  margin-top: 16px;
}

.gallery-scroll {
  display: flex;
  overflow-x: auto;
  gap: 16px;
  padding: 12px 0 8px 4px;
  scroll-snap-type: x mandatory;
  scrollbar-width: thin;
  scrollbar-color: rgba(0,0,0,0.15) transparent;
  -webkit-overflow-scrolling: touch;
}

.gallery-scroll::-webkit-scrollbar { height: 6px; }
.gallery-scroll::-webkit-scrollbar-track { background: transparent; }
.gallery-scroll::-webkit-scrollbar-thumb {
  background-color: rgba(0, 0, 0, 0.15);
  border-radius: 3px;
}

.dark .gallery-scroll::-webkit-scrollbar-thumb {
  background-color: rgba(255, 255, 255, 0.2);
}

.gallery-item {
  flex: 0 0 320px;
  width: 320px;
  flex-shrink: 0;
  scroll-snap-align: start;
  background: var(--entry);
  border-radius: 12px;
  overflow: hidden;
  border: 1px solid var(--border);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.gallery-item:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.12);
}

.gallery-item img {
  width: 100%;
  height: 200px;
  object-fit: contain;
  display: block;
  background: #f5f5f5;
  cursor: zoom-in;
}

.dark .gallery-item img {
  background: #1a1a1a;
}

.gallery-caption {
  padding: 12px 14px;
  color: var(--content);
  font-size: 0.9rem;
  font-weight: 500;
}

@media (max-width: 768px) {
  .gallery-item {
    flex: 0 0 260px;
    width: 260px;
  }
  .gallery-item img { height: 170px; }
}

/* Lightbox */
.sd-lightbox {
  position: fixed;
  inset: 0;
  z-index: 9999;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.2s ease;
}

.sd-lightbox.open {
  opacity: 1;
  pointer-events: auto;
}

.sd-lightbox-backdrop {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.7);
}

.sd-lightbox-content {
  position: relative;
  z-index: 1;
  width: min(900px, 92vw);
  max-height: 86vh;
  padding: 14px;
  border-radius: 14px;
  background: var(--entry);
  border: 1px solid var(--border);
  box-shadow: 0 18px 60px rgba(0, 0, 0, 0.4);
  transform: translateY(10px) scale(0.98);
  transition: transform 0.2s ease;
}

.sd-lightbox.open .sd-lightbox-content {
  transform: translateY(0) scale(1);
}

.sd-lightbox-img {
  width: 100%;
  max-height: 70vh;
  object-fit: contain;
  display: block;
  border-radius: 10px;
}

.sd-lightbox-caption {
  margin-top: 10px;
  color: var(--content);
  font-size: 0.9rem;
}

.sd-lightbox-close {
  position: absolute;
  top: 8px;
  right: 10px;
  width: 34px;
  height: 34px;
  border-radius: 8px;
  border: 1px solid var(--border);
  background: var(--theme);
  color: var(--content);
  cursor: pointer;
  font-size: 20px;
  line-height: 1;
  z-index: 10;
  display: flex;
  align-items: center;
  justify-content: center;
}

.sd-lightbox-close:hover {
  background: var(--code-bg);
}

@media (max-width: 768px) {
  .sd-lightbox-content {
    padding-top: calc(50px + env(safe-area-inset-top));
  }
  .sd-lightbox-close {
    top: calc(10px + env(safe-area-inset-top));
    right: 12px;
  }
}
</style>

<h3 style="margin-top: 8px;">2025</h3>
<div class="gallery-wrapper">
<div class="gallery-scroll">
<div class="gallery-item">
<img src="/SD1.jpeg" loading="lazy" alt="Senior Design Project 1" />
<div class="gallery-caption">EMT Vision</div>
</div>
<div class="gallery-item">
<img src="/SD2.jpeg" loading="lazy" alt="Senior Design Project 2" />
<div class="gallery-caption">Lock And Roll</div>
</div>
</div>
</div>

<div id="sd-lightbox" class="sd-lightbox" aria-hidden="true">
<div class="sd-lightbox-backdrop" data-sd-lightbox-close></div>
<figure class="sd-lightbox-content" role="dialog" aria-modal="true" aria-label="Expanded image">
<button class="sd-lightbox-close" type="button" data-sd-lightbox-close aria-label="Close">&times;</button>
<img class="sd-lightbox-img" alt="" />
<figcaption class="sd-lightbox-caption"></figcaption>
</figure>
</div>

<script>
(function() {
  var lightbox = document.getElementById('sd-lightbox');
  var lbImg = lightbox ? lightbox.querySelector('.sd-lightbox-img') : null;
  var lbCaption = lightbox ? lightbox.querySelector('.sd-lightbox-caption') : null;

  function openLightbox(imgEl) {
    if (!lightbox || !lbImg || !lbCaption) return;
    lbImg.src = imgEl.src;
    lbImg.alt = imgEl.alt || '';
    lbCaption.textContent =
      imgEl.getAttribute('data-caption') ||
      (imgEl.closest('.gallery-item') ? imgEl.closest('.gallery-item').querySelector('.gallery-caption').textContent : '') ||
      '';
    lightbox.classList.add('open');
    lightbox.setAttribute('aria-hidden', 'false');
    document.body.style.overflow = 'hidden';
  }

  function closeLightbox() {
    if (!lightbox || !lbImg) return;
    lightbox.classList.remove('open');
    lightbox.setAttribute('aria-hidden', 'true');
    document.body.style.overflow = '';
    setTimeout(function() { lbImg.src = ''; }, 150);
  }

  document.querySelectorAll('.gallery-item img').forEach(function(img) {
    img.addEventListener('click', function() { openLightbox(img); });
  });

  if (lightbox) {
    lightbox.addEventListener('click', function(e) {
      if (e.target.hasAttribute('data-sd-lightbox-close')) {
        e.preventDefault();
        e.stopPropagation();
        closeLightbox();
      }
    });
  }

  document.addEventListener('keydown', function(e) {
    if (e.key === 'Escape' && lightbox && lightbox.classList.contains('open')) closeLightbox();
  });
})();
</script>

