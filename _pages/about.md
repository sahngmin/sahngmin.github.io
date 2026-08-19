---
permalink: /
title: "Applied ML Engineer for Multimodal AI"
excerpt: "RL post-training, multimodal retrieval, and efficient on-device AI"
author_profile: true
hide_author_identity: true
redirect_from:
  - /about/
  - /about.html
---

I build compact multimodal agents at **Samsung Electronics** that connect natural-language intent with visual evidence—from **RL post-training** and **cross-modal text–image retrieval** to grounded visual question answering and efficient on-device AI.

I earned my Ph.D., M.S., and B.S. in Electrical Engineering from **KAIST**. Across Samsung, Klleon, and KAIST, I have led work from research prototypes to deployed products spanning retrieval-grounded language models, multimodal person clustering, and generative vision.

<div class="impact-strip" aria-label="Career and research highlights">
  <div><strong>9 years</strong><span>research & industry</span></div>
  <div><strong>146+</strong><span>Google Scholar citations</span></div>
  <div><strong>8</strong><span>peer-reviewed papers</span></div>
  <div><strong>12</strong><span>patent filings & grants</span></div>
</div>

<nav class="hero-actions" aria-label="Primary profile links">
  <a class="hero-action hero-action--primary" href="/images/Sahngmin_Yoo_CV_v2.pdf">View CV</a>
  <a class="hero-action" href="https://scholar.google.com/citations?user=YDQ6lwcAAAAJ&hl=en">Google Scholar</a>
</nav>

<a id="research"></a>
## Research & Product Highlights

- **RL Post-Training for Retrieval.** Improved full-corpus retrieval reciprocal rank by **23.7%** (0.617 to 0.763) over an SFT baseline on 300 held-out queries across 10,275 screens. Trained a 0.8B Query Router with DPO on 1,523 retrieval-grounded preference pairs, and separately applied GRPO to grounded VLM answer generation.

- **Cross-Modal Gallery Agent.** Own a 450M-parameter LoRA SLM Query Processor and PEFT-tuned VLM Answer Generator for Samsung's Gallery Agent. Built 200K+ synthetic training and evaluation examples that connect underspecified text requests to OCR, visual, source-app, temporal, and abstention signals.

- **On-Device Multimodal AI.** Led and shipped a person-clustering system that fuses face, appearance, language-guided vision, and graph-density signals. Achieved **87.97% average recall** and compressed the vision model **25×**, from 344 MB to 13.4 MB, using CNN distillation and TFLite FP16 quantization.

- **Retrieval Evaluation.** Built **SHARD**, a 10,275-screen benchmark for underspecified screenshot retrieval, and **SpreadRAG**, a 31,089-query stress test for retrieval when multi-hop evidence is dispersed.

<a id="experience"></a>
## Experience

<div class="career-grid">
  <article class="career-card">
    <span class="career-card__date">NOV. 2023–PRESENT · SEOUL</span>
    <h3>Samsung Electronics</h3>
    <p class="career-card__role">AI/ML Researcher</p>
    <p>Own compact SLM/VLM components for Gallery Agent across RL post-training, cross-modal retrieval, grounded QA, synthetic data, and on-device deployment.</p>
  </article>
  <article class="career-card">
    <span class="career-card__date">AUG. 2022–OCT. 2023 · SEOUL</span>
    <h3>Klleon</h3>
    <p class="career-card__role">AI/ML Team Lead</p>
    <p>Led real-time generative vision, including a 123-FPS face-swapping system and production-oriented head blending at 0.950 SSIM and 60.5 FPS.</p>
  </article>
  <article class="career-card">
    <span class="career-card__date">AUG. 2017–JUL. 2022 · DAEJEON</span>
    <h3>KAIST RIT Lab</h3>
    <p class="career-card__role">MS/PhD Researcher</p>
    <p>Researched continual learning, domain adaptation, robust multimodal perception, synthetic simulation, and noise-resilient sequence modeling.</p>
  </article>
</div>

<a id="publications"></a>
## Publications

### Peer-Reviewed

- **Beyond Faces: A Multimodal Person Clustering for Unconstrained Environments**<br>
  **S. M. Yoo**, S. Lee, S. Jo · **WACV 2026** · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:UeHWp8X0CEIC)

- **Towards High-Fidelity Head Blending with Chroma Keying for Industrial Applications**<br>
  H. M. Lew<sup>*</sup>, **S. M. Yoo<sup>*</sup>**, H. Kang, G. M. Park · **WACV 2025** · [[paper]](https://arxiv.org/abs/2411.00652) · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:Tyk-4Ss8FVUC)

- **FastSwap: A Lightweight One-Stage Framework for Real-Time Face Swapping**<br>
  **S. M. Yoo**, T. M. Choi, J. W. Choi, J. H. Kim · **WACV 2023** · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:zYLM7Y9cAGgC)

