---
title: Selected Projects
description: Examples of standout work across recent offerings
nav_order: 3
---

# Selected Projects
Examples of standout work across recent offerings

<style>
  /* 1. Grid Layout - Fixed 3 columns */
  .project-list {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-bottom: 40px;
    box-sizing: border-box;
  }

  /* 2. The Card - Force Block behavior to override theme defaults */
  a.project-card {
    display: flex !important; /* Force flex layout */
    flex-direction: column !important;
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    overflow: hidden;
    text-decoration: none !important; /* Kill theme underline */
    color: #333 !important; /* Force readable text color */
    height: 100%;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }

  /* Hover effect */
  a.project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-color: #0366d6; /* Highlight border on hover */
  }

  /* 3. Image Container - FIXED HEIGHT so it never collapses */
  .project-image-container {
    width: 100%;
    height: 180px; /* Force height even if image breaks */
    background-color: #f6f8fa; /* Light gray placeholder background */
    border-bottom: 1px solid #eaecef;
    flex-shrink: 0; /* Prevent shrinking */
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
  }

  .project-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  /* 4. Content Area */
  .project-content {
    padding: 15px;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    text-align: left; /* Reset alignment */
  }

  /* Title - Switched to div to avoid parser issues */
  .project-title-text {
    margin: 0 0 8px 0 !important;
    font-size: 16px !important;
    font-weight: 700 !important;
    color: #24292e !important;
    line-height: 1.4 !important;
    display: block;
  }

  /* Description */
  .project-desc-text {
    margin: 0 !important;
    font-size: 14px !important;
    line-height: 1.5 !important;
    color: #586069 !important;
    display: block;
  }

  /* Responsive Mobile Fallback */
  @media (max-width: 900px) {
    .project-list {
      grid-template-columns: repeat(2, 1fr);
    }
  }
  @media (max-width: 600px) {
    .project-list {
      grid-template-columns: 1fr;
    }
  }
</style>

## 2025

<div class="project-list">
  
  <a href="https://tarhanefe.github.io/CLIPasso3DWebsite/" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler1.png" alt="CLIPasso 3D" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">From Pixels to Wireframes</div>
      <div class="project-desc-text">
        Extending sketch abstraction from 2D to 3D by constructing wireframe-like structures using optimized Bézier curves.
      </div>
    </div>
  </a>

  <a href="https://example.com/project-robust-multimodal" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler2.png" alt="Robust Multimodal" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Robust Multimodal Retrieval</div>
      <div class="project-desc-text">
        Designed a contrastive pretraining recipe that stays accurate under occlusions, boosting zero-shot retrieval.
      </div>
    </div>
  </a>

</div>

## 2024

<div class="project-list">

  <a href="https://example.com/project-open-set" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler1.png" alt="Open Set" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Open-Set Scene Detection</div>
      <div class="project-desc-text">
        Introduced uncertainty-aware prompts for vision transformers, improving detection of unseen classes in driving scenes.
      </div>
    </div>
  </a>

  <a href="https://example.com/project-human-motion" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler2.png" alt="Motion Synthesis" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Text-to-Motion Synthesis</div>
      <div class="project-desc-text">
        Built a diffusion model that translates free-form text into physically plausible human motion clips with style control.
      </div>
    </div>
  </a>

  <a href="https://example.com/project-3d-recon" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler3.png" alt="3D Reconstruction" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Few-Shot 3D Reconstruction</div>
      <div class="project-desc-text">
        Combined NeRF distillation with geometric priors to recover consistent meshes from as few as three posed images.
      </div>
    </div>
  </a>

</div>


## 2023

<div class="project-list">

  <a href="https://example.com/project-open-set" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler1.png" alt="Open Set" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Open-Set Scene Detection</div>
      <div class="project-desc-text">
        Introduced uncertainty-aware prompts for vision transformers, improving detection of unseen classes in driving scenes.
      </div>
    </div>
  </a>

  <a href="https://example.com/project-human-motion" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler2.png" alt="Motion Synthesis" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Text-to-Motion Synthesis</div>
      <div class="project-desc-text">
        Built a diffusion model that translates free-form text into physically plausible human motion clips with style control.
      </div>
    </div>
  </a>

  <a href="https://example.com/project-3d-recon" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler3.png" alt="3D Reconstruction" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Few-Shot 3D Reconstruction</div>
      <div class="project-desc-text">
        Combined NeRF distillation with geometric priors to recover consistent meshes from as few as three posed images.
      </div>
    </div>
  </a>

  <a href="https://example.com/project-3d-recon" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler4.png" alt="3D Reconstruction" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Few-Shot 3D Reconstruction</div>
      <div class="project-desc-text">
        Combined NeRF distillation with geometric priors to recover consistent meshes from as few as three posed images.
      </div>
    </div>
  </a>

  <a href="https://example.com/project-3d-recon" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/filler5.png" alt="3D Reconstruction" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Few-Shot 3D Reconstruction</div>
      <div class="project-desc-text">
        Combined NeRF distillation with geometric priors to recover consistent meshes from as few as three posed images.
      </div>
    </div>
  </a>
  
  
</div>