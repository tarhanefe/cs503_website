---
title: Selected Projects
description: Examples of standout work across recent offerings
nav_order: 3
---

# Selected Projects
Examples of standout work across recent offerings

<style>
  /* Container for the grid */
  .project-list {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Exactly 3 columns */
    gap: 1.5rem; /* Space between cards */
    margin-bottom: 3rem;
  }

  /* The Card Container */
  .project-card {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    overflow: hidden;
    text-decoration: none; /* Remove underline from links */
    color: inherit; /* Keep text color normal */
    display: flex;
    flex-direction: column;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    height: 100%; /* Ensure full height in grid */
  }

  /* Hover Effects */
  .project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-color: #d0d7de;
    text-decoration: none;
  }

  /* Image Styling */
  .project-image-container {
    width: 100%;
    height: 160px; /* Fixed height for consistency */
    overflow: hidden;
    background-color: #f6f8fa;
    border-bottom: 1px solid #eaecef;
  }

  .project-image {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures image fills the box without stretching */
    display: block;
  }

  /* Text Content */
  .project-content {
    padding: 1.25rem;
    display: flex;
    flex-direction: column;
    flex-grow: 1; /* Pushes content to fill space */
  }

  .project-title {
    margin: 0 0 0.5rem 0;
    font-size: 1.1rem;
    font-weight: 600;
    color: #24292e;
    line-height: 1.3;
  }

  .project-description {
    margin: 0;
    font-size: 0.95rem;
    line-height: 1.5;
    color: #586069;
    /* Optional: Clamp text to 3 lines */
    display: -webkit-box;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
    overflow: hidden;
  }

  /* Responsive Design */
  @media (max-width: 900px) {
    .project-list {
      grid-template-columns: repeat(2, 1fr); /* 2 columns on tablets */
    }
  }

  @media (max-width: 600px) {
    .project-list {
      grid-template-columns: 1fr; /* 1 column on mobile */
    }
    .project-image-container {
      height: 180px; /* Slightly taller image on mobile */
    }
  }
</style>

## 2025

<div class="project-list">
  
  <a href="https://tarhanefe.github.io/CLIPasso3DWebsite/" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="/assets/images/projects/clipasso3d.png" alt="CLIPasso 3D Preview" class="project-image">
    </div>
    <div class="project-content">
      <h3 class="project-title">From Pixels to Wireframes</h3>
      <p class="project-description">
        Extending sketch abstraction from 2D to 3D by constructing wireframe-like structures using optimized Bézier curves and constrained Gaussian splatting.
      </p>
    </div>
  </a>

  <a href="https://example.com/project-robust-multimodal" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="/assets/images/790-placeholder.png" alt="Robust Multimodal Preview" class="project-image">
    </div>
    <div class="project-content">
      <h3 class="project-title">Robust Multimodal Retrieval</h3>
      <p class="project-description">
        Designed a contrastive pretraining recipe that stays accurate under occlusions, boosting zero-shot retrieval on out-of-domain photos.
      </p>
    </div>
  </a>

</div>

## 2024

<div class="project-list">

  <a href="https://example.com/project-open-set" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="/assets/images/790-placeholder.png" alt="Open Set Preview" class="project-image">
    </div>
    <div class="project-content">
      <h3 class="project-title">Open-Set Scene Detection</h3>
      <p class="project-description">
        Introduced uncertainty-aware prompts for vision transformers, improving detection of unseen classes in driving scenes.
      </p>
    </div>
  </a>

  <a href="https://example.com/project-human-motion" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="/assets/images/790-placeholder.png" alt="Motion Synthesis Preview" class="project-image">
    </div>
    <div class="project-content">
      <h3 class="project-title">Text-to-Motion Synthesis</h3>
      <p class="project-description">
        Built a diffusion model that translates free-form text into physically plausible human motion clips with style control.
      </p>
    </div>
  </a>

  <a href="https://example.com/project-3d-recon" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="/assets/images/790-placeholder.png" alt="3D Reconstruction Preview" class="project-image">
    </div>
    <div class="project-content">
      <h3 class="project-title">Few-Shot 3D Reconstruction</h3>
      <p class="project-description">
        Combined NeRF distillation with geometric priors to recover consistent meshes from as few as three posed images.
      </p>
    </div>
  </a>

</div>