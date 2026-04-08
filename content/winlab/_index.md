---
title: "WINLAB"
description: "Wireless Intelligent Networks (WIN) Lab at Santa Clara University"
---

<div style="display: flex; flex-direction: column; align-items: center; gap: 14px; margin-bottom: 28px;">
  <img src="/PNG_Vertical - Color.png" alt="WIN Lab Logo" style="width: 320px; height: 320px; object-fit: contain; border-radius: 16px;" />
  <a href="https://www.linkedin.com/company/scu-win-lab/" target="_blank" rel="noopener noreferrer" style="display: inline-flex; align-items: center; gap: 8px; padding: 8px 18px; background-color: #0A66C2; color: #fff; border-radius: 20px; text-decoration: none; font-size: 13px; font-weight: 600; letter-spacing: 0.02em; transition: background-color 0.2s ease, box-shadow 0.2s ease; box-shadow: 0 2px 8px rgba(10,102,194,0.25);" onmouseover="this.style.backgroundColor='#004182';this.style.boxShadow='0 4px 14px rgba(10,102,194,0.4)';" onmouseout="this.style.backgroundColor='#0A66C2';this.style.boxShadow='0 2px 8px rgba(10,102,194,0.25)';">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="#fff"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
    Follow us on LinkedIn
  </a>
</div>

<p style="font-size: 14px; line-height: 1.8;">
  The <strong>Wireless Intelligent Networks (WIN) Lab</strong> at Santa Clara University explores next-generation wireless systems that adapt, learn, and make intelligent decisions — with a focus on efficient resource allocation, smarter access protocols, and user-centered performance.
</p>

<p style="font-size: 14px; line-height: 1.8;">
We focus on technologies like WiFi 7, 5G/6G, and intelligent multiple access protocols—including NOMA, RSMA, and 6TiSCH — alongside research in QoE/QoS optimization, machine learning techniques in wireless network, network economics, wireless multimedia and cognitive radio.
</p>

<p style="font-size: 14px; line-height: 1.8;">
Whether you’re passionate about future wireless networks, curious about how machine learning can shape next gen communications, or eager to build real-world impact through research — the WIN Lab is a collaborative space where your ideas matter, your growth is supported, and your work can shape the networks of tomorrow.
</p>

<style>
.toggle-wrapper {
  display: flex;
  justify-content: center;
  margin-bottom: 20px;
}

.toggle-buttons {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.toggle-buttons button {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  border-radius: 8px;
  background-color: #e0e0e0;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.toggle-buttons button:hover {
  background-color: #ffd580; /* orange highlight on hover */
}

.toggle-buttons button.active {
  background-color: #ffd580;
  font-weight: bold;
}

.toggle-section {
  display: none;
}
.toggle-section.active {
  display: block;
}
 
.team-section {
  margin-top: 40px;
}

.team-section h3 {
  text-align: center;
  font-size: 18px;
  margin-bottom: 20px;
  color: #333;
  position: relative;
}

.team-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  justify-content: center;
  margin-bottom: 40px;
}

.member-card {
  background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
  border-radius: 12px;
  padding: 20px 28px;
  min-width: 200px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: all 0.3s ease;
  border: 1px solid rgba(0,0,0,0.06);
  display: flex;
  flex-direction: column;
  align-items: center;
}

.team-grid-2col {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  justify-content: center;
  margin-bottom: 40px;
}

.team-grid-2col .member-card {
  width: calc(50% - 40px);
  min-width: 200px;
  max-width: 280px;
}

.member-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(244, 162, 97, 0.25);
  border-color: #f4a261;
}

.member-card a {
  text-decoration: none;
  border-bottom: none !important;
  box-shadow: none !important;
}

.alumni-grid a {
  border-bottom: none !important;
  box-shadow: none !important;
}

.member-name {
  font-weight: 600;
  font-size: 16px;
  color: #2d3436;
  margin-bottom: 6px;
}

.member-card a .member-name {
  color: #f4a261;
  transition: color 0.2s ease;
}

.member-card a:hover .member-name {
  color: #e07b3c;
}

.member-photo {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 12px;
  border: 3px solid #f0f0f0;
  transition: border-color 0.3s ease;
}

.member-card:hover .member-photo {
  border-color: #f4a261;
}

.member-role {
  font-size: 13px;
  color: #636e72;
  font-weight: 400;
}

.alumni-grid {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 12px;
  margin-bottom: 40px;
}

.alumni-chip {
  background: #f1f2f6;
  border-radius: 20px;
  padding: 10px 20px;
  font-size: 14px;
  color: #555;
  transition: all 0.2s ease;
  border: 1px solid transparent;
}

