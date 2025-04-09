---
title: "Data"
description: "Datasets on various philological topics."
---

<p align="center">
  <img src="/lab.jpeg" alt="My photo" width="900" height="200"/>
</p>

<p style="font-size: 16px; line-height: 1.8;">
  The <strong>Wireless Intelligent Networks (WIN) Lab</strong> at Santa Clara University explores next-generation wireless systems that adapt, learn, and make intelligent decisions — with a focus on efficient resource allocation, smarter access protocols, and user-centered performance.
</p>

<p style="font-size: 16px; line-height: 1.8;">
We focus on technologies like WiFi 7, 5G/6G, and intelligent multiple access protocols—including NOMA, RSMA, and 6TiSCH — alongside research in QoE/QoS optimization, machine learning techniques in wireless network, network economics, wireless multimedia and cognitive radio.
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
</style>

<div class="toggle-wrapper">
  <div class="toggle-buttons">
    <button id="btn-research" class="active" onclick="showSection('research')">Current Research</button>
    <button id="btn-people" onclick="showSection('people')">Meet the Team</button>
    <button id="btn-prospective" onclick="showSection('prospective')">Prospective Students</button>
  </div>
</div>

<div id="research" class="toggle-section active">
<ul style="font-size: 16px; line-height: 1.8; list-style: none; padding-left: 0;">
  <li>📡 <strong>NOMA Networks:</strong> Intelligent QoE-aware strategies for non-orthogonal multiple access.</li>
  <li>🧠 <strong>WiFi 7:</strong> Multi-Link Operation (MLO) for high-throughput, low-latency wireless systems.</li>
  <li>🔍 <strong>6TiSCH IoT Networks:</strong> Game-theoretic scheduling and energy-efficient resource management.</li>
  <li>⚙️ <strong>RSMA Networks:</strong> Flexible and fair access via rate-splitting in next-gen communication.</li>
</ul>

</div>

<div id="people" class="toggle-section">
  <h3>Undergraduate Students:</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 40px; justify-content: space-between;">
    <div style="flex: 1 1 45%; display: flex; gap: 20px; align-items: center;">
      <img src="/picture1.jpeg" alt="Derek Chui" style="width: 120px; height: 120px; object-fit: cover; border-radius: 8px;">
      <div>
        <h3 style="margin: 0;">Derek Chui</h3>
        <p style="margin: 4px 0;">B.S. Student</p>
        <p style="margin: 4px 0;"><em>Project:</em> Optimizing NOMA Network.</p>
      </div>
    </div>
  </div>

  <h3 style="margin-top: 40px;">Graduate Students:</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 40px; justify-content: space-between;">
    <div style="flex: 1 1 45%; display: flex; gap: 20px; align-items: center;">
      <img src="/picture1.jpeg" alt="Mrudhula Lokesh" style="width: 120px; height: 120px; object-fit: cover; border-radius: 8px;">
      <div>
        <h3 style="margin: 0;">Mrudhula Lokesh</h3>
        <p style="margin: 4px 0;">M.S Student</p>
        <p style="margin: 4px 0;"><em>Project:</em> WiFi 7 - MLO.</p>
      </div>
    </div>

  <div style="flex: 1 1 45%; display: flex; gap: 20px; align-items: center;">
      <img src="/picture1.jpeg" alt="Samarth Kulkarni" style="width: 120px; height: 120px; object-fit: cover; border-radius: 8px;">
      <div>
        <h3 style="margin: 0;">Samarth Kulkarni</h3>
        <p style="margin: 4px 0;">M.S Student</p>
        <p style="margin: 4px 0;"><em>Project:</em> ML Models for WiFi 7.</p>
      </div>
    </div>

  <div style="flex: 1 1 45%; display: flex; gap: 20px; align-items: center;">
      <img src="/picture1.jpeg" alt="Brin" style="width: 120px; height: 120px; object-fit: cover; border-radius: 8px;">
      <div>
        <h3 style="margin: 0;">Brian Trinh</h3>
        <p style="margin: 4px 0;">M.S Student</p>
        <p style="margin: 4px 0;"><em>Project:</em> ML Models for WiFi 7.</p>
      </div>
    </div>
  </div>
</div>

<div id="prospective" class="toggle-section">
  <p style="font-size: 16px; line-height: 1.8;">
    <strong>Ph.D. Students:</strong><span style="color: #b86f50;">
  I’m looking to welcome kind, curious, and self-driven Ph.D. students to join the WIN Lab.</span> If you’re passionate about wireless networks, ML for networks, or network economics, feel free to <a href="mailto:kkattiyanramamoorthy@scu.edu" style="color: #f4a261;">email me</a> with your CV and research interests.
  </p>

  <p style="font-size: 16px; line-height: 1.8;">
    <strong>M.S. Students:</strong> If you’re interested in completing a master’s thesis or working on directed research under my supervision, I’d love to hear from you. RA positions are offered based on performance in prior research, typically through a directed research pathway.
  </p>

  <p style="font-size: 16px; line-height: 1.8;">
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



