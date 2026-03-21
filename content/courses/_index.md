---
title: "Teaching"
description: ""
---


<style>
.course-glow-section {
  margin-top: 40px;
}

.course-glow-title {
  font-size: 20px;
  font-weight: 700;
  margin: 40px 0 20px;
  padding-bottom: 5px;
  border-bottom: 2px solid #e2e2e2;
}

.course-glow-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 24px;
}

.course-glow-column {
  display: flex;
  flex-direction: column;
  gap: 24px;
}

.course-glow-card {
  background: #fff;
  border-radius: 16px;
  padding: 20px 24px;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.05);
  border: 1px solid #f0f0f0;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
  text-decoration: none;
  color: inherit;
  display: block;
}

.course-glow-card::before {
  content: "";
  position: absolute;
  top: -30%;
  left: -30%;
  width: 160%;
  height: 160%;
  background: radial-gradient(circle, rgba(255,213,128,0.15), transparent 70%);
  transform: scale(0);
  transition: transform 0.5s ease;
}

.course-glow-card:hover::before {
  transform: scale(1);
}

.course-glow-card:hover {
  box-shadow: 0 12px 32px rgba(0,0,0,0.12);
  border-color: #ffd580;
  transform: translateY(-4px);
}

.course-glow-card h4 {
  margin: 0 0 6px;
  font-size: 18px;
  font-weight: 600;
}

.course-glow-card p {
  margin: 0;
  font-size: 15px;
  color: #555;
}
</style>

<!-- Undergraduate Courses -->
<div class="course-glow-section">
  <div class="course-glow-title">Undergraduate</div>
  <div class="course-glow-column">
    <div class="course-glow-card">
      <h4>CSEN 11: Advanced Programming</h4>
      <p>Session: Winter '26</p>
    </div>
    <div class="course-glow-card">
      <h4>CSEN 79: OO Programming and Advanced Data Structures</h4>
      <p>Session: Winter '25</p>
    </div>
    <div class="course-glow-card" onclick="openSyllabus()" style="cursor:pointer;">
      <h4>CSEN 171: Design and Implementation of Programming Languages</h4>
      <p>Session: Fall '25</p>
      <p style="margin-top:8px; font-size:12px; font-weight:600; color:#b07800;">📄 View Syllabus ↗</p>
    </div>
  </div>
</div>

<!-- Graduate Courses -->
<div class="course-glow-section">
  <div class="course-glow-title">Graduate</div>
  <div class="course-glow-grid">
    <div class="course-glow-card">
      <h4>CSEN 233: Computer Networks</h4>
      <p>Session: Fall '24</p>
    </div>
  </div>
</div>

<!-- Syllabus Modal -->
<div id="syllabus-modal" style="display:none; position:fixed; inset:0; background:rgba(0,0,0,0.55); z-index:9999; align-items:center; justify-content:center;" onclick="closeSyllabusOutside(event)">
  <div id="syllabus-modal-inner" style="background:#fff; border-radius:16px; width:90%; max-width:860px; height:85vh; display:flex; flex-direction:column; overflow:hidden; box-shadow:0 20px 60px rgba(0,0,0,0.25);">
    <div style="display:flex; align-items:center; justify-content:space-between; padding:14px 20px; border-bottom:1px solid #eee;">
      <span style="font-weight:600; font-size:15px;">CSEN 171 Syllabus</span>
      <button onclick="closeSyllabus()" style="background:none; border:none; font-size:22px; cursor:pointer; line-height:1; color:#555;">&#x2715;</button>
    </div>
    <iframe src="/CSEN_171__Syllabus__Section1-3.pdf" style="flex:1; border:none; width:100%;"></iframe>
  </div>
</div>

<script>
function openSyllabus() {
  const m = document.getElementById('syllabus-modal');
  m.style.display = 'flex';
}
function closeSyllabus() {
  document.getElementById('syllabus-modal').style.display = 'none';
}
function closeSyllabusOutside(e) {
  if (e.target === document.getElementById('syllabus-modal')) closeSyllabus();
}
</script>