.alumni-chip:hover {
  background: #fff;
  border-color: #ddd;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}

.alumni-name {
  font-weight: 500;
  color: #333;
}

.alumni-dest {
  font-size: 12px;
  color: #888;
  margin-top: 3px;
}

</style>

<div class="toggle-wrapper">
  <div class="toggle-buttons">

   <button id="btn-prospective" class="active" onclick="showSection('prospective')">Prospective Students</button>

  <button id="btn-research"  onclick="showSection('research')">Current Research</button>

  <button id="btn-people" onclick="showSection('people')">Meet the Team</button>

    
  </div>
</div>

<div id="research" class="toggle-section">

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
.win-lightbox {
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

.win-lightbox.open {
  opacity: 1;
  pointer-events: auto;
}

.win-lightbox-backdrop {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.7);
}

.win-lightbox-content {
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

.win-lightbox.open .win-lightbox-content {
  transform: translateY(0) scale(1);
}

.win-lightbox-img {
  width: 100%;
  max-height: 70vh;
  object-fit: contain;
  display: block;
  border-radius: 10px;
}

.win-lightbox-caption {
  margin-top: 10px;
  color: var(--content);
  font-size: 0.9rem;
}

.win-lightbox-close {
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

.win-lightbox-close:hover {
  background: var(--code-bg);
}

@media (max-width: 768px) {
  .win-lightbox-content {
    padding-top: calc(50px + env(safe-area-inset-top));
  }
  .win-lightbox-close {
    top: calc(10px + env(safe-area-inset-top));
    right: 12px;
  }
}
</style>

<h3 style="margin-top: 8px;">Semantic Aware User Grouping for 6G NOMA</h3>
<p style="font-size: 14px; line-height: 1.8;">
Method for grouping users in 6G Non-Orthogonal Multiple Access (NOMA) networks that accounts not only for signal strength and interference, but also for how important each user's data is to transmit accurately (semantic importance). The approach aims to improve overall network efficiency and user experience by prioritizing the most meaningful information while maintaining strong performance across all connected users.
</p>
<div class="gallery-wrapper">
<div class="gallery-scroll">
<div class="gallery-item">
<img src="/win0.png" loading="lazy" data-caption="6G Semantic Q Learning NOMA" data-link="https://drive.google.com/file/d/12F5-P4dct3hl-_B_vAe0MAUBt1dEbzD7/view?usp=sharing" alt="6G Semantic Q Learning NOMA" />
<div class="gallery-caption">6G Semantic Q Learning NOMA</div>
</div>
<div class="gallery-item">
<img src="/win2.png" loading="lazy" data-caption="Click the image for project details." data-link="https://drive.google.com/file/d/1TZ-hggjblw8D4OI7lmwQi5GvmUcgvjQ7/view?usp=sharing" alt="Semantic Greedy NOMA Grouping" />
<div class="gallery-caption">Semantic Greedy NOMA Grouping</div>
</div>
<div class="gallery-item">
<img src="/win1.png" loading="lazy" data-caption="Click the image for project details." data-link="https://drive.google.com/file/d/1C5jopMzgl9t2hgAJOYhTnA18xQ7LQbZU/view?usp=sharing" alt="State of the Field Poster" />
<div class="gallery-caption">State of the Field Poster</div>
</div>
<div class="gallery-item">
<img src="/win3.png" loading="lazy" data-caption="Click the image for project details." data-link="https://drive.google.com/file/d/1sKTumPeglMpADQQpm-wT4cGTqHteR7Kh/view?usp=sharing" alt="Traditional vs Semantic User Grouping" />
<div class="gallery-caption">Traditional vs Semantic User Grouping</div>
</div>
<div class="gallery-item">
<img src="/win4.png" loading="lazy" data-caption="Click the image for project details." data-link="https://drive.google.com/file/d/1bnmEY68AvoT-BOUoi62nJNvAtt0XLwHg/view?usp=sharing" alt="NOMA Algorithm Comparison" />
<div class="gallery-caption">NOMA Algorithm Comparison</div>
</div>
</div>
</div>
<div id="win-lightbox" class="win-lightbox" aria-hidden="true">
<div class="win-lightbox-backdrop" data-win-lightbox-close></div>
<figure class="win-lightbox-content" role="dialog" aria-modal="true" aria-label="Expanded image">
<button class="win-lightbox-close" type="button" data-win-lightbox-close aria-label="Close">&times;</button>
<img class="win-lightbox-img" alt="" />
<figcaption class="win-lightbox-caption"></figcaption>
</figure>
</div>

<script>
(function() {
  var lightbox = document.getElementById('win-lightbox');
  var lbImg = lightbox ? lightbox.querySelector('.win-lightbox-img') : null;
  var lbCaption = lightbox ? lightbox.querySelector('.win-lightbox-caption') : null;
  var activeHref = null;
  var armNavigateAt = 0;

  function openLightbox(imgEl) {
    if (!lightbox || !lbImg || !lbCaption) return;
    lbImg.src = imgEl.src;
    lbImg.alt = imgEl.alt || '';
    lbCaption.textContent =
      imgEl.getAttribute('data-caption') ||
      (imgEl.closest('.gallery-item') ? imgEl.closest('.gallery-item').querySelector('.gallery-caption').textContent : '') ||
      '';
    activeHref = imgEl.getAttribute('data-link') || null;
    armNavigateAt = Date.now() + 400;
    lightbox.classList.add('open');
    lightbox.setAttribute('aria-hidden', 'false');
    document.body.style.overflow = 'hidden';
  }

  function closeLightbox() {
    if (!lightbox || !lbImg) return;
    lightbox.classList.remove('open');
    lightbox.setAttribute('aria-hidden', 'true');
    document.body.style.overflow = '';
    activeHref = null;
    setTimeout(function() { lbImg.src = ''; }, 150);
  }

  document.querySelectorAll('.gallery-item img').forEach(function(img) {
    img.addEventListener('click', function() { openLightbox(img); });
  });

  if (lbImg) {
    lbImg.addEventListener('click', function(e) {
      if (!lightbox.classList.contains('open')) return;
      if (!activeHref) return;
      if (Date.now() < armNavigateAt) return;
      e.preventDefault();
      e.stopPropagation();
      window.open(activeHref, '_blank', 'noopener,noreferrer');
    });
  }

  if (lightbox) {
    lightbox.addEventListener('click', function(e) {
      if (e.target.hasAttribute('data-win-lightbox-close')) {
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

<h3 style="margin-top: 36px;">Wi-Fi 7 Multi-Link Scheduling with Reinforcement Learning</h3>
<p style="font-size: 14px; line-height: 1.8;">
Wi-Fi 7 Multi-Link Operation project that uses simulation plus reinforcement learning to decide which band (2.4/5/6 GHz) should carry each uplink packet or video frame as conditions change (signal quality, congestion, interference, etc). Improves what users actually feel, lower delay for interactive traffic, and fewer stalls/missed deadlines for HEVC (H.265) streaming. Outperforms fixed band and simple round robin/heuristic scheduling under challenging network conditions.
</p>
<div style="display: flex; gap: 16px; justify-content: center; margin-top: 16px; margin-bottom: 8px; flex-wrap: wrap;">
  <div style="width: min(340px, 100%); background: var(--entry); border-radius: 12px; overflow: hidden; border: 1px solid var(--border); transition: transform 0.3s ease, box-shadow 0.3s ease;" onmouseover="this.style.transform='translateY(-4px)';this.style.boxShadow='0 6px 20px rgba(0,0,0,0.12)'" onmouseout="this.style.transform='';this.style.boxShadow=''">
    <img src="/dql1.png" loading="lazy" data-caption="DQL Wi-Fi 7 Band Scheduler" alt="DQL Wi-Fi 7 Band Scheduler" style="width: 100%; height: 180px; display: block; background: #f5f5f5; object-fit: contain; cursor: zoom-in;" onclick="(function(img){var lb=document.getElementById('win-lightbox');var lbImg=lb.querySelector('.win-lightbox-img');var lbCap=lb.querySelector('.win-lightbox-caption');lbImg.src=img.src;lbImg.alt=img.alt;lbCap.textContent=img.getAttribute('data-caption')||'';lb.classList.add('open');lb.setAttribute('aria-hidden','false');document.body.style.overflow='hidden';})(this)" />
    <div style="padding: 10px 14px; color: var(--content); font-size: 0.85rem; font-weight: 500;">DQL Wi-Fi 7 Band Scheduler</div>
  </div>
  <div style="width: min(340px, 100%); background: var(--entry); border-radius: 12px; overflow: hidden; border: 1px solid var(--border); transition: transform 0.3s ease, box-shadow 0.3s ease;" onmouseover="this.style.transform='translateY(-4px)';this.style.boxShadow='0 6px 20px rgba(0,0,0,0.12)'" onmouseout="this.style.transform='';this.style.boxShadow=''">
    <img src="/qoe1.png" loading="lazy" data-caption="QoE-Aware Wi-Fi 7 Scheduling" alt="QoE-Aware Wi-Fi 7 Scheduling" style="width: 100%; height: 180px; display: block; background: #f5f5f5; object-fit: contain; cursor: zoom-in;" onclick="(function(img){var lb=document.getElementById('win-lightbox');var lbImg=lb.querySelector('.win-lightbox-img');var lbCap=lb.querySelector('.win-lightbox-caption');lbImg.src=img.src;lbImg.alt=img.alt;lbCap.textContent=img.getAttribute('data-caption')||'';lb.classList.add('open');lb.setAttribute('aria-hidden','false');document.body.style.overflow='hidden';})(this)" />
    <div style="padding: 10px 14px; color: var(--content); font-size: 0.85rem; font-weight: 500;">QoE-Aware Wi-Fi 7 Scheduling</div>
  </div>
</div>

</div>


<div id="people" class="toggle-section">

<!-- UNDERGRADUATE STUDENTS -->
<div class="team-section">
  <h3>Undergraduate Students</h3>
  <div class="team-grid">
    <div class="member-card">
      <a href="https://derekchui.com/" target="_blank">
        <img src="/Derek.png" alt="Derek Chui" class="member-photo">
        <div class="member-name">Derek Chui</div>
        <div class="member-role">B.S. Student</div>
      </a>
    </div>
  </div>
</div>

<!-- GRADUATE STUDENTS -->
<div class="team-section">
  <h3>Graduate Students</h3>
  <div class="team-grid-2col">
    <div class="member-card">
      <a href="https://www.linkedin.com/in/zachary-common/" target="_blank">
        <img src="/zack.webp" alt="Zack Common" class="member-photo">
        <div class="member-name">Zack Common</div>
        <div class="member-role">M.S. Student</div>
      </a>
    </div>
    <div class="member-card">
      <a href="https://www.linkedin.com/in/briantrinh00/" target="_blank">
        <img src="/Brian.PNG" alt="Brian Trinh" class="member-photo">
        <div class="member-name">Brian Trinh</div>
        <div class="member-role">M.S. Student</div>
      </a>
    </div>
    <div class="member-card">
      <a href="https://www.linkedin.com/in/duyngoph/" target="_blank">
        <img src="/tom.webp" alt="Tom Ngo" class="member-photo">
        <div class="member-name">Tom Ngo</div>
        <div class="member-role">M.S. Student</div>
      </a>
    </div>
    <div class="member-card">
      <a href="https://www.linkedin.com/in/khushi-savaliya/" target="_blank">
        <img src="/khushi.webp" alt="Khushi Savaliya" class="member-photo">
        <div class="member-name">Khushi Savaliya</div>
        <div class="member-role">M.S. Student</div>
      </a>
    </div>
  </div>
</div>

<!-- ALUMNI -->
<div class="team-section">
  <h3>Alumni</h3>
  <div class="alumni-grid">
    <a href="https://www.linkedin.com/in/mrudhula-lokesh-173b1a1aa/" target="_blank" style="text-decoration: none;">
      <div class="alumni-chip">Mrudhula Lokesh - Qualcomm</div>
    </a>
    <a href="https://www.linkedin.com/in/samarth-kulkarni-a97891189/" target="_blank" style="text-decoration: none;">
      <div class="alumni-chip">Samarth Kulkarni - Piedmont Global Language Systems (PGLS)</div>
    </a>
  </div>
</div>

</div>


<div id="prospective" class="toggle-section active">
  <p style="font-size: 14px; line-height: 1.8;">
    <strong>Ph.D. Students:</strong><span style="color: #b86f50;">
  I’m looking to welcome kind, curious, and self-driven Ph.D. students to join the WIN Lab.</span> If you’re passionate about wireless networks, protocols for 6G, machine learning for networks, or network economics, feel free to <a href="mailto:kkattiyanramamoorthy@scu.edu" style="color: #f4a261;">email me</a> with your CV and research interests.
  </p>

  <p style="font-size: 14px; line-height: 1.8;">
    <strong>M.S. Students:</strong> If you’re interested in completing a master’s thesis or working on directed research under my supervision, I’d love to hear from you. RA positions are offered based on performance in prior research, typically through a directed research pathway.
  </p>

  <p style="font-size: 14px; line-height: 1.8;">
    <strong>Undergraduate Students:</strong> Curious minds are always welcome! If you're excited to explore research, build real-world systems, or dive into wireless and IoT innovations, drop by my office or send a quick note. No prior research experience is required—just enthusiasm and a willingness to learn.
  </p>
</div>

<script>
function showSection(sectionId) {
  document.querySelectorAll('.toggle-section').forEach(div => div.classList.remove('active'));
  document.querySelectorAll('.toggle-buttons button').forEach(btn => btn.classList.remove('active'));

  document.getElementById(sectionId).classList.add('active');
  document.getElementById('btn-' + sectionId).classList.add('active');
}
</script>



