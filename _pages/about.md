---
permalink: /
title: ""
redirect_from:
  - /about/
  - /about.html
---

<div class="homepage-profile" style="display:flex;gap:20px;align-items:center;margin-bottom:1.5em;">
  <div style="flex-shrink:0;">
    <img src="{{ '/images/me2.jpg' | prepend: site.baseurl }}" alt="Yiding Wang" style="width:120px;height:120px;border-radius:50%;object-fit:cover;border:2px solid #e0e0e0;box-shadow:0 2px 8px rgba(0,0,0,0.1);">
  </div>
  <div>
    <div style="margin:0 0 4px;font-size:1.4em;font-weight:600;color:#202124;">Yiding Wang</div>
    <p style="color:#5f6368;margin:0;">Ph.D. Student in Mathematics, Xi'an Jiaotong University</p>
  </div>
</div>

<div style="margin-bottom:2em;">
  <div style="display:flex;gap:16px;flex-wrap:wrap;margin-bottom:12px;">
    <a href="mailto:ytcur1@stu.xjtu.edu.cn" style="color:#5f6368;font-size:0.85em;"><i class="fas fa-fw fa-envelope"></i> Email</a>
    <a href="https://scholar.google.com/citations?user=xCTmZ9kAAAAJ" style="color:#5f6368;font-size:0.85em;"><i class="ai ai-google-scholar"></i> Google Scholar</a>
    <a href="https://github.com/Yiding00" style="color:#5f6368;font-size:0.85em;"><i class="fab fa-fw fa-github"></i> GitHub</a>
  </div>
  <div>
    <span class="interest-badge">Causal Discovery</span>
    <span class="interest-badge">Brain Connectivity</span>
    <span class="interest-badge">Dynamic ECN</span>
    <span class="interest-badge">Machine Learning</span>
    <span class="interest-badge">fMRI Analysis</span>
  </div>
</div>

## Research Interests

- **Causal Discovery**: Granger causality, dynamic causal modeling, distribution learning
- **Brain Connectivity**: Dynamic effective connectivity networks, functional brain networks
- **Machine Learning**: Graph neural networks, spatio-temporal deep learning, explainable AI

## Selected Publications

{% include base_path %}

<ol>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ol>
