---
title: Selected Projects
description: Examples of standout work across recent offerings
nav_order: 3
#nav_exclude: true

---

# Selected Projects
Examples of standout work across recent offerings

<style>
.project-year {
  margin-top: 2.5rem;
  margin-bottom: 1.25rem;
}
.project-list {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
  align-items: stretch;
}
.project-card {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 12px;
  overflow: hidden;
  background: #f8f9fb;
  color: inherit;
  text-decoration: none;
  box-shadow: 0 6px 20px rgba(0,0,0,0.08);
  transition: transform 0.15s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  border: 1px solid transparent;
  width: 100%;
}
.project-card:hover, .project-card:focus {
  transform: translateY(-3px);
  box-shadow: 0 12px 28px rgba(0,0,0,0.12);
  border-color: #d7e3ff;
  outline: none;
}
.project-card .project-title {
  margin: 0;
  padding: 1rem 1.1rem 0.4rem;
  font-size: 1.05rem;
}
.project-card .project-image {
  width: 100%;
  height: 200px;
  object-fit: cover; /* crop to fixed size */
  display: block;
}
.project-card .project-description {
  margin: 0;
  padding: 0 1.1rem 1.2rem;
  color: #4a4f5a;
  font-size: 0.94rem;
}

@media (max-width: 900px) {
  .project-list {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
@media (max-width: 640px) {
  .project-list {
    grid-template-columns: 1fr;
  }
  .project-card .project-image {
    width: 100%;
    height: 180px;
  }
}
</style>

## 2025

<div class="project-list">
  {% include project-card.html
    title="From Pixels to Wireframes: 3D Reconstruction via CLIP-Based Sketch Abstraction"
    description="This project explores extending sketch abstraction from 2D images to 3D representations by constructing wireframe-like structures using optimized Bézier curves and a constrained Gaussian splatting formulation. By limiting Gaussians to matte, single-color spherical blobs placed along curve paths, the approach yields compact, interpretable, and visually expressive 3D sketches that capture object structure effectively."
    img="/assets/projects/clipasso3d.png"
    alt="Preview"
    link="https://tarhanefe.github.io/CLIPasso3DWebsite/"
  %}
  {% include project-card.html
    title="Robust Multimodal Retrieval"
    description="Designed a contrastive pretraining recipe that stays accurate under occlusions, boosting zero-shot retrieval on out-of-domain photos."
    img="/assets/img/projects/robust-multimodal.jpg"
    alt="Robust multimodal model preview"
    link="https://example.com/project-robust-multimodal"
  %}
</div>

## 2024

<div class="project-list">
  {% include project-card.html
    title="Open-Set Scene Detection"
    description="Introduced uncertainty-aware prompts for vision transformers, improving detection of unseen classes in driving scenes."
    img="/assets/img/projects/open-set.jpg"
    alt="Open set detection preview"
    link="https://example.com/project-open-set"
  %}
  {% include project-card.html
    title="Text-to-Motion Synthesis"
    description="Built a diffusion model that translates free-form text into physically plausible human motion clips with style control."
    img="/assets/img/projects/human-motion.jpg"
    alt="Human motion synthesis preview"
    link="https://example.com/project-human-motion"
  %}
  {% include project-card.html
    title="Few-Shot 3D Reconstruction"
    description="Combined NeRF distillation with geometric priors to recover consistent meshes from as few as three posed images."
    img="/assets/img/projects/3d-recon.jpg"
    alt="3D reconstruction preview"
    link="https://example.com/project-3d-recon"
  %}
</div>

