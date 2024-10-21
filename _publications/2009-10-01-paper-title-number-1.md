---
title: "A Realistic Multi-scale Surface-based Cloth Appearance Model"
layout: publication
permalink: /publications/sig24cloth/
classes: wide
author_profile: false
---

# A Realistic Multi-scale Surface-based Cloth Appearance Model
{: .text-center}

**Junqiu Zhu**, Lukas Bode, Adrian Jarabo, Carlos Aliaga, Christophe Hery, Ling-Qi Yan, Matt Jen-Yuan Chiang
{: .text-center}

ACM SIGGRAPH 2024 (Conference Track)
{: .text-center}

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/sig24_teaser.jpg){: .align-center}

{% capture notice-2 %}
#### Abstract

Surface-based cloth appearance models have been rapidly advancing, shifting from detail-less BRDFs to modern per-point shading models with accurate spatially-varying reflection, transmission, and so on. However, the increased complexity has brought about realism-performance trade-offs: from closeup, rendered cloth can be highly inaccurate due to the missing, unaffordable parallax effects; from far away, significant amount of noise will show up since every point can be shaded differently inside a pixel's footprint.

In this paper, we aim at eliminating the trade-off with a realistic multi-scale surface-based cloth appearance model. We propose a comprehensive micro-scale model focusing on correct parallax effects, and a practical meso-scale integration scheme, emphasizing efficiency while losslessly preserving accurate highlights and self-shadowing. We further improve its performance using our novel Clustered Control Variates (CCV) and Summed-Area Table (SAT) integration scheme, and its practicality using an efficient Clustered Principal Component Analysis (C-PCA) compression method. As a result, our multi-scale model achieves a 30× acceleration compared to the state-of-the-art, is able to represent a variety of realistic cloth appearance, and can be potentially applied in real-time applications.
{% endcapture %}

<div class="notice">
  {{ notice-2 | markdownify }}
</div>

## Downloads
[Paper (PDF)](/assets/files/sig24cloth.pdf){: .btn .btn--primary}
[Slides (PPT)](/assets/files/sig24cloth_slides.pptx){: .btn .btn--primary}
[Supplementary Video](https://drive.google.com/file/d/some-video-id/view){: .btn .btn--primary}
[Shader Code](/assets/files/sig24cloth_code.zip){: .btn .btn--primary}

## Videos
{% include video id="some-video-id" provider="google-drive" %}

## Cite

```html
@inproceedings{zhu2024realistic,
  title={A Realistic Multi-scale Surface-based Cloth Appearance Model},
  author={Zhu, Junqiu and Bode, Lukas and Jarabo, Adrian and Aliaga, Carlos and Hery, Christophe and Yan, Ling-Qi and Chiang, Matt Jen-Yuan},
  booktitle={ACM SIGGRAPH Conference Proceedings},
  year={2024}
}
