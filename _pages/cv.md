---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- ====== Styling ====== -->
<style>
.cv-container {
  background: #ffffff;
  padding: 2.5rem;
  border-radius: 16px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  line-height: 1.7;
  color: #333;
  max-width: 900px;
  margin: 0 auto;
  font-size: 1rem;
}

.download-btn {
  display: inline-block;
  background-color: #8b0000;
  color: #fff;
  padding: 0.6rem 1.2rem;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  transition: background-color 0.3s ease, transform 0.2s ease;
  margin-bottom: 2rem;
}
.download-btn:hover {
  background-color: #a01919;
  transform: translateY(-2px);
}

/* Section headers */
.cv-section {
  margin-bottom: 3rem;
}
.cv-section h2 {
  color: #8b0000;
  font-size: 1.4rem;
  font-weight: 700;
  border-bottom: 2px solid #eee;
  padding-bottom: 0.4rem;
  margin-bottom: 1.5rem;
}

/* Timeline layout */
.timeline {
  position: relative;
  margin: 0;
  padding-left: 2rem;
  border-left: 3px solid #8b0000;
}
.timeline-item {
  position: relative;
  margin-bottom: 1.8rem;
}
.timeline-item::before {
  content: '';
  position: absolute;
  left: -10px;
  top: 0.5rem;
  width: 14px;
  height: 14px;
  background-color: #8b0000;
  border-radius: 50%;
}
.timeline-date {
  color: #777;
  font-size: 0.9rem;
  font-weight: 500;
}
.timeline-role {
  font-weight: 600;
  color: #111;
  margin-bottom: 0.3rem;
}
.timeline-org {
  font-style: italic;
  color: #444;
  margin-bottom: 0.5rem;
}

/* Awards and others */
.cv-section ul {
  list-style: none;
  padding-left: 0;
  margin: 0;
}
.cv-section li {
  margin-bottom: 0.8rem;
}

/* Print-friendly */
@media print {
  .download-btn { display: none; }
  .cv-container {
    box-shadow: none;
    padding: 0;
  }
}
</style>

---

<div class="cv-container">

<a href="{{ site.baseurl }}/assets/files/CV_Gbouna.pdf" class="download-btn" download> Download Full CV (PDF)</a>

<!-- ======================= -->
<!-- Education -->
<!-- ======================= -->
<div class="cv-section">
  <h2>Education</h2>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-role">PhD in Computer Science</div>
      <div class="timeline-org">Aston University</div>
      <div class="timeline-date">Oct 2022 – Sept 2025</div>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Postgraduate Certificate in Learning and Teaching in Higher Education (PGCert)</div>
      <div class="timeline-org">Aston University</div>
      <div class="timeline-date">Oct 2023 – Nov 2024</div>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Introduction to Learning and Teaching Practice in Higher Education (ILTP)</div>
      <div class="timeline-org">Aston University</div>
      <div class="timeline-date">Mar 2023 – Sept 2023</div>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Master of Engineering in Mechatronic Engineering</div>
      <div class="timeline-org">Zhejiang University</div>
      <div class="timeline-date">2018 – 2021</div>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Bachelor of Engineering in Electronics Information Engineering</div>
      <div class="timeline-org">Liaoning University of Technology</div>
      <div class="timeline-date">2014 – 2018</div>
    </div>

  </div>
</div>

<!-- ======================= -->
<!-- Experience -->
<!-- ======================= -->
<div class="cv-section">
  <h2>Professional Experience</h2>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-role">Lecturer in AI and Data Science</div>
      <div class="timeline-org">University of Hull</div>
      <div class="timeline-date">June 2025 – Present</div>
      <ul>
        <li>Module leader for <em>Programming for AI and Data Science</em>, coordinating assessments and teaching materials.</li>
        <li>Develop inclusive and engaging teaching resources that bridge theory with practice.</li>
        <li>Supervise postgraduate dissertation projects and support student wellbeing.</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Lecturer in Computing</div>
      <div class="timeline-org">Ulster University (QA Higher Education)</div>
      <div class="timeline-date">Jan 2025 – Nov 2025</div>
      <ul>
        <li>Taught modules and provided guidance on computer science–related subjects.</li>
        <li>Contributed to assessment design and supervision of postgraduate projects.</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Postgraduate Teaching Assistant</div>
      <div class="timeline-org">Aston University</div>
      <div class="timeline-date">Oct 2022 – Oct 2025</div>
      <ul>
        <li>Delivered tutorials in AI, Data Mining, and Machine Learning modules.</li>
        <li>Assessed assignments and supervised dissertation projects.</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Research Assistant</div>
      <div class="timeline-org">The Hong Kong Polytechnic University</div>
      <div class="timeline-date">Nov 2021 – July 2022</div>
      <ul>
        <li>Developed vision-based models for occupant thermal comfort prediction.</li>
        <li>Managed hardware procurement and research administration.</li>
        <li>Designed and maintained the <a href="https://ibeems-lee.com/">IBEEMS research website</a>.</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-role">Research Assistant</div>
      <div class="timeline-org">Westlake University</div>
      <div class="timeline-date">June 2021 – Nov 2021</div>
      <ul>
        <li>Designed embedded systems for biodiversity monitoring.</li>
        <li>Collaborated on interdisciplinary research and hardware development.</li>
      </ul>
    </div>

  </div>
</div>

<!-- ======================= -->
<!-- Certifications -->
<!-- ======================= -->
<div class="cv-section">
  <h2>Professional Certification</h2>
  <ul>
    <li>Fellow of the Higher Education Academy (FHEA), AdvanceHE — <em>Nov 2024</em></li>
    <li>Associate Fellow of the Higher Education Academy (AFHEA), AdvanceHE — <em>Sept 2023</em></li>
  </ul>
</div>

<!-- ======================= -->
<!-- Awards -->
<!-- ======================= -->
<div class="cv-section">
  <h2>Awards</h2>
  <ul>
    <li> Best Paper Runner-Up — International Conference on AI in Healthcare, 2024</li>
    <li> Best Paper Award — 22nd Int’l Conference on Construction Applications of Virtual Reality, 2022</li>
    <li> UKRI PhD Studentship — Fully funded doctoral research, 2022–2025</li>
    <li> F.C.T Scholarship Board — Ministerial Special Scholarship Award of Excellence, 2018</li>
  </ul>
</div>

<!-- ======================= -->
<!-- Service -->
<!-- ======================= -->
<div class="cv-section">
  <h2>Professional Service</h2>
  <p><strong>Peer Reviewer</strong></p>
  <ul>
    <li>International Conference on AI in Healthcare (AIiH 2025)</li>
    <li>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2024–2025)</li>
    <li>Proceedings of Machine Learning Research (PMLR)</li>
    <li>IEEE Int’l Symposium on Industrial Electronics (ISIE 2024)</li>
  </ul>

  <p><strong>Organising Committee</strong></p>
  <ul>
    <li><a href="https://uk-ai.org/ukai2025/">The Third UK AI Conference 2025</a></li>
  </ul>

  <p><strong>Editorial Role</strong></p>
  <ul>
    <li>Editor, UK AI Proceedings in <a href="https://proceedings.mlr.press/v295/">Proceedings of Machine Learning Research</a></li>
  </ul>
</div>

<!-- ======================= -->
<!-- Publications -->
<!-- ======================= -->
<div class="cv-section">
  <h2>Publications</h2>
  <p>Visit the <a href="{{ site.baseurl }}/publications/">Publications</a> page for an up-to-date list of my publications.</p>
</div>

</div>
