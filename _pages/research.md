---
layout: archive
title:
permalink: /Research/
author_profile: true
---

{% include base_path %}

<style>
/* ====== Intro Section ====== */
.research-intro {
  background: linear-gradient(to right, #f5f7fa, #e8eef3);
  padding: 2rem;
  border-radius: 12px;
  margin-bottom: 3rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
}
.research-intro .intro-text {
  max-width: 900px;
  margin: 0 auto;
  font-size: 1.05rem;
  color: #333;
  line-height: 1.7;
}

/* ====== NEW: Full-Width Research Section ====== */
/* This makes the entire section stretch full-width, like on your about page */
.research-section {
  position: relative;
  left: 50%;
  right: 50%;
  width: 100vw;
  margin-left: -50vw;
  margin-right: -50vw;
  background: #ffffff;
  padding: 2.5rem 0;
  text-align: center;
}

/* ====== NEW: Content Container ====== */
/* This container sits inside .research-section to center your grid */
.research-container {
  width: 100%;
  max-width: 1000px; /* Sets how wide the content area can go */
  margin: 0 auto; /* Centers inside full-width section */
  padding: 0 2rem;
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
  
/* ====== Research Grid (Your existing style) ====== */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  align-items: stretch;
  text-align: left; /* Resets text-align for cards */
}

/* ====== Research Card (Your existing style) ====== */
.research-card {
  background: white;
  border-radius: 16px;
  padding: 2rem;
  box-shadow: 0 6px 12px rgba(0,0,0,0.07);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.research-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 18px rgba(0,0,0,0.1);
}
.research-card h3 {
  color: #8b0000;
  font-weight: 600;
  margin-bottom: 1rem;
}
.research-card p {
  color: #333;
  font-size: 0.98rem;
  line-height: 1.7;
}
</style>


<div class="research-intro">
  <div class="intro-text">
    <p>
      The research directions below aim to advance human-centred intelligent home environments that are adaptive, trustworthy, sustainable, and supportive of independent living and ageing in place. 
      By integrating insights from computer vision, human–computer interaction, and embedded AI, 
      my work seeks to design systems that not only understand and respond to human activity 
      but also respect privacy, support user autonomy, and promote sustainable living. 
      The following are my key research directions:
    </p>
  </div>
</div>


<div class="research-section">
  
    <div class="research-container">

        <div class="pub-header"> RESEARCH FOCUS </div>

        <div class="research-grid">

      <div class="research-card">
        <h3> Human Activity Analysis in the Home Environment</h3>
        <p>
          This research focuses on developing novel deep learning models for analysing human activity within home environments. 
          The aim is to address both the technical and human-centered challenges that influence user acceptance and system performance in home activity monitoring. 
          Key challenges include balancing the trade-off between accuracy and computational efficiency to enable real-time monitoring on low-cost, resource-constrained embedded systems;s
          ensuring privacy and data security; and supporting user agency and autonomy in how monitoring systems operate within personal spaces.
        </p>
      </div>

      <div class="research-card">
        <h3> User Acceptance of Ambient Assisted Living Technologies</h3>
        <p>
          This research explores the human factors that shape the adoption and sustained use of ambient assisted living (AAL) technologies in home environments. 
          It seeks to understand user perceptions, preferences, and concerns regarding these systems, 
          with a focus on identifying the barriers and facilitators to their acceptance. 
          The overall goal is to ensure that AAL technologies are designed to meet the needs, expectations, and ethical considerations of end users, 
          thereby promoting trust, adoption, and long-term engagement.
        </p>
      </div>

      <div class="research-card">
        <h3> Computer Vision for Smart & Sustainable Homes</h3>
        <p>
          This research investigates computer vision–based methods for occupant-centred control of home systems 
          to achieve a balance between thermal comfort and energy efficiency. 
          It focuses on developing non-invasive, privacy-preserving approaches to capture and interpret occupant data. 
        *   Deep learning models are trained to estimate comfort levels, 
          which are then used to automate systems such as HVAC in a way that enhances both user comfort and sustainability.
        </p>
      </div>

    </div>   </div> </div> ```

</div>
