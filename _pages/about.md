---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<!-- ====== Styling ====== -->
<style>
/* Intro Section */
.about-intro {
  background: linear-gradient(60deg, #f7f9fb, #e6edf3);
  padding: 3rem 1.5rem;
  text-align: justify;
  border-radius: 16px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  margin-bottom: 3rem;
}
.about-intro h2 {
  color: #8b0000;
  font-size: 2rem;
  font-weight: 600;
  margin-bottom: 1rem;
}
.about-intro p {
  max-width: 800px;
  margin: 0 auto 1rem;
  font-size: 1.05rem;
  color: #333;
  line-height: 1.7;
}

/* Research Highlights */
.highlight-section {
  text-align: center;
}
.highlight-section h2 {
  color: #8b0000;
  font-size: 1.8rem;
  font-weight: 700;
  margin-bottom: 2.5rem;
}

.highlight-grid {
  display: flex;
  flex-direction: column;
  gap: 3rem;
}

/* Each highlight card */
.highlight-card {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 2rem;
  flex-wrap: wrap;
  background: #ffffff;
  border-radius: 16px;
  box-shadow: 0 6px 16px rgba(0,0,0,0.08);
  overflow: hidden;
  transition: transform 0.3s ease;
}
.highlight-card:hover {
  transform: translateY(-5px);
}

.highlight-card.reverse {
  flex-direction: row-reverse;
}

/* Text Section */
.highlight-text {
  flex: 1 1 45%;
  padding: 2rem;
  text-align: left;
}
.highlight-text h3 {
  color: #8b0000;
  margin-bottom: 1rem;
  font-size: 1.3rem;
}
.highlight-text p {
  color: #333;
  line-height: 1.7;
  font-size: 1rem;
}

/* Media Section */
.highlight-media {
  flex: 1 1 45%;
  position: relative;
  overflow: hidden;
  min-height: 250px;
  border-radius: 0 16px 16px 0;
}
.highlight-media img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.bg-video {
  width: 100%;
  height: 100%;
  object-fit: cover;
}


.highlight-links {
  margin-top: 1rem;
}
.highlight-btn {
  display: inline-block;
  background-color: #8b0000;
  color: white;
  text-decoration: none;
  padding: 0.45rem 0.9rem;
  margin-right: 0.5rem;
  border-radius: 8px;
  font-size: 0.9rem;
  transition: background-color 0.3s ease, transform 0.2s ease;
}
.highlight-btn:hover {
  background-color: #a01919;
  transform: translateY(-2px);
}
  
/* Responsive */
@media (max-width: 900px) {
  .highlight-card, .highlight-card.reverse {
    flex-direction: column;
  }
  .highlight-text {
    text-align: center;
  }
  .highlight-media {
    border-radius: 0 0 16px 16px;
  }
}
</style>


<!-- ====== Intro Section ====== -->
<div class="about-intro">
  <div class="intro-content">
    <h2>Welcome!</h2>
    <p>
      I conduct research on <strong>intelligent home environments</strong> that integrate 
      <strong>computer vision</strong>, <strong>embedded AI</strong>, and 
      <strong>human–computer interaction</strong> to support independent living and ageing in place. 
      My work spans human activity recognition, user acceptance of ambient assisted living technologies, 
      and occupant-centred control for energy-efficient home management. 
      Across these directions, I focus on developing adaptive, privacy-preserving, and sustainable systems 
      that promote user trust and comfort.
    </p>
    <p>
      Explore the <a href="{{ site.baseurl }}/Research/">Research</a> page for more insights into my ongoing projects.
    </p>
  </div>
</div>


<!-- ====== Research Highlights Section ====== -->
<div class="highlight-section">
  <h2> Research Highlights</h2>
  <div class="highlight-grid">


    <!-- Highlight 1 -->
    <div class="highlight-card reverse">
      <div class="highlight-media">
        <!-- Example background video -->
        <video autoplay loop muted playsinline class="bg-video">
          <source src="{{ site.baseurl }}/assets/videos/activity_recognition.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="highlight-text">
        <h3> Privacy-preserving Human Activity Recognition</h3>
        <p>
          To support safe and independent living, this research focuses on developing a 
          privacy-preserving model for understanding human activity within the home environment. 
          The proposed system performs robustly even in cluttered, unstructured real-world settings, 
          enabling accurate activity recognition while preserving users' privacy. 
        </p>
        <div class="highlight-links">
          <a href="https://doi.org/10.26599/BDMA.2025.9020003" class="highlight-btn" target="_blank"> Paper</a>
          <a href="https://github.com/Gbouna/RE-TCN" class="highlight-btn" target="_blank"> Code</a>
        </div>
      </div>
    </div>



    <!-- Highlight 2 -->
    <div class="highlight-card">
      <div class="highlight-text">
        <h3> Sustainable & Adaptive Smart Homes</h3>
        <p>
          Designing vision-based solutions that dynamically manage energy and comfort. 
          These systems integrate occupant feedback and AI-driven control strategies 
          for improved building sustainability and user satisfaction.
        </p>
        <div class="highlight-links">
          <a href="https://doi.org/10.1016/j.autcon.2024.105811" class="highlight-btn" target="_blank"> Paper</a>
          <a href="https://github.com/Gbouna/Non-invasive-vision-based-personal-comfort-model" class="highlight-btn" target="_blank"> Code</a>
        </div>
      </div>
      <div class="highlight-media">
        <img src="{{ site.baseurl }}/assets/images/thermal_comfort.jpg" alt="Sustainable Smart Home">
      </div>
    </div>



    <!-- Highlight 3 -->
    <div class="highlight-card reverse">
      <div class="highlight-media">
        <!-- Example background video -->
        <video autoplay loop muted playsinline class="bg-video">
          <source src="{{ site.baseurl }}/assets/videos/robot_skin.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="highlight-text">
        <h3> Human–Robot Collaboration in Healthcare</h3>
        <p>
          Exploring safe and intuitive interaction methods between humans and assistive robots 
          using capacitive sensing. This research aims to improve telehealthcare 
          and rehabilitation support in smart environments.
        </p>
        <div class="highlight-links">
          <a href="https://doi.org/10.1109/JBHI.2021.3082563" class="highlight-btn" target="_blank"> Paper</a>
        </div>
      </div>
    </div>

  </div>
</div>
