---
layout: default
title: Home
permalink: /
---

<div class="intro">
  <div class="intro-photo">
    <img src="{{ '/assets/img/headshot.jpeg' | relative_url }}" alt="Polina Lee">
  </div>
  <div class="intro-text">
    <p class="intro-name">Polina Lee</p>
    <p>4th year biomedical engineering undergraduate at The University of Texas at
    Austin. I have experience in <strong>electrochemical biomarker sensing, MRI phantoms, and ML-based dementia detection.</strong></p>
    <p><strong>Looking for</strong> — full time graduate or industry positions in
    point-of-need medicine or microplastics research.</p>
  </div>
</div>

## Strongest projects

<!-- The whole card is the <a>, so image and title are one click target.
     Thumbnails deliberately reuse the same files as the Projects-page slots
     rather than separate card-*.jpg crops, so there's one copy to update. -->

<div class="proj-cards">

  <a class="proj-card" href="{{ '/projects/#chang' | relative_url }}">
    <div class="img-slot"><img src="{{ '/assets/img/signals_built.png' | relative_url }}" alt=""></div>
    <span class="proj-card-title">Gait-based random forest screen for early cognitive impairment</span>
  </a>

  <a class="proj-card" href="{{ '/projects/#tetrel' | relative_url }}">
    <div class="img-slot img-slot--fill"><img src="{{ '/assets/img/tetrel_built.png' | relative_url }}" alt=""></div>
    <span class="proj-card-title">Assay and signal model for a printed-electrode protein sensor</span>
  </a>

  <a class="proj-card" href="{{ '/projects/#afrl' | relative_url }}">
    <div class="img-slot img-slot--fill"><img src="{{ '/assets/img/afrl_methods_intensity.png' | relative_url }}" alt=""></div>
    <span class="proj-card-title">Multimodal phantom for preclinical-scale MRI validation</span>
  </a>

</div>
