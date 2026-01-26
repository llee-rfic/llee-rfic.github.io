---
layout: single
author_profile: true
title: "Projects"
---
<style>
.paper-item {
  display: flex;
  gap: 25px;
  margin-bottom: 40px;
  align-items: flex-start;
  border-bottom: 1px solid #eee;
  padding-bottom: 20px;
}

.paper-img-col {
  flex: 0 0 280px; 
  max-width: 280px;
}

.paper-img-col img {
  width: 100%;
  border: 1px solid #e0e0e0;
  padding: 3px;
  box-shadow: 2px 2px 5px rgba(0,0,0,0.05);
  border-radius: 3px;
}

.paper-content-col {
  flex: 1; 
}

.paper-title {
  display: block;
  font-size: 1.15em;
  font-weight: 700;
  /* THE RED TITLE */
  color: #d32f2f !important; 
  text-decoration: none;
  margin-bottom: 8px;
  line-height: 1.3;
}

.paper-title:hover {
  text-decoration: underline;
  color: #b71c1c !important; 
}

.paper-authors {
  color: #444;
  font-size: 0.95em;
  margin-bottom: 12px;
  line-height: 1.5;
}

.paper-buttons {
  margin-top: 10px;
}

/* --- BUTTONS UPDATED HERE --- */
.badge-btn {
  display: inline-flex;
  align-items: center;
  background-color: #fff; /* Start white */
  color: #d32f2f !important; /* Red text */
  border: 1px solid #d32f2f; /* Red border */
  padding: 4px 10px;
  border-radius: 4px;
  font-size: 0.85em;
  font-weight: 600;
  text-decoration: none !important;
  margin-right: 8px;
  transition: all 0.2s ease-in-out; /* Smooth animation */
}

/* HOVER EFFECT: Fills with red */
.badge-btn:hover {
  background-color: #d32f2f !important; /* Turns solid red */
  color: #fff !important; /* Text turns white */
  box-shadow: 0 2px 5px rgba(211, 47, 47, 0.3); /* Adds a little glow */
}
/* ---------------------------- */

.badge-btn i {
  margin-right: 5px;
}

@media (max-width: 768px) {
  .paper-item { flex-direction: column; }
  .paper-img-col { flex: 0 0 auto; max-width: 100%; width: 100%; }
}
</style>

<div class="paper-item">
  <div class="paper-img-col">
    <img src="/assets/images/cover_photo_drpf25.png" alt="Matrix Multiplication">
  </div>
  <div class="paper-content-col">
    <a href="/assets/documents/drp_f25_presentation.pdf" class="paper-title">
      Approximating Matrix Multiplication via Randomized Linear Algebra
    </a>
    <div class="paper-authors">
      <strong>Linyang Lee</strong>, Justin Toyota (Mentor)
    </div>
    <p style="font-size: 0.9em; color: #666; margin-bottom: 10px;">
      An introduction to the intuition behind Randomized Linear Algebra. Approximating large-scale matrix multiplication with a norm-squared sampling of rank-1 matrices. Given as a talk at the Fall 2025 UT Austin DRP Symposium.
    </p>
    <div class="paper-buttons">
      <a href="/assets/documents/drp_f25_presentation.pdf" class="badge-btn">
        <i class="fas fa-file-pdf"></i> PDF Slides
      </a>
    </div>
  </div>
</div>
