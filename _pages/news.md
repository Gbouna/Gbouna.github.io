---
layout: archive
title: 
permalink: /news/
author_profile: true
---

{% include base_path %}

<style>
/* ====== Full-width News Section ====== */
.news-section {
  position: relative;
  left: 50%;
  right: 50%;
  width: 100vw;
  margin-left: -50vw;
  margin-right: -50vw;
  background: #ffffff;
  padding: 2.5rem 0;
}

/* ====== Header ====== */
.pub-header {
  background-color: #e4e4e4;
  padding: 1rem 1rem;
  text-align: center;
  font-size: 2.2rem;
  font-weight: 700;
  color: #111;
  border-radius: 10px;
  margin-bottom: 2rem;
}

/* ====== News Container ====== */
.news-grid {
  display: flex;
  flex-direction: column;
  gap: 3rem;
  width: 100%;
  max-width: 1000px; /* Adjust for desired readable width */
  margin: 0 auto;
  padding: 0 2rem;
}

/* ====== Each News Item ====== */
.news-item {
  display: flex;
  flex-direction: row; /* ensures horizontal alignment */
  align-items: center;
  justify-content: space-between;
  gap: 40px;
  background: #ffffff;
  border-radius: 16px;
  box-shadow: 0 6px 16px rgba(0,0,0,0.08);
  padding: 1.5rem;
  transition: transform 0.3s ease;
}

.news-item:hover {
  transform: translateY(-5px);
}

/* ====== Image Section ====== */
.news-item img {
  width: 420px;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  flex: 0 0 auto;
}

/* ====== Text Section ====== */
.news-text {
  flex: 1 1 50%;
  min-width: 300px;
}

.news-text h2 {
  font-size: 1.4em;
  color: #7b1b1b;
  margin-bottom: 10px;
}

.news-text p {
  line-height: 1.6;
  color: #333;
  font-size: 1rem;
}

/* ====== Link Buttons ====== */
.link-group {
  margin-top: 10px;
}

.link-btn {
  display: inline-block;
  background-color: #7b1b1b;
  color: white !important;
  padding: 6px 14px;
  border-radius: 8px;
  text-decoration: none;
  margin-right: 8px;
  transition: 0.3s;
}

.link-btn:hover {
  background-color: #5a1111;
}

/* ====== Divider ====== */
hr {
  border: 0;
  border-top: 1px solid #e0e0e0;
  margin: 50px 0;
}

/* ====== Responsive Layout ====== */
@media (max-width: 900px) {
  .news-item {
    flex-direction: column;
    text-align: center;
  }

  .news-item img {
    width: 100%;
    max-width: 500px;
  }

  .news-text {
    text-align: center;
  }
}
</style>



<div class="pub-header"> LATEST NEWS</div>

<div class="news-item">
  <img src="{{ site.baseurl }}/assets/images/news/reviewer.jpg" alt="Outstanding Reviewer Award">
  <div class="news-text">
    <h2>Outstanding Reviewer Award: International Conference on AI in Healthcare 2025</h2>
    <p>
      As part of the International Program Committee, I was honoured to receive the 
      <b>Outstanding Reviewer Award</b> at the AI in Healthcare Conference 2025, 
      in recognition of my contributions to the peer review process. It's a privilege to 
      support the scientific community and help maintain the quality of research in this 
      rapidly evolving field.
    </p>
  </div>
</div>

<hr>

<div class="news-item">
  <img src="{{ site.baseurl }}/assets/images/news/aiiH2025.jfif" alt="Best Paper Award">
  <div class="news-text">
    <h2>Best Paper Award: Privacy-Preserving Activity Recognition for Ambient Assisted Living</h2>
    <p>
      Our paper received the <b>Best Paper Award</b> for its innovative approach to 
      preserving user privacy in computer vision-based activity monitoring. 
      We introduced TD-GDSCN, which performs accurate activity recognition locally, 
      eliminating the need to stream sensitive data to the cloud.
    </p>
    <div class="link-group">
      <a href="https://doi.org/10.1007/978-3-031-67285-9_15" class="link-btn" target="_blank">Paper</a>
      <a href="https://github.com/Gbouna/Action-Recognition-for-Privacy-Preserving-Ambient-Assisted-Living" class="link-btn" target="_blank">Code</a>
      <a href="https://www.youtube.com/watch?v=FExfkhTpHJA" class="link-btn" target="_blank">Demo</a>
    </div>
  </div>
</div>

<hr>

<div class="news-item">
  <img src="{{ site.baseurl }}/assets/images/news/best_paper.jpg" alt="Best Paper Award">
  <div class="news-text">
    <h2>Best Paper Award: IoT-Based Monitoring System for Smart Building Energy and Environmental Management</h2>
    <p>
      Our paper received the <b>Best Paper Award</b> for presenting an integrated, 
      non-invasive IoT-based monitoring system designed to improve energy efficiency 
      and indoor environmental quality (IEQ) in buildings. 
      The system combines hardware and software components to collect, process, 
      and visualise high-resolution energy and IEQ data in real time.
    </p>
    <div class="link-group">
      <a href="https://arxiv.org/abs/2503.23323" class="link-btn" target="_blank">Paper</a>
    </div>
  </div>
</div>

<hr>

<div class="news-item">
  <img src="{{ site.baseurl }}/assets/images/news/cover_page.jfif" alt="Cover Paper">
  <div class="news-text">
    <h2>Featured Cover Paper: Enhancing Human-Robot Collaboration in Healthcare 4.0</h2>
    <p>
      Our paper was <b>featured on the cover page</b>, highlighting our contribution to 
      safe and intuitive human-robot collaboration in Healthcare 4.0. 
      We proposed a modular proximity sensing solution based on self-capacitive technology, 
      enabling collaborative robots to detect approach and contact. 
      Operating in both interaction and safety modes, the system supports gesture-based control 
      and obstacle avoidance, enhancing telehealthcare delivery in human-centred environments.
    </p>
    <div class="link-group">
      <a href="https://doi.org/10.1109/JBHI.2021.3082563" class="link-btn" target="_blank">Paper</a>
    </div>
  </div>
</div>
