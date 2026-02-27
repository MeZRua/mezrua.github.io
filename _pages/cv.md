---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-download-bar {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
  margin-bottom: 28px;
}

.cv-download-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 8px 18px;
  border-radius: 6px;
  font-size: 0.92em;
  font-weight: bold;
  text-decoration: none !important;
  transition: all 0.2s;
  border: none;
  cursor: pointer;
}

.cv-btn-primary {
  background-color: #2980b9;
  color: white !important;
}

.cv-btn-primary:hover {
  background-color: #1a5f8a;
}

.cv-btn-secondary {
  background-color: #8e44ad;
  color: white !important;
}

.cv-btn-secondary:hover {
  background-color: #6c3483;
}

.cv-section-title {
  font-size: 1.2em;
  font-weight: bold;
  color: #2c3e50;
  border-left: 4px solid #2980b9;
  padding-left: 10px;
  margin: 30px 0 15px 0;
}

.cv-card {
  background: #f9f9f9;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 16px 20px;
  margin-bottom: 14px;
  transition: box-shadow 0.2s ease;
}

.cv-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  border-color: #bbb;
}

.cv-card-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 6px;
}

.cv-card-title {
  font-weight: bold;
  font-size: 1.0em;
  color: #2c3e50;
}

.cv-card-date {
  font-size: 0.82em;
  color: #888;
  background: #eee;
  padding: 2px 8px;
  border-radius: 10px;
  white-space: nowrap;
}

.cv-card-subtitle {
  font-size: 0.90em;
  color: #555;
  margin-top: 4px;
  font-style: italic;
}

.cv-card-desc {
  font-size: 0.88em;
  color: #666;
  margin-top: 6px;
  line-height: 1.6;
}

.cv-badge {
  display: inline-block;
  font-size: 0.75em;
  padding: 2px 8px;
  border-radius: 4px;
  font-weight: bold;
  margin-right: 6px;
  color: white;
}

.badge-edu    { background-color: #27ae60; }
.badge-intern { background-color: #e67e22; }
.badge-review { background-color: #8e44ad; }

.cv-tag {
  display: inline-block;
  font-size: 0.78em;
  padding: 1px 8px;
  border-radius: 10px;
  background: #eaf4fb;
  border: 1px solid #aed6f1;
  color: #2980b9;
  margin: 2px 3px 2px 0;
}
</style>

<!-- ======= Download Buttons ======= -->
<div class="cv-download-bar">
  <a class="cv-download-btn cv-btn-primary" 
     href="/files/RUAN%20Mengzhe_CV.pdf" target="_blank">
    📄 Download Full CV
  </a>
  <a class="cv-download-btn cv-btn-secondary" 
     href="/files/research_statement.pdf" target="_blank">
    🔬 Research Statement
  </a>
</div>


<!-- ======= Education ======= -->
<div class="cv-section-title">🎓 Education</div>

<div class="cv-card">
  <div class="cv-card-header">
    <span><span class="cv-badge badge-edu">PhD</span>
    <span class="cv-card-title">City University of Hong Kong</span></span>
    <span class="cv-card-date">Aug. 2020 – Jun. 2025</span>
  </div>
  <div class="cv-card-subtitle">Doctor of Philosophy · Department of Computer Science</div>
  <div class="cv-card-desc">
    Supervised by <a href="https://www.weitaoxu.com/" target="_blank">Dr. XU Weitao</a>. 
    Research on communication-efficient distributed & federated learning.
  </div>
</div>

<div class="cv-card">
  <div class="cv-card-header">
    <span><span class="cv-badge badge-edu">B.S. &amp; B.Econ.</span>
    <span class="cv-card-title">Sichuan University</span></span>
    <span class="cv-card-date">Aug. 2016 – Jun. 2020</span>
  </div>
  <div class="cv-card-subtitle">
    B.S. in Computer Science &amp; Technology &nbsp;|&nbsp; 
    B.Econ. in Financial Engineering
  </div>
  <div class="cv-card-desc">
    Wu Yuzhang Honors College, Sichuan University.
  </div>
</div>


<!-- ======= Internship ======= -->
<div class="cv-section-title">💼 Internship Experience</div>

<div class="cv-card">
  <div class="cv-card-header">
    <span><span class="cv-badge badge-intern">Intern</span>
    <span class="cv-card-title">Huawei Corporate Development (Hubble Investment)</span></span>
    <span class="cv-card-date">2024.4 – Present</span>
  </div>
  <div class="cv-card-subtitle">Technology Investment Analyst Intern · Shenzhen, China</div>
  <div class="cv-card-desc">
    <span class="cv-tag">Tech Investment</span>
    <span class="cv-tag">AI Ecosystem</span>
  </div>
</div>

<div class="cv-card">
  <div class="cv-card-header">
    <span><span class="cv-badge badge-intern">Intern</span>
    <span class="cv-card-title">Qilin Investment</span></span>
    <span class="cv-card-date">2024.2 – 2024.3</span>
  </div>
  <div class="cv-card-subtitle">Quantitative Researcher Intern (Machine Learning) · Shanghai, China</div>
  <div class="cv-card-desc">
    Developing deep learning models for time series forecasting.
    <br>
    <span class="cv-tag">Time Series</span>
    <span class="cv-tag">Deep Learning</span>
    <span class="cv-tag">Quant Finance</span>
  </div>
</div>

<div class="cv-card">
  <div class="cv-card-header">
    <span><span class="cv-badge badge-intern">Intern</span>
    <span class="cv-card-title">Huawei Technologies 2012 Labs</span></span>
    <span class="cv-card-date">2023.11 – 2024.2</span>
  </div>
  <div class="cv-card-subtitle">AI (Machine Learning) Engineer Intern · Hangzhou, China</div>
  <div class="cv-card-desc">
    Research on distributed collective communication algorithms (NCCL, HCCL).
    <br>
    <span class="cv-tag">Distributed ML</span>
    <span class="cv-tag">NCCL</span>
    <span class="cv-tag">HCCL</span>
  </div>
</div>


<!-- ======= Service ======= -->
<div class="cv-section-title">🤝 Academic Service</div>

<div class="cv-card">
  <div class="cv-card-header">
    <span><span class="cv-badge badge-review">Reviewer</span>
    <span class="cv-card-title">Conference Reviewer</span></span>
  </div>
  <div class="cv-card-desc" style="margin-top:8px;">
    <span class="cv-tag">ICLR 2025</span>
    <span class="cv-tag">AISTATS 2025</span>
    <span class="cv-tag">ICDCS 2024</span>
  </div>
</div>

<div class="cv-card">
  <div class="cv-card-header">
    <span><span class="cv-badge badge-review">Reviewer</span>
    <span class="cv-card-title">Journal Reviewer</span></span>
  </div>
  <div class="cv-card-desc" style="margin-top:8px;">
    <span class="cv-tag">Intelligent and Converged Networks</span>
  </div>
</div>
