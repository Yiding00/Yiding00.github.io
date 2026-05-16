---
permalink: /
title: ""
redirect_from:
  - /about/
  - /about.html
---

<div class="homepage-profile">
  <img src="{{ '/images/me2.jpg' | prepend: site.baseurl }}" alt="Yiding Wang" class="homepage-avatar">
  <div>
    <div class="homepage-name">Yiding Wang</div>
    <p class="homepage-bio">Ph.D. Student in Mathematics, Xi'an Jiaotong University</p>
  </div>
</div>

<div style="margin-bottom:2em;">
  <div class="homepage-links">
    <a href="mailto:ytcur1@stu.xjtu.edu.cn"><i class="fas fa-fw fa-envelope"></i> Email</a>
    <a href="https://scholar.google.com/citations?user=xCTmZ9kAAAAJ"><i class="ai ai-google-scholar"></i> Google Scholar</a>
    <a href="https://github.com/Yiding00"><i class="fab fa-fw fa-github"></i> GitHub</a>
  </div>
  <div>
    <span class="interest-badge">Causal Discovery</span>
    <span class="interest-badge">Brain Effective Connectivity</span>
    <span class="interest-badge">Identifiability</span>
    <span class="interest-badge">Continuous-Time Modeling</span>
  </div>
</div>

## Research Interests

- **Causal Discovery**: Granger causality, structural causal models, constraint-based and score-based methods
- **Brain Effective Connectivity**: Dynamic effective connectivity networks, fMRI-based causal inference
- **Identifiability**: Identifiability conditions for causal models, structural identifiability analysis
- **Continuous-Time Modeling**: Neural ODE/SDE, latent continuous-time dynamics, irregular time series

## Selected Publications

{% include base_path %}

<ol>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ol>
