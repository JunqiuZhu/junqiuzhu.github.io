---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="row" style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <!-- 图片显示在左边，占1/4宽度 -->
  <div class="col-md-3" style="flex: 1; margin-right: 20px;">
    <img src="{{ '/imgs/sig24.jpg' | prepend: base_path }}" alt="SIGGRAPH 2024 Cloth Model" style="max-width: 100%; height: auto;">
  </div>
  
  <!-- 论文信息显示在右边，占3/4宽度 -->
  <div class="col-md-9" style="flex: 3;">
    <h2 class="archive__item-title" itemprop="headline">
      <a href="https://sites.cs.ucsb.edu/~lingqi/publications/paper_sig24cloth.pdf" target="_blank">
        A Realistic Multi-scale Surface-based Cloth Appearance Model
      </a>
    </h2>
    <p>
      <strong>Authors:</strong> Junqiu Zhu, Lukas Bode, Adrian Jarabo, Carlos Aliaga, Christophe Hery, Ling-Qi Yan, Matt Jen-Yuan Chiang
    </p>
    <p>Published in <i>ACM SIGGRAPH 2024 (Conference Track)</i></p>
    <p><a href="https://sites.cs.ucsb.edu/~lingqi/publications/paper_sig24cloth.pdf" target="_blank">[Download Paper]</a></p>
    <p class="archive__item-excerpt" itemprop="description">
      Surface-based cloth appearance models have been rapidly advancing, shifting from detail-less BRDFs to modern per-point shading models with accurate spatially-varying reflection, transmission, and so on. However, the increased complexity has brought about realism-performance trade-offs: from closeup, rendered cloth can be highly inaccurate due to the missing, unaffordable parallax effects; from far away, significant amount of noise will show up since every point can be shaded differently inside a pixel's footprint. In this paper, we aim at eliminating the trade-off with a realistic multi-scale surface-based cloth appearance model. We propose a comprehensive micro-scale model focusing on correct parallax effects, and a practical meso-scale integration scheme, emphasizing efficiency while losslessly preserving accurate highlights and self-shadowing. We further improve its performance using our novel Clustered Control Variates (CCV) and Summed-Area Table (SAT) integration scheme, and its practicality using an efficient Clustered Principal Component Analysis (C-PCA) compression method. As a result, our multi-scale model achieves a 30× acceleration compared to the state-of-the-art, is able to represent a variety of realistic cloth appearance, and can be potentially applied in real-time applications.
    </p>
  </div>
</div>
