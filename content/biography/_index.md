---
title: "Books"
description: "Books by Professor Dr von Igelfeld's."
---

<p style="font-size: 16px; line-height: 1.7;">
  I'm Krishna Ramamoorthy, a faculty member in Computer Science and Engineering at Santa Clara University. I'm currently a tenure-track Assistant Professor, and before this, I taught as a Lecturer at San Diego State University and worked as a System Architect at Kaiser Permanente IT. I earned my Ph.D. in Computational Science from UC Irvine in 2023, advised by <a href="https://wwang.sdsu.edu/" class="advisor-link" target="_blank">Dr. Wei Wang</a>, and hold prior degrees from CSUN and Amrita Vishwa Vidyapeetham University.
</p>


<p style="font-size: 16px; line-height: 1.7;">
  I strive to make meaningful contributions to research while fostering a learning environment built on curiosity, clarity, and care. Teaching and mentoring are at the heart of my academic life.  I’ve published in leading journals such as IEEE Transactions on Vehicular Technology, and actively present and serve on technical program committees for conferences like IEEE ICC and IEEE WCNC. 
  You can view my full CV <a href="/KrishnaRamamoorthyCV.pdf" class="advisor-link" target="_blank">here</a>.
</p>


<style>
.bio-tab-wrapper {
  display: flex;
  justify-content: center;
  margin: 40px 0 20px;
}

.bio-tabs {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.bio-tabs button {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  border-radius: 8px;
  background-color: #e0e0e0;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.2s ease;
}

.bio-tabs button:hover {
  background-color: #ffd580;
}

.bio-tabs button.active {
  background-color: #ffd580;
  font-weight: bold;
}

.bio-section {
  display: none;
  animation: fadeIn 0.4s ease;
}
.bio-section.active {
  display: block;
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}
</style>

<div class="bio-tab-wrapper">
  <div class="bio-tabs">
    <button id="btn-news" class="active" onclick="showBioSection('news')">📌 News</button>
    <button id="btn-service" onclick="showBioSection('service')">🤝 Professional Service</button>
    <button id="btn-beyond" onclick="showBioSection('beyond')">🌱 Beyond Work</button>
  </div>
</div>

<!-- 📌 NEWS -->
<div id="news" class="bio-section active">
  <div style="font-size: 16px; line-height: 1.8;">
    <p><strong>📌 March 24, 2025</strong> – It was a joy to see my students present their research at the <em>IEEE Wireless Communications and Networking Conference (WCNC)</em> in Milan, Italy.</p>
    <p><strong>📌 November 18, 2024</strong> – Fortunate to receive the <em>2FURS Grant</em> in support of our ongoing research efforts.</p>
    <p><strong>📌 September 1, 2024</strong> – Started my position as a tenure-track Assistant Professor at <em>Santa Clara University</em>. Truly thankful to begin this new chapter.</p>
  </div>
</div>

<!-- 🤝 SERVICE -->
<div id="service" class="bio-section">
  <p style="font-size: 16px; line-height: 1.8;"><strong>Technical Program Committee:</strong></p>
  <ul style="font-size: 15px; line-height: 1.8; padding-left: 20px; margin-top: -10px;">
    <li>IEEE Wireless Communications and Networking Conference (WCNC): 2023, 2024, 2025</li>
    <li>IEEE Global Communications Conference (Globecom): 2019</li>
    <li>IEEE Intermountain Engineering, Technology and Computing Conference (IETC): 2024</li>
  </ul>

  <p style="font-size: 16px; line-height: 1.8;"><strong>Technical Reviewer:</strong></p>
  <ul style="font-size: 15px; line-height: 1.8; padding-left: 20px; margin-top: -10px;">
    <li>IEEE Communications Magazine — 2024</li>
    <li>Results in Optics — 2023</li>
    <li>International Journal of Electrical, Electronics and Computer Systems (IJEECS) — 2021</li>
  </ul>

  <p style="font-size: 16px; line-height: 1.8;"><strong>Judge:</strong></p>
  <ul style="font-size: 15px; line-height: 1.8; padding-left: 20px; margin-top: -10px;">
    <li>Student Research Symposium, San Diego State University — 2023</li>
  </ul>
</div>

<!-- 🌱 BEYOND WORK -->
<div id="beyond" class="bio-section">
  <p style="font-size: 16px; line-height: 1.8;">
    Outside of work, I love playing fetch with my kitty cat Eevee (yes, he actually plays fetch!) and unwinding with a good board game — <strong>Catan</strong> is my all-time favorite. I truly enjoy <strong>aquascaping</strong>, and I also <strong>foster kittens</strong> whenever I can. These little side passions bring a lot of joy and balance to my life.
  </p>

  <h4 style="margin-top: 30px;">🐠 Aquascaping</h4>
  <div style="display: flex; flex-wrap: wrap; gap: 16px; margin-bottom: 30px;">
    <img src="/A3.JPG" alt="Aquascape 1" style="width: 30%; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <img src="/A2.JPG" alt="Aquascape 2" style="width: 30%; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <img src="/A1.JPG" alt="Aquascape 3" style="width: 30%; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
  </div>

  <h4>🐾 Foster Kittens</h4>
  <div style="display: flex; flex-wrap: wrap; gap: 16px;">
    <img src="/F1.JPG" alt="Foster Kitty 1" style="width: 30%; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <img src="/F2.JPG" alt="Foster Kitty 2" style="width: 30%; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <img src="/F3.JPG" alt="Foster Kitty 3" style="width: 30%; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
  </div>
</div>

<!-- JS Logic -->
<script>
function showBioSection(id) {
  document.querySelectorAll('.bio-section').forEach(s => s.classList.remove('active'));
  document.querySelectorAll('.bio-tabs button').forEach(b => b.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  document.getElementById('btn-' + id).classList.add('active');
}
</script>