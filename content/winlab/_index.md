---
title: "WINLAB"
description: "Wireless Intelligent Networks (WIN) Lab at Santa Clara University"
---

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

<ul style="font-size: 14px; line-height: 1.9; list-style: none; padding-left: 0;">
  <li>🎯 <strong>NOMA for 6G Cellular Networks:</strong> Designing user-focused algorithms to enhance Quality of Experience (QoE) and fairness in non-orthogonal multiple access networks, leveraging machine learning and game theory.</li>
  
  <li>🎯 <strong>Multi-Link WiFi 7 for Intelligent LANs:</strong> Exploring Multi-Link Operation (MLO) for smarter traffic steering across bands and interfaces to achieve ultra-low latency and high throughput in wireless LANs.</li>
  
  <li>🎯 <strong>MAC-Layer Optimization for 6TiSCH IoT Networks:</strong> Developing distributed game-theoretic algorithms at the MAC layer to enhance scheduling efficiency, reduce energy consumption, and improve reliability in low-power industrial IoT networks built on the 6TiSCH protocol.</li>
  
  <li>🎯 <strong>RSMA for Next-Gen Spectrum Sharing:</strong> Exploring rate-splitting multiple access as a flexible and interference-aware access strategy for multi-user wireless systems, enabling improved spectral efficiency, user fairness, and adaptability under diverse QoS demands.</li>
</ul>

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
      <img src="/zack.webp" alt="Zack Common" class="member-photo">
      <div class="member-name">Zack Common</div>
      <div class="member-role">M.S. Student</div>
    </div>
    <div class="member-card">
      <img src="/Brian.PNG" alt="Brian Trinh" class="member-photo">
      <div class="member-name">Brian Trinh</div>
      <div class="member-role">M.S. Student</div>
    </div>
    <div class="member-card">
      <img src="/tom.webp" alt="Tom Ngo" class="member-photo">
      <div class="member-name">Tom Ngo</div>
      <div class="member-role">M.S. Student</div>
    </div>
    <div class="member-card">
      <img src="/khushi.webp" alt="Khushi Savaliya" class="member-photo">
      <div class="member-name">Khushi Savaliya</div>
      <div class="member-role">M.S. Student</div>
    </div>
  </div>
</div>

<!-- ALUMNI -->
<div class="team-section">
  <h3>Alumni</h3>
  <div class="alumni-grid">
    <div class="alumni-chip">Mrudhula Lokesh</div>
    <div class="alumni-chip">
      <div class="alumni-name">Samarth Kulkarni</div>
      <div class="alumni-dest">→ Piedmont Global Language Systems (PGLS)</div>
    </div>
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