- **ChangeSim: Towards End-to-End Online Scene Change Detection in Industrial Indoor Environments**<br>
  J. M. Park, J. H. Jang, **S. M. Yoo**, S. K. Lee, U. H. Kim, J. H. Kim · **IROS 2021** · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:IjCSPb-OGe4C)

- **Convolutional Neural Network with Developmental Memory for Continual Learning**<br>
  G. M. Park, **S. M. Yoo**, J. H. Kim · **IEEE TNNLS 2021** · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:qjMakFHDy7sC)

- **Type Anywhere You Want: An Introduction to Invisible Mobile Keyboard**<br>
  **S. M. Yoo**, U. H. Kim, Y. Hwang, J. H. Kim · **IJCAI 2021** · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:9yKSN-GCB0IC)

- **I-Keyboard: Fully Imaginary Keyboard on Touch Devices Empowered by Deep Neural Decoder**<br>
  U. H. Kim, **S. M. Yoo**, J. H. Kim · **IEEE Transactions on Cybernetics** · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:u-x6o8ySG0sC)

- **Human Robot Social Interaction Framework Based on Emotional Episodic Memory**<br>
  W. H. Lee, **S. M. Yoo**, J. W. Choi, U. H. Kim, J. H. Kim · **RiTA 2018** · [[DBLP]](https://dblp.org/rec/conf/rita/LeeYCKK18)

### Preprint

- **Continual Unsupervised Domain Adaptation for Semantic Segmentation**<br>
  J. Kim<sup>*</sup>, **S. M. Yoo<sup>*</sup>**, G. M. Park, J. H. Kim · **arXiv 2020** · [[Google Scholar]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=YDQ6lwcAAAAJ&citation_for_view=YDQ6lwcAAAAJ:2osOgNQ5qMEC)

<small><sup>*</sup> Equal contribution.</small>

## Education

- **Ph.D. in Electrical Engineering**, KAIST, 2022
- **M.S. in Electrical Engineering**, KAIST, 2018
- **B.S. in Electrical Engineering**, KAIST, 2017

<a id="patents"></a>
## Patents & IP

**12 patent applications and registrations** across efficient input systems, continual adaptation, generative vision, multimodal person clustering, and AI content recommendation. Four recent filings are listed by invention title while public patent-database indexing is pending.

<ol class="patent-list">
  <li><span class="patent-status">FILED · 2026</span><div><strong>Electronic Device for Providing Recommended Content and Operating Method for the Same</strong><code>KR10-2026-0113923 · public search pending</code></div></li>
  <li><span class="patent-status">FILED · 2026</span><div><strong>Method for Performing Face Feature Clustering and Electronic Device for Performing the Same</strong><code>KR10-2026-0034249 · public search pending</code></div></li>
  <li><span class="patent-status">FILED · 2025</span><div><strong>Electronic Device and Operating Method for the Same</strong><code>KR10-2025-0093322 · public search pending</code></div></li>
  <li><span class="patent-status">FILED · 2025</span><div><strong>Electronic Device Clustering Individuals Detected in Images and Method Thereof</strong><code>KR10-2025-0075023 · public search pending</code></div></li>
  <li><span class="patent-status">GRANTED · 2025</span><div><strong>Unsupervised Domain Adaptation System and Method</strong><code>KR10-2878012</code><a href="https://patents.google.com/patent/KR102878012B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2025</span><div><strong>Head Swapping Framework</strong><code>KR10-2859125</code><a href="https://patents.google.com/patent/KR102859125B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">FILED · 2024</span><div><strong>Electronic Device and Operating Method for the Same</strong><code>KR10-2024-0114486</code><a href="https://patents.google.com/patent/WO2026075336A1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2024</span><div><strong>Image Processing Apparatus Comprising Face Swapping Framework and Method Thereof</strong><code>KR10-2692338</code><a href="https://patents.google.com/patent/KR102692338B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2022</span><div><strong>Apparatus for Analysing and Providing Soft Keyboard and Method Thereof</strong><code>KR10-2447469</code><a href="https://patents.google.com/patent/KR102447469B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2022</span><div><strong>Method and Apparatus for Face Swapping Using Deep Learning Network</strong><code>KR10-2409988</code><a href="https://patents.google.com/patent/KR102409988B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2022</span><div><strong>Decoder Architecture, Operation Method Thereof, and Virtual Keyboard Using Decoder</strong><code>KR10-2355890</code><a href="https://patents.google.com/patent/KR102355890B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED</span><div><strong>Method and Non-Transitory Computer-Readable Storage Medium for Clustering of Person</strong><code>registration number not listed</code></div></li>
</ol>
