---
layout: page
permalink: /cv/
title: CV
description: Download my CV
nav: true
nav_order: 3
---

<!-- _pages/cv.md -->

<div class="cv-container">
  <div class="text-center">
    <h1>Curriculum Vitae</h1>
    <p>Click the button below to download my CV in PDF format.</p>
    
    <a href="{{ '/assets/pdf/CV.pdf' | relative_url }}" 
       class="btn btn-primary btn-lg" 
       target="_blank" 
       rel="noopener noreferrer">
      <i class="fas fa-download"></i> Download CV (PDF)
    </a>
  </div>
</div>

<style>
.cv-container {
  padding: 2rem 0;
  min-height: 60vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cv-container h1 {
  margin-bottom: 1rem;
  color: var(--global-text-color);
}

.cv-container p {
  margin-bottom: 2rem;
  color: var(--global-text-color-light);
  font-size: 1.1rem;
}

.btn-primary {
  background-color: var(--global-theme-color);
  border-color: var(--global-theme-color);
  padding: 0.75rem 2rem;
  font-size: 1.1rem;
  border-radius: 0.5rem;
  transition: all 0.3s ease;
}

.btn-primary:hover {
  background-color: var(--global-hover-color);
  border-color: var(--global-hover-color);
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.btn-primary i {
  margin-right: 0.5rem;
}
</style>
