---
title: "WINLAB"
description: "Wireless Intelligent Networks (WIN) Lab at Santa Clara University"
---

<p align="center">
  <img src="/lab.jpeg" alt="WIN Lab Logo" style="max-width: 100%; height: auto;"/>
</p>

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
 
.student-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: center;
  margin-top: 20px;
}

.student-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: center;
  margin-top: 20px;
}

.student-card {
  width: 210px;
  height: 260px;
  background-color: white;
  border-radius: 16px;
  overflow: hidden;
  position: relative;
  box-shadow: 0 0 10px rgba(0,0,0,0.06);
  transition: box-shadow 0.3s ease;
  text-align: center;
  cursor: pointer;
  padding-top: 20px;
}

.student-card:hover {
  box-shadow: 0 0 12px 2px gold;
}

.student-image {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 8px;
  transition: all 0.4s ease;
  margin-bottom: 10px;
}

.student-card:hover .student-image {
  width: 80px;
  height: 80px;
  margin-bottom: 4px;
}

.student-info {
  transition: transform 0.3s ease;
}

.student-name {
  font-weight: bold;
  margin-bottom: 4px;
  transition: margin-bottom 0.3s ease;
}

.student-role {
  font-style: italic;
  font-size: 14px;
  color: #555;
  transition: margin-bottom 0.3s ease;
}

.project-hover {
  opacity: 0;
  transition: opacity 0.3s ease;
  font-size: 14px;
  margin-top: 6px;
  padding: 0 10px;
}

.student-card:hover .project-hover {
  opacity: 1;
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
<h3 style="text-align: center; margin-top: 40px;">Undergraduate Students:</h3>
<div class="student-grid">
  <div class="student-card">
    <img src="/picture1.jpeg" alt="Derek Chui" class="student-image">
    <div class="student-info">
      <div class="student-name">Derek Chui</div>
      <div class="student-role">B.S. Student</div>
      <div class="project-hover"><em>Project:</em> Efficient user grouping in NOMA Networks</div>
    </div>
  </div>
</div>

<!-- GRADUATE STUDENTS -->
<h3 style="text-align: center; margin-top: 50px;">Graduate Students:</h3>
<div class="student-grid">
  <div class="student-card">
    <img src="/picture1.jpeg" alt="Mrudhula Lokesh" class="student-image">
    <div class="student-info">
      <div class="student-name">Mrudhula Lokesh</div>
      <div class="student-role">M.S. Student</div>
      <div class="project-hover"><em>Project:</em> Optimizing Multi Link Operation (MLO) in WiFi 7</div>
    </div>
  </div>

  <div class="student-card">
    <img src="/picture1.jpeg" alt="Samarth Kulkarni" class="student-image">
    <div class="student-info">
      <div class="student-name">Samarth Kulkarni</div>
      <div class="student-role">M.S. Student</div>
      <div class="project-hover"><em>Project:</em> Advanced Reinforcement Learning Models for WiFi 7</div>
    </div>
  </div>

  <div class="student-card">
    <img src="/Brian.PNG" alt="Brian Trinh" class="student-image">
    <div class="student-info">
      <div class="student-name">Brian Trinh</div>
      <div class="student-role">M.S. Student</div>
      <div class="project-hover"><em>Project:</em> ML driven Traffic Distribution in WiFi 7</div>
    </div>
  </div>
</div>

</div>


<div id="prospective" class="toggle-section active">
  <p style="font-size: 14px; line-height: 1.8;">
    <strong>Ph.D. Students:</strong><span style="color: #b86f50;">
  I’m looking to welcome kind, curious, and self-driven Ph.D. students to join the WIN Lab.</span> If you’re passionate about wireless networks, ML for networks, or network economics, feel free to <a href="mailto:kkattiyanramamoorthy@scu.edu" style="color: #f4a261;">email me</a> with your CV and research interests.
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



