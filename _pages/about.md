---
permalink: /
title: "Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I’m Xinyi Yang, a PhD researcher in Robotics at Georgia Tech.
My work sits at the intersection of aerospace, structures, and mechanism design, with a strong focus on novel mechanical systems, robotics dynamics, and adaptive materials.

I am especially interested in:
- Designing and fabricating programmable structures that adapt to their environment;
- Developing inverse design for robotics and materials;
- Exploring multidisciplinary approaches that bridge engineering, design, and fabrication.

Outside of research, I enjoy hands-on prototyping, data-driven analysis, and collaborative projects that connect robotics with broader applications in aerospace systems and human-centered design.

Research
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

<div class="research-list">

  <div class="item">
    <div class="media">
      <img src="/images/1.gif" alt="Quadrotor–pendulum dynamics">
    </div>
    <div class="meta">
      <h3>Physics-guided clustering for quadrotor–pendulum dynamics</h3>
      <p>Two-level clustering of flight trajectories to reveal regime structure and guide sequence models for inverse design.</p>
      <p><strong>DOI:</strong> <a href="https://doi.org/10.1234/placeholder">10.1234/placeholder</a></p>
    </div>
  </div>

  <div class="item">
    <div class="media">
      <img src="/images/1.gif" alt="Self-disassembly cube">
    </div>
    <div class="meta">
      <h3>Self-disassembly modular structures</h3>
      <p>Vibration-triggered interconnects for programmable assembly and release in lightweight lattices.</p>
      <p><strong>DOI:</strong> <a href="https://doi.org/10.1234/placeholder2">10.1234/placeholder2</a></p>
    </div>
  </div>

  <div class="item">
    <div class="media">
      <img src="/images/1.gif" alt="Bistable TPU-fabric morphing">
    </div>
    <div class="meta">
      <h3>Bistable morphing via printed TPU on stretch fabric</h3>
      <p>Planar prints that pop into 3D domes with tunable snap-through for deployable mechanisms.</p>
      <p><strong>DOI:</strong> <a href="https://doi.org/10.1234/placeholder3">10.1234/placeholder3</a></p>
    </div>
  </div>

</div>

<style>
.research-list .item { display: flex; align-items: center;   /* aligns gif + text vertically */ gap: 16px; margin: 24px 0;}
.research-list .media img { max-width: 300px; height: 100%;   /* stretch image to fill height of text */ object-fit: cover; /* keeps aspect ratio without distortion */}
.research-list .meta { flex:1; }
@media (max-width: 640px) { .research-list .item { flex-direction:column; } }
</style>

