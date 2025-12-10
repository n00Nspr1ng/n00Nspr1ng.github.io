---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a Ph.D. student in Mechanical Engineering at University of California, Berkeley. I work in the [ICON Lab](https://iconlab.negarmehr.com/) under Prof. [Negar Mehr](https://negarmehr.com/). My research focuses on robot learning, especially on developing autonomous robots that can work alongside humans and other robots.

Prior to Berkeley, I earned my B.S. in Mechanical Engineering from Yonsei University. During my undergraduate studies, I worked as a research intern in [MLCS Lab](https://mlcs.yonsei.ac.kr/) under Prof. Jongeun Choi, where I worked on MPCs and RL for autonomous driving, as well as visuamotor policy learning for contact-rich manipulation.


<div style="margin-top: 40px;"></div>

Research
======

<div style="margin-bottom: 20px;"></div>

<!-- My research lies at the intersection of robot learning, control, and foundation models. I study how <span style="color:#003366; font-weight:600;">LLMs and VLMs can guide reinforcement learning</span> to acquire complex, coordinated robot behaviors. This includes building curriculum-driven frameworks such as CRAFT for multi-robot collaboration and extending them toward humanoid whole-body control and multi-humanoid interaction. 

In parallel, I explore scalable <span style="color:#003366; font-weight:600;">imitation learning</span> methods that can transfer single-robot expertise to multi-robot settings, where data collection is especially challenging. Ultimately, I aim to develop autonomous systems that can learn efficiently, coordinate intelligently, and operate safely alongside humans and other robots. -->

My research lies at the intersection of robot learning, control, and foundation models. I study how **LLMs and VLMs can guide reinforcement learning** to acquire complex, coordinated robot behaviors. This includes building curriculum-driven frameworks such as CRAFT for multi-robot collaboration and extending them toward humanoid whole-body control and multi-humanoid interaction. 

In parallel, I explore scalable **imitation learning** methods that can transfer single-robot expertise to multi-robot settings, where data collection is especially challenging. Ultimately, I aim to develop autonomous systems that can learn efficiently, coordinate intelligently, and operate alongside humans and other robots.

<!-- My most recent research direction is integrating foundation models such as LLMs and VLMs with reinforcement learning to learn intricate robot behaviors. I have written CRAFT to learn multi-robot collaboration, and I am extending this work to humanoids, starting from learning a single humanoid whole-body controller, and making up to learing multiple humanoid 
(and with other robots) interactions. This will help in developing robots that can work alongside humans and other robots.

In the other hand, I am also interested in utilizing imitation learning. Imitation learning is a powerful tool to learn the exact "right" behavior, however, it always suffers from data collection (the quality, the size, etc). This gets worse for a multi-robot settings where collecting data when multiple robots are all active is very hard. I am interested in developing methods that can scale well with the number of robots, especially taking a single-robot policy and able to extend it to learning intelligent interaction behavior between multiple robots. -->

<div style="margin-top: 40px;"></div>

News
======

<div style="margin-bottom: 20px;"></div>

<div class="news-table">
<table style="width:100%; border-collapse:separate; border-spacing:0 6px;">
  <tr>
    <td class="news-date" style="width:130px; font-weight:bold; white-space:nowrap;">
      Sep, 2025
    </td>
    <td>
      I am excited to announce that my first first-authored paper <a href="https://arxiv.org/abs/2509.14380">CRAFT</a> is now available in Arxiv.
    </td>
  </tr>

  <tr>
    <td class="news-date" style="font-weight:bold; white-space:nowrap;">
      Jul, 2025
    </td>
    <td>
      I was selected as one of the best 10 research proposals in the Google-BAIR Commons Annual Workshop.
    </td>
  </tr>

  <tr>
    <td class="news-date" style="font-weight:bold; white-space:nowrap;">
      Apr, 2024
    </td>
    <td>
      I will start my Ph.D at UC Berkeley, beginning Fall 2024. 🥳
    </td>
  </tr>
</table>
</div>



<div style="margin-top: 40px;"></div>

Publications
======

<div style="margin-bottom: 20px;"></div>

<div class="pub-card">

  <div class="pub-thumb-wrapper">
    <img src="images/CRAFT.gif" alt="CRAFT Thumbnail" class="pub-thumb">
    <div class="pub-badge">Preprint</div>
  </div>

  <div class="pub-content">
    <a href="https://iconlab.negarmehr.com/CRAFT/" class="pub-title">
      CRAFT: Coaching Reinforcement Learning Autonomously using Foundation Models for Multi-Robot Coordination Tasks
    </a>
    <p>
      <strong>S. Choi*</strong>, K. Ryu*, J. Ock, and N. Mehr  
      <em>(*Equal contribution)</em><br>
      <em>Submitted to ICRA, 2026.</em>
    </p>
    <div class="pub-buttons">
      <a href="https://arxiv.org/abs/2509.14380" class="pub-btn">Arxiv</a>
      <a href="https://iconlab.negarmehr.com/CRAFT/" class="pub-btn">Website</a>
    </div>
  </div>
</div>


<div class="pub-card">

  <div class="pub-thumb-wrapper">
    <img src="images/MIMIC-D.jpg" alt="MIMIC-D Thumbnail" class="pub-thumb">
    <div class="pub-badge">Preprint</div>
  </div>

  <div class="pub-content">
    <a href="https://iconlab.negarmehr.com/MIMIC-D/" class="pub-title">
      MIMIC-D: Multi-modal Imitation for Multi-agent Coordination with Decentralized Diffusion Policies
    </a>
    <p>
      D. Dong*, M. Bhatt*, <strong>S. Choi</strong>, and N. Mehr  
      <em>(*Equal contribution)</em><br>
      <em>Submitted to ICRA, 2026.</em>
    </p>
    <div class="pub-buttons">
      <a href="https://arxiv.org/abs/2509.14159" class="pub-btn">Arxiv</a>
      <a href="https://github.com/labicon/MIMIC-D" class="pub-btn">Code</a>
      <a href="https://iconlab.negarmehr.com/MIMIC-D/" class="pub-btn">Website</a>
    </div>
  </div>
</div>


<div class="pub-card">

  <div class="pub-thumb-wrapper">
    <img src="images/EquiContact.gif" alt="EquiContact Thumbnail" class="pub-thumb">
    <div class="pub-badge">Preprint</div>
  </div>

  <div class="pub-content">
    <a href="https://sites.google.com/berkeley.edu/equicontact" class="pub-title">
      EquiContact: A Hierarchical SE(3) Vision-to-Force Equivariant Policy for Spatially Generalizable Contact-rich Tasks
    </a>
    <p>
      J. Seo, A. Kruthiventy, S. Lee, M. Teng, X. Zhang, <strong>S. Choi</strong>, J. Choi, and R. Horowitz<br>
      <em>Submitted to RA-L.</em>
    </p>
    <div class="pub-buttons">
      <a href="https://arxiv.org/abs/2507.10961" class="pub-btn">Arxiv</a>
      <a href="https://github.com/Joohwan-Seo/EquiContact-Simulation" class="pub-btn">Code</a>
      <a href="https://sites.google.com/berkeley.edu/equicontact" class="pub-btn">Website</a>
    </div>
  </div>
</div>