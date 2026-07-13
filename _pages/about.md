---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

**I am currently a Ph.D. student at LIESMARS, Wuhan University, under the supervision of Prof. Mi Wang and Prof. Jing Xiao. I obtained my Bachelor's degree from Sun Yat-sen University in 2024.**

**My current research focuses on multimodal learning and satellite 3D reconstruction.**

# 📝 Selected Publications 

## Multimodal Learning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Modality-agnostic Semantic Segmentation</div><img src='images/aaai_2026_charm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CHARM: Collaborative Harmonization Across Arbitrary Modalities for Modality-Agnostic Semantic Segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/38033)

**Lekang Wen**, Jing Xiao\*, Liang Liao, Jiajun Chen, Mi Wang (\* corresponding author) 

The 40th Annual AAAI Conference on Artificial Intelligence (**AAAI**), 2026.

**TLDR:** Modality-agnostic semantic segmentation aims to achieve robust scene understanding across incomplete modality configurations. However, explicit feature alignment methods cause modal homogenization that suppresses modality-specific characteristics. CHARM enables implicit content alignment and individual enhancement through mutual perception units and dual-path optimization.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Incomplete Multimodal Semantic Segmentation</div><img src='images/tgrs_2026_sgma.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SGMA: Semantic-Guided Modality-Aware Segmentation for Remote Sensing with Incomplete Multimodal Data](https://ieeexplore.ieee.org/abstract/document/11517493)

**Lekang Wen**, Liang Liao, Jing Xiao\*, Mi Wang (\* corresponding author) 

IEEE Transaction on Geoscience and Remote Sensing (**TGRS**), 2026.

**TLDR:** Incomplete multimodal semantic segmentation for remote sensing integrates diverse sensors but frequently encounters missing input data. Conventional methods struggle with severe modality imbalance, massive intraclass variation, and cross-modal heterogeneity. SGMA incorporates semantic-guided fusion via classwise prototypes and modality-aware sampling to prioritize fragile modalities dynamically.

</div>
</div>

## 3D Reconstruction

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Semantic 3D Reconstruction</div><img src='images/isprs_2026_uniortho.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[UniOrtho: From View-centric to Unified Orthographic Framework for Satellite Semantic 3D Reconstruction](https://www.sciencedirect.com/science/article/pii/S092427162600345X)

**Lekang Wen**, Yingdong Pi\*, Qiyan Luo, Jie Yang, Mi Wang (\* corresponding author) 

ISPRS Journal of Photogrammetry and Remote Sensing (**ISPRS**), 2026.

**TLDR:** Satellite semantic 3D reconstruction unifies surface geometry and land classification from multi-view imagery. However, view-centric methods cause severe error accumulation and exhibit weak height-semantic coupling. UniOrtho introduces direct orthographic warping guided by explicit spatial and vertical consistency constraints.

</div>
</div>

# 📖 Educations
- *2024.06 - present*, State Key Laboratory of Information Engineering in Surveying,
  Mapping and Remote Sensing (LIESMARS), Wuhan University. 
- *2020.09 - 2024.06*, School of Geospatial Engineering and Science, Sun Yat-sen University. 
