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
  
  <a href="{{site.baseurl}}/assets/pdfs/dit_edit.pdf" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/dit_edit.png" alt="DiT-Edit" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">DiT-Edit: An Image Editing Framework for Diffusion Transformers</div>
      <div class="project-desc-text">
        A training-free image composition framework for Diffusion Transformers that unifies noise composition, QKV patching, and timestep control to seamlessly insert foreground objects into backgrounds.
      </div>
    </div>
  </a>

  <a href="https://tarhanefe.github.io/CLIPasso3DWebsite/" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/clipasso3d.png" alt="CLIPasso 3D" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">From Pixels to Wireframes: 3D Reconstruction via CLIP-Based Sketch Abstraction
      </div>
      <div class="project-desc-text">
        Extending sketch abstraction from 2D to 3D by constructing wireframe-like structures using optimized Bézier curves.
      </div>
    </div>
  </a>

  <a href="{{site.baseurl}}/assets/pdfs/retinal_sim.pdf" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/retinal_sim.png" alt="Retinal Implant Simulation" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Deep Learning Approach for Image Classification-Optimized Retinal Implant Stimulation</div>
      <div class="project-desc-text">
        An end-to-end differentiable pipeline that learns retinal implant stimulation patterns (PRIMA, Argus II) optimized for image classification using percept simulations.
      </div>
    </div>
  </a>

  <a href="{{site.baseurl}}/assets/pdfs/zero_shot_mm_vision.pdf" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/zero_shot_mm_vision.png" alt="Zero Shot MM" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Exploring Zero-Shot Translation in Multi-Modal Vision Models</div>
      <div class="project-desc-text">
        An empirical study showing that a large multimodal generative model (4M) can perform zero-shot modality translation without aligned training pairs when sufficient binding modalities exist.
      </div>
    </div>
  </a>
</div>

## 2024

<div class="project-list">

  <a href="https://ahmad-jarrar.github.io/cs503-vi-project/" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/vision_is_ayn.png" alt="Vision is All You Need" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Vision Is All You Need: A Vision-Based Approach to Dynamics Estimation in Autonomous Navigation</div>
      <div class="project-desc-text">
        This project investigates using solely visual input for autonomous drone navigation in dynamic environments, training policies that navigate through gates and avoid projectiles based on camera observations.
      </div>
    </div>
  </a>

  <a href="{{site.baseurl}}/assets/pdfs/vision_evolution.pdf" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/vision_evolution.png" alt="Vision Evolution" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Vision Evolution: Natural Selection Shaped by Environment</div>
      <div class="project-desc-text">
        This project studies how an agent’s visual perception (number of eyes and field of view) adapts to its environment under energy constraints while learning to gather resources.
      </div>
    </div>
  </a>
</div>

## 2023  

<div class="project-list">

  <a href="https://arvind6599.github.io/PredatorPreyWebsite/" target="_blank" class="project-card">
    <div class="project-image-container">
      <img src="{{site.baseurl}}/assets/images/projects/predator_prey.png" alt="Predator-Prey" class="project-image">
    </div>
    <div class="project-content">
      <div class="project-title-text">Hunting for Insights: Investigating Predator-Prey Dynamics through Simulated Vision and Reinforcement Learning
      </div>
      <div class="project-desc-text">
        This study analyzes how vision characteristics shape predator–prey interactions using reinforcement learning in simulated environments. Results show that depth perception benefits predators, while a wide field of view aids prey. The framework also enables further exploration of complex interaction dynamics.
      </div>
    </div>
  </a>
</div>

## More Example Projects & Inspiration

- [ViZDoom](https://github.com/mwydmuch/ViZDoom#awesome-doom-toolsprojects)
- [OpenAI Gym Third-Party Environments](https://github.com/openai/gym/blob/master/docs/third_party_environments.md)
- [DeepMindLab](https://github.com/deepmind/lab#)
- [Habitat](https://aihabitat.org/tutorial/2020/)
- [Gibson/iGibson](http://svl.stanford.edu/igibson/docs/)
- [ThreeDWorld](https://www.threedworld.org/)
- [AI2THOR Environments](https://ai2thor.allenai.org/)
- [RL Baselines3 Zoo](https://github.com/DLR-RM/rl-baselines3-zoo)
- [Habitat Challenge](https://aihabitat.org/challenge/2021/)
- [AWS DeepRacer](https://aws.amazon.com/deepracer/)
- [EmbodiedAI Workshop Challenges](https://embodied-ai.org/#challenges)
- [ImageNet Generalization](https://arxiv.org/abs/1902.10811)
- [Metric Learning Reality Check](https://arxiv.org/abs/2003.08505)
- [Cheating on Visual Kinship Challenges](https://arxiv.org/abs/1809.06200)
- [Mid-Level Visual Representations](http://perceptual.actor/)
- [Gibson Environment](http://gibsonenv.stanford.edu/)
- [Cross-Task Consistency](https://consistency.epfl.ch/)
- [Cross-Domain Ensembles](https://crossdomain-ensembles.epfl.ch/)
- [Semantically-Aware Sketching](https://clipasso.github.io/clipasso/)
- [3D Corruptions / Augmentations](https://3dcommoncorruptions.epfl.ch/)
- [Multi-Modal / Multi-Task Learning](https://multimae.epfl.ch/)
- [Long-Horizon Planning](https://palmer.epfl.ch/)
- [Task Discovery](https://taskdiscovery.epfl.ch/)
- [Modality-Invariant Visual Odometry](https://embodied-ai.org/papers/2022/17.pdf)
