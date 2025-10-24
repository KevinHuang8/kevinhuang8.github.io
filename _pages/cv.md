---
layout: page
permalink: /cv/
title: CV
description: View my CV
nav: true
nav_order: 3
---

<!-- _pages/cv.md -->

<div class="cv-container">
  <iframe src="{{ '/assets/pdf/CV.pdf' | relative_url }}" 
          width="100%" 
          height="800px" 
          style="border: none; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <p>Your browser does not support PDFs. 
       <a href="{{ '/assets/pdf/CV.pdf' | relative_url }}" target="_blank">Download the CV instead</a>.
    </p>
  </iframe>
</div>

<style>
.cv-container {
  padding: 2rem 0;
  max-width: 100%;
  margin: 0 auto;
}

@media (max-width: 768px) {
  .cv-container iframe {
    height: 600px;
  }
}

@media (max-width: 480px) {
  .cv-container iframe {
    height: 500px;
  }
}
</style>
