---
layout: default
---

Hi! I'm Philip, a graduate student at the University of Toronto in the department of Statistical Sciences. I have have a deep interest in machine learning, and mathematical optimization. My current research focuses on investigating the intrinsic biases of deep learning models within time series data. I enjoy exploring how high-capacity models represent complex information and identifying where they succeed or fail across different domains.

---
<section id="projects" class="projects-section">
<h2>Projects</h2>

<div class="filter-bar">
  <button class="filter-btn active" data-filter="all">All</button>
  <button class="filter-btn" data-filter="python">Python</button>
  <button class="filter-btn" data-filter="r">R</button>
  <button class="filter-btn" data-filter="sql">SQL</button>
</div>

<div id="no-results" style="display:none; color:#666; margin-top:1.5rem;">No projects found for this filter.</div>

<div class="projects-grid">

  <!-- ── Python projects ── -->
  <div class="project-card" data-lang="python">
    <span class="lang-badge python">Python</span>
    <span class="status-badge in-progress">In Progress</span>
    <span class="date-badge">2026</span>
    <h3><a href="https://github.com/ploewen/Trajectory_Prediction " target="_blank">nuScenes Trajectory Prediction</a></h3>
    <p>A comparative study of RNN and Transformer architectures for forecasting autonomous agent trajectories using standardized spatio-temporal preprocessing.</p>
  </div>

  <div class="project-card" data-lang="python">
    <span class="lang-badge python">Python</span>
    <span class="status-badge in-progress">In Progress</span>
    <span class="date-badge">2026</span>
    <h3><a href="https://github.com/ploewen/zooplankton" target="_blank">Zooplankton Hierarchical Classification</a></h3>
    <p>A hybrid CNN-RNN architecture that treats hierarchical zooplankton identification as a sequence prediction task to achieve high-precision taxonomic classification.</p>
  </div>

  <div class="project-card" data-lang="python">
    <span class="lang-badge python">Python</span>
    <span class="date-badge">2025</span>
    <h3><a href="https://github.com/ploewen/CDTSFM" target="_blank">Cross Domain Time Series Foundation Models</a></h3>
    <p>A geometric audit of time series foundation models revealing that lightweight custom features often outperform massive pre-trained architectures in non-stationary domains.</p>
  </div>

<div class="project-card" data-lang="r">
    <span class="lang-badge r">R</span>
    <span class="date-badge">2024</span>
    <h3><a href="https://github.com/ploewen/internet_speed" target="_blank">UBCSecure Upload Speed Analysis</a></h3>
    <p>A full factorial experiment designed to determine which factors most impact upload speeds on the UBCSecure network.</p>
  </div>

  <div class="project-card" data-lang="r">
    <span class="lang-badge r">R</span>
    <span class="date-badge">2024</span>
    <h3><a href="https://github.com/ploewen/heart_disease" target="_blank">Understanding and Predicting Heart Disease </a></h3>
    <p>A statistical analysis of clinical heart disease predictors using logistic regression with LASSO and Ridge regularization.</p>
  </div>

 <div class="project-card" data-lang="python">
    <span class="lang-badge python">Python</span>
    <span class="date-badge">2023</span>
    <h3><a href="https://github.com/ploewen/Math_340_Project" target="_blank">Optimal Water Allocation for Agricultural Production in British Columbia</a></h3>
    <p>A linear programming approach to optimizing water allocation across diverse agricultural sectors in British Columbia to maximize industry revenue during extreme drought.</p>
  </div>

  <!-- ── R projects ── -->
  <div class="project-card" data-lang="r">
    <span class="lang-badge r">R</span>
    <span class="date-badge">2023</span>
    <h3><a href="https://github.com/ploewen/Stat_306_Project" target="_blank">Logistic Regression: Death following Heart Failure</a></h3>
    <p>A multivariate logistic regression analysis that achieves 86% accuracy in predicting heart failure mortality by optimizing feature selection through AIC, BIC, and Principal Component Analysis.</p>
  </div>

  <!-- ── SQL projects ── -->
<!--   
  <div class="project-card" data-lang="sql">
    <span class="lang-badge sql">SQL</span>
    <span class="date-badge">Date TBD</span>
    <h3><a href="https://github.com/ploewen/your-repo-5" target="_blank">Project Title 5</a></h3>
    <p>Short description of what this project does and what problem it solves.</p>
  </div> -->
</div>
</section>

---
<section id="course-notes" class="notes-section">
  <h2>Select Course Notes</h2>
  <div class="notes-grid">
    <div class="note-card">
      <span class="note-badge">Mathematics</span>
      <span class="date-badge">2024</span>
      <h3><a href="/assets/notes/Lecture_notes_310.pdf" target="_blank">MATH 310: Abstract Linear Algebra</a></h3>
    </div>
    
   <div class="note-card">
      <span class="note-badge">Mathematics</span>
      <span class="date-badge">2024</span>
      <h3><a href="/assets/notes/Lecture_Notes_321.pdf" target="_blank">MATH 321: Real Variables II</a></h3>
    </div>
  </div>
