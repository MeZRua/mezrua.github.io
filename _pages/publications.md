---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
.pub-section-title {
  font-size: 1.2em;
  font-weight: bold;
  color: #2c3e50;
  border-left: 4px solid #e74c3c;
  padding-left: 10px;
  margin: 30px 0 15px 0;
}

.pub-card {
  background: #f9f9f9;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 16px 20px;
  margin-bottom: 16px;
  transition: box-shadow 0.2s ease;
}

.pub-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.10);
  border-color: #bbb;
}

.pub-badge {
  display: inline-block;
  background-color: #2980b9;
  color: white;
  font-size: 0.75em;
  font-weight: bold;
  padding: 2px 8px;
  border-radius: 4px;
  margin-right: 8px;
  vertical-align: middle;
  letter-spacing: 0.5px;
}

.pub-badge-journal  { background-color: #8e44ad; }
.pub-badge-conf     { background-color: #2980b9; }
.pub-badge-preprint { background-color: #e67e22; }

.pub-title {
  font-size: 1.0em;
  font-weight: bold;
  color: #2c3e50;
  display: inline;
  vertical-align: middle;
}

.pub-authors {
  margin-top: 6px;
  font-size: 0.92em;
  color: #555;
}

.pub-venue {
  margin-top: 4px;
  font-size: 0.88em;
  color: #888;
  font-style: italic;
}

.pub-links {
  margin-top: 8px;
}

.pub-link-btn {
  display: inline-block;
  font-size: 0.78em;
  padding: 2px 10px;
  border-radius: 12px;
  border: 1px solid #aaa;
  color: #555;
  text-decoration: none !important;
  margin-right: 6px;
  transition: all 0.2s;
}

.pub-link-btn:hover {
  background-color: #2980b9;
  color: white !important;
  border-color: #2980b9;
}

.pub-me   { font-weight: bold; color: #2c3e50; }
.pub-guid { text-decoration: underline; color: #2c3e50; }

.pub-stats {
  display: flex;
  gap: 30px;
  background: #f0f4f8;
  border-radius: 8px;
  padding: 14px 20px;
  margin-bottom: 24px;
  font-size: 0.95em;
  color: #444;
  flex-wrap: wrap;
}

.pub-stat-item { text-align: center; }

.pub-stat-num {
  font-size: 1.6em;
  font-weight: bold;
  color: #2980b9;
  display: block;
}

.pub-stat-label {
  font-size: 0.80em;
  color: #888;
}
</style>


<!-- ======= Stats Bar（数字由 JS 自动统计）======= -->
<div class="pub-stats">
  <div class="pub-stat-item">
    <span class="pub-stat-num" id="count-total">—</span>
    <span class="pub-stat-label">Total Papers</span>
  </div>
  <div class="pub-stat-item">
    <span class="pub-stat-num" id="count-journal">—</span>
    <span class="pub-stat-label">Journal Papers</span>
  </div>
  <div class="pub-stat-item">
    <span class="pub-stat-num" id="count-conf">—</span>
    <span class="pub-stat-label">Conference Papers</span>
  </div>
  <div class="pub-stat-item">
    <span class="pub-stat-num" id="count-preprint">—</span>
    <span class="pub-stat-label">Preprint & Reviewing</span>
  </div>
</div>
<!-- ======= Stats Bar ======= -->
<!-- {% assign journal_count = 0 %}
{% assign conf_count = 0 %}
{% assign preprint_count = 0 %}

{% comment %} 每新增一篇论文，对应的 assign +1 {% endcomment %}
{% assign journal_count = 2 %}    
{% assign conf_count = 2 %}       
{% assign preprint_count = 1 %}   

{% assign total_count = journal_count | plus: conf_count | plus: preprint_count %} -->

<!-- <div class="pub-stats">
  <div class="pub-stat-item">
    <span class="pub-stat-num">{{ total_count }}</span>
    <span class="pub-stat-label">Total Papers</span>
  </div>
  <div class="pub-stat-item">
    <span class="pub-stat-num">{{ journal_count }}</span>
    <span class="pub-stat-label">Journal Papers</span>
  </div>
  <div class="pub-stat-item">
    <span class="pub-stat-num">{{ conf_count }}</span>
    <span class="pub-stat-label">Conference Papers</span>
  </div>
  <div class="pub-stat-item">
    <span class="pub-stat-num">{{ preprint_count }}</span>
    <span class="pub-stat-label">Preprint & Reviewing</span>
  </div>
</div> -->



<!-- ======= Journal Papers ======= -->
<div class="pub-section-title">📖 Journal Papers</div>

<!-- J1 -->
<div class="pub-card pub-type-journal">
  <span class="pub-badge pub-badge-journal">IEEE JSTSP</span>
  <span class="pub-title">Adaptive Top-K in SGD for Communication-Efficient Distributed Learning in Multi-Robot Collaboration</span>
  <div class="pub-authors">
    <span class="pub-me">Mengzhe Ruan</span>, Guangfeng Yan, Yuanzhang Xiao, Linqi Song, Weitao Xu
  </div>
  <div class="pub-venue">
    📄 IEEE Journal of Selected Topics in Signal Processing — Early Access, March 2024
  </div>
  <div class="pub-links">
    <a class="pub-link-btn" href="https://arxiv.org/abs/2210.13532" target="_blank">📄 arXiv</a>
    <a class="pub-link-btn" href="#" target="_blank">🔗 IEEE</a>
  </div>
</div>

<!-- J2 -->
<div class="pub-card pub-type-journal">
  <span class="pub-badge pub-badge-journal">ACM TOSN</span>
  <span class="pub-title">mmSign: mmWave-based Few-Shot Online Handwritten Signature Verification</span>
  <div class="pub-authors">
    Mingda Han, Huanqi Yang, Tao Ni, Di Duan, <span class="pub-me">Mengzhe Ruan</span>, Yongliang Chen, Jia Zhang, Weitao Xu
  </div>
  <div class="pub-venue">
    📄 ACM Transactions on Sensor Networks — Volume 20, Issue 4, Pages 1–31, May 2024
  </div>
  <div class="pub-links">
    <a class="pub-link-btn" href="#" target="_blank">🔗 ACM DL</a>
  </div>
</div>


<!-- ======= Conference Papers ======= -->
<div class="pub-section-title">🏛️ Conference Papers</div>

<!-- C1 -->
<div class="pub-card pub-type-conf">
  <span class="pub-badge pub-badge-conf">ICPADS 2024</span>
  <span class="pub-title">Optimal Power Control for Over-the-Air Federated Learning with Gradient Compression</span>
  <div class="pub-authors">
    <span class="pub-me">Mengzhe Ruan</span>, <span class="pub-guid">Yunhe Li</span>, Weizhou Zhang, Linqi Song, Weitao Xu
  </div>
  <div class="pub-venue">
    🖥️ 30th International Conference on Parallel and Distributed Systems (ICPADS) — Belgrade, Serbia, 2024
  </div>
  <div class="pub-links">
    <a class="pub-link-btn" href="#" target="_blank">📄 Paper</a>
    <a class="pub-link-btn" href="#" target="_blank">🖼️ Slides</a>
  </div>
</div>

<!-- C2 -->
<div class="pub-card pub-type-conf">
  <span class="pub-badge pub-badge-conf">GLOBECOM 2023</span>
  <span class="pub-title">Adaptive Top-K in SGD for Communication-Efficient Distributed Learning</span>
  <div class="pub-authors">
    <span class="pub-me">Mengzhe Ruan</span>, Guangfeng Yan, Yuanzhang Xiao, Linqi Song, Weitao Xu
  </div>
  <div class="pub-venue">
    🎙️ IEEE Global Communications Conference (GLOBECOM) — Kuala Lumpur, Malaysia, 2023
  </div>
  <div class="pub-links">
    <a class="pub-link-btn" href="https://arxiv.org/abs/2210.13532" target="_blank">📄 arXiv</a>
    <a class="pub-link-btn" href="#" target="_blank">🖼️ Slides</a>
    <a class="pub-link-btn" href="#" target="_blank">🎬 Video</a>
  </div>
</div>


<!-- ======= Preprint, Revised & Reviewing Papers ======= -->
<div class="pub-section-title">📝 Preprint, Revised & Reviewing Papers</div>

<!-- P1：示例，按格式添加即可 -->
<div class="pub-card pub-type-preprint">
  <span class="pub-badge pub-badge-preprint">Revised</span>
  <span class="pub-title">Gradient Decoupling: A Plug-and-play Framework for Accelerating General Federated Learning</span>
  <div class="pub-authors">
    <span class="pub-me">Mengzhe Ruan</span>, Yunhe LI, Hao Shi, Hanxu Hou, Jianping Wang, Weitao Xu, Linqi Song
  </div>
  <div class="pub-venue"> 
    🔄 Revising
  </div>
  <!-- <div class="pub-links">
    <a class="pub-link-btn" href="#" target="_blank">📄 arXiv</a>
  </div> -->
</div>
<div class="pub-card pub-type-preprint">
  <span class="pub-badge pub-badge-preprint">Reviewing</span>
  <span class="pub-title">REGATE: Confidence-Calibrated Integration of Temporally-Aligned Exogenous Texts for Dynamic Graphs</span>
  <div class="pub-authors">
    Liangzu Liu, <span class="pub-me">Mengzhe Ruan</span>, Yinjun Wu, Yang Liu, Guanjun Wang 
  </div>
  <div class="pub-venue"> 
    📮 Submitted to ACL 2026
  </div>
  <!-- <div class="pub-links">⏳
    <a class="pub-link-btn" href="#" target="_blank">📄 arXiv</a>
  </div> -->
</div>


<!-- ======= 自动统计 JS（修复版）======= 如果你的卡片是后续异步注入的：用 MutationObserver 如果你发现页面初始 HTML 里没有这些 .pub-card（由 JS/插件后插入），用这个更彻底：-->
<!-- <script>
document.addEventListener("DOMContentLoaded", () => {
  const update = () => {
    const j = document.querySelectorAll(".pub-type-journal").length;
    const c = document.querySelectorAll(".pub-type-conf").length;
    const p = document.querySelectorAll(".pub-type-preprint").length;

    document.getElementById("count-total").textContent    = j + c;
    document.getElementById("count-journal").textContent  = j;
    document.getElementById("count-conf").textContent     = c;
    document.getElementById("count-preprint").textContent = p;
  };

  update();

  const obs = new MutationObserver(() => update());
  obs.observe(document.body, { childList: true, subtree: true });
});
</script> -->
<script>
document.addEventListener("DOMContentLoaded", () => {
  const update = () => {
    const j = document.querySelectorAll(".pub-type-journal").length;
    const c = document.querySelectorAll(".pub-type-conf").length;
    const p = document.querySelectorAll(".pub-type-preprint").length;

    const set = (id, val) => {
      const el = document.getElementById(id);
      if (el) el.textContent = String(val);
    };

    set("count-total", j + c + p);
    set("count-journal", j);
    set("count-conf", c);
    set("count-preprint", p);
  };

  update();
  setTimeout(update, 200);
  setTimeout(update, 800);
});
</script>