</section>

<style>
/* ── Filter bar ── */
.filter-bar {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  margin: 1.75rem 0 1.5rem;
}

.filter-btn {
  padding: 7px 22px;
  border: 2px solid #235579;
  background: transparent;
  color: #235579;
  border-radius: 20px;
  cursor: pointer;
  font-size: 0.9rem;
  font-weight: 700;
  letter-spacing: 0.03em;
  transition: background 0.15s, color 0.15s;
}

.filter-btn:hover,
.filter-btn.active {
  background: #235579;
  color: #fff;
}

/* ── Project grid ── */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.25rem;
  margin-top: 0.5rem;
}

.projects-section {
  margin-top: 3.5rem;
}

.projects-section h2 {
  margin-bottom: 0.5rem;
}

.notes-section {
  margin-top: 3.5rem;
}

.notes-section h2 {
  margin-bottom: 0.5rem;
}

.projects-section h2,
.notes-section h2 {
  color: #235579;
}

.section-intro {
  margin-bottom: 1.25rem;
  color: #52606d;
}

.notes-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.25rem;
}

.project-card {
  position: relative;
  border: 1px solid #d1d9e0;
  border-radius: 8px;
  padding: 1.25rem 1.5rem 1.5rem;
  background: #fff;
  transition: transform 0.15s, box-shadow 0.15s;
}

.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.note-card {
  position: relative;
  border: 1px solid #d1d9e0;
  border-radius: 8px;
  padding: 1.25rem 1.5rem 1.5rem;
  background: #fcfcfd;
  transition: transform 0.15s, box-shadow 0.15s;
}

.note-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.project-card h3 {
  margin: 0.5rem 0 0.6rem;
  font-size: 1.1rem;
}

.note-card h3 {
  margin: 0.75rem 0 0.6rem;
  font-size: 1.1rem;
}

.project-card h3 a {
  color: #1e6bb8;
  text-decoration: none;
}

.note-card h3 a {
  color: #1e6bb8;
  text-decoration: none;
}

.project-card h3 a:hover {
  text-decoration: underline;
}

.note-card h3 a:hover {
  text-decoration: underline;
}

.project-card p {
  margin: 0;
  font-size: 0.95rem;
  color: #444;
  line-height: 1.5;
}

.note-card p {
  margin: 0;
  font-size: 0.95rem;
  color: #444;
  line-height: 1.5;
}

/* ── Language badges ── */
.lang-badge {
  display: inline-block;
  padding: 2px 10px;
  border-radius: 12px;
  font-size: 0.72rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.lang-badge.python {
  background: #ddeeff;
  color: #1a5276;
  border: 1px solid #aac8e8;
}

.lang-badge.r {
  background: #f4e8f4;
  color: #5e1a50;
  border: 1px solid #d5a2cf;
}

.lang-badge.sql {
  background: #fff3e0;
  color: #7d4e0f;
  border: 1px solid #f5c070;
}

.status-badge {
  display: inline-block;
  margin-left: 8px;
  padding: 2px 10px;
  border-radius: 12px;
  font-size: 0.72rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.status-badge.in-progress {
  background: #ffe3d1;
  color: #8f3a00;
  border: 1px solid #ffb37e;
}

.note-badge {
  display: inline-block;
  padding: 2px 10px;
  border-radius: 12px;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  background: #e8eefc;
  color: #25408f;
  border: 1px solid #bfd0f7;
}

.date-badge {
  position: absolute;
  top: 12px;
  right: 12px;
  display: inline-block;
  padding: 2px 8px;
  border-radius: 10px;
  font-size: 0.66rem;
  font-weight: 600;
  letter-spacing: 0.02em;
  background: #f5f7fa;
  color: #4b5563;
  border: 1px solid #d8dee9;
}
</style>

<script>
(function () {
  const buttons = document.querySelectorAll('.filter-btn');
  const cards   = document.querySelectorAll('.project-card');
  const noResults = document.getElementById('no-results');

  buttons.forEach(function (btn) {
    btn.addEventListener('click', function () {
      const filter = btn.getAttribute('data-filter');

      // Update active button
      buttons.forEach(function (b) { b.classList.remove('active'); });
      btn.classList.add('active');

      // Show/hide cards
      let visible = 0;
      cards.forEach(function (card) {
        const show = filter === 'all' || card.getAttribute('data-lang') === filter;
        card.style.display = show ? '' : 'none';
        if (show) visible++;
      });

      noResults.style.display = visible === 0 ? '' : 'none';
    });
  });
}());
</script>
