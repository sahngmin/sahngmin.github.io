---
permalink: /
title: "Sahngmin Yoo"
excerpt: "RL post-training, multimodal retrieval, and efficient on-device AI"
author_profile: true
classes: [wide-home]
hide_author_bio: true
redirect_from:
  - /about/
  - /about.html
---

<p class="hero-kicker">Applied ML · Multimodal AI · On-device systems</p>

<p class="hero-lede">I build compact multimodal agents at <strong>Samsung Electronics</strong> that connect natural-language intent with visual evidence—from <strong>RL post-training</strong> and <strong>cross-modal text–image retrieval</strong> to grounded visual question answering and efficient on-device AI.</p>

<p class="hero-supporting">I earned my Ph.D., M.S., and B.S. in Electrical Engineering from <strong>KAIST</strong>. Across Samsung, Klleon, and KAIST, I have led work from research prototypes to deployed products spanning retrieval-grounded language models, multimodal person clustering, and generative vision.</p>

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

<div class="research-grid">
  <article class="research-card">
    <span class="research-card__index">01</span>
    <h3>RL Post-Training for Retrieval</h3>
    <p>Improved full-corpus retrieval reciprocal rank by <strong>23.7%</strong> (0.617 to 0.763) over an SFT baseline on 300 held-out queries across 10,275 screens. Trained a 0.8B Query Router with DPO on 1,523 retrieval-grounded preference pairs, and separately applied GRPO to grounded VLM answer generation.</p>
  </article>
  <article class="research-card">
    <span class="research-card__index">02</span>
    <h3>Cross-Modal Gallery Agent</h3>
    <p>Own a 450M-parameter LoRA SLM Query Processor and PEFT-tuned VLM Answer Generator for Samsung's Gallery Agent. Built <strong>200K+</strong> synthetic training and evaluation examples that connect underspecified text requests to OCR, visual, source-app, temporal, and abstention signals.</p>
  </article>
  <article class="research-card">
    <span class="research-card__index">03</span>
    <h3>On-Device Multimodal AI</h3>
    <p>Led and shipped a person-clustering system that fuses face, appearance, language-guided vision, and graph-density signals. Achieved <strong>87.97% average recall</strong> and compressed the vision model <strong>25×</strong>, from 344 MB to 13.4 MB, using CNN distillation and TFLite FP16 quantization.</p>
  </article>
  <article class="research-card">
    <span class="research-card__index">04</span>
    <h3>Retrieval Evaluation</h3>
    <p>Built <strong>SHARD</strong>, a 10,275-screen benchmark for underspecified screenshot retrieval, and <strong>SpreadRAG</strong>, a 31,089-query stress test for retrieval when multi-hop evidence is dispersed.</p>
  </article>
</div>

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

<div class="publication-grid">
  <article class="publication-card">
    <a class="publication-card__visual" href="https://openaccess.thecvf.com/content/WACV2026/papers/Yoo_Beyond_Faces_A_Multimodal_Person_Clustering_for_Unconstrained_Environments_WACV_2026_paper.pdf" aria-label="Open Beyond Faces paper">
      <img src="{{ '/images/publications/beyond-faces.jpg' | relative_url }}" alt="Comparison of person clustering results across photo galleries" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">WACV 2026</span>
      <h4>Beyond Faces: A Multimodal Person Clustering for Unconstrained Environments</h4>
      <p><strong>S. M. Yoo</strong>, S. Lee, S. Jo</p>
      <div class="publication-card__links"><a href="https://openaccess.thecvf.com/content/WACV2026/papers/Yoo_Beyond_Faces_A_Multimodal_Person_Clustering_for_Unconstrained_Environments_WACV_2026_paper.pdf">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:UeHWp8X0CEIC">Google Scholar ↗</a></div>
    </div>
  </article>
  <article class="publication-card">
    <a class="publication-card__visual" href="https://arxiv.org/pdf/2411.00652" aria-label="Open Head Blending preprint">
      <img src="{{ '/images/publications/head-blending.jpg' | relative_url }}" alt="CHANGER pipeline from source and target frames to blended video" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">WACV 2025</span>
      <h4>Towards High-Fidelity Head Blending with Chroma Keying for Industrial Applications</h4>
      <p>H. M. Lew<sup>*</sup>, <strong>S. M. Yoo<sup>*</sup></strong>, H. Kang, G. M. Park</p>
      <div class="publication-card__links"><a href="https://openaccess.thecvf.com/content/WACV2025/html/Lew_Towards_High-Fidelity_Head_Blending_with_Chroma_Keying_for_Industrial_Applications_WACV_2025_paper.html">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:Tyk-4Ss8FVUC">Google Scholar ↗</a></div>
    </div>
  </article>
  <article class="publication-card">
    <a class="publication-card__visual" href="https://openaccess.thecvf.com/content/WACV2023/papers/Yoo_FastSwap_A_Lightweight_One-Stage_Framework_for_Real-Time_Face_Swapping_WACV_2023_paper.pdf" aria-label="Open FastSwap paper">
      <img src="{{ '/images/publications/fastswap.jpg' | relative_url }}" alt="Source, target, and generated face swapping examples" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">WACV 2023</span>
      <h4>FastSwap: A Lightweight One-Stage Framework for Real-Time Face Swapping</h4>
      <p><strong>S. M. Yoo</strong>, T. M. Choi, J. W. Choi, J. H. Kim</p>
      <div class="publication-card__links"><a href="https://openaccess.thecvf.com/content/WACV2023/html/Yoo_FastSwap_A_Lightweight_One-Stage_Framework_for_Real-Time_Face_Swapping_WACV_2023_paper.html">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:zYLM7Y9cAGgC">Google Scholar ↗</a></div>
    </div>
  </article>
  <article class="publication-card">
    <a class="publication-card__visual" href="https://arxiv.org/pdf/2103.05368" aria-label="Open ChangeSim preprint">
      <img src="{{ '/images/publications/changesim.jpg' | relative_url }}" alt="Four photorealistic industrial indoor environments in ChangeSim" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">IROS 2021</span>
      <h4>ChangeSim: Towards End-to-End Online Scene Change Detection in Industrial Indoor Environments</h4>
      <p>J. M. Park, J. H. Jang, <strong>S. M. Yoo</strong>, S. K. Lee, U. H. Kim, J. H. Kim</p>
      <div class="publication-card__links"><a href="https://ieeexplore.ieee.org/document/9636350">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:IjCSPb-OGe4C">Google Scholar ↗</a></div>
    </div>
  </article>
  <article class="publication-card">
    <a class="publication-card__visual" href="https://ieeexplore.ieee.org/document/9145832" aria-label="Open CNN-DM paper">
      <img src="{{ '/images/publications/cnn-dm.jpg' | relative_url }}" alt="CNN-DM logistic, knowledge distillation, and memory loss pathways" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">IEEE TNNLS 2021</span>
      <h4>Convolutional Neural Network with Developmental Memory for Continual Learning</h4>
      <p>G. M. Park, <strong>S. M. Yoo</strong>, J. H. Kim</p>
      <div class="publication-card__links"><a href="https://ieeexplore.ieee.org/document/9145832">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:qjMakFHDy7sC">Google Scholar ↗</a></div>
    </div>
  </article>
  <article class="publication-card">
    <a class="publication-card__visual" href="https://www.ijcai.org/proceedings/2021/0242.pdf" aria-label="Open Invisible Mobile Keyboard paper">
      <img src="{{ '/images/publications/invisible-keyboard.jpg' | relative_url }}" alt="Visualized typing patterns from users of the invisible mobile keyboard" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">IJCAI 2021</span>
      <h4>Type Anywhere You Want: An Introduction to Invisible Mobile Keyboard</h4>
      <p><strong>S. M. Yoo</strong>, U. H. Kim, Y. Hwang, J. H. Kim</p>
      <div class="publication-card__links"><a href="https://www.ijcai.org/proceedings/2021/242">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:9yKSN-GCB0IC">Google Scholar ↗</a></div>
    </div>
  </article>
  <article class="publication-card">
    <a class="publication-card__visual" href="https://arxiv.org/pdf/1907.13285" aria-label="Open I-Keyboard preprint">
      <img src="{{ '/images/publications/i-keyboard.jpg' | relative_url }}" alt="Touchscreen and monitor setup used to collect invisible keyboard typing data" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">IEEE Transactions on Cybernetics</span>
      <h4>I-Keyboard: Fully Imaginary Keyboard on Touch Devices Empowered by Deep Neural Decoder</h4>
      <p>U. H. Kim, <strong>S. M. Yoo</strong>, J. H. Kim</p>
      <div class="publication-card__links"><a href="https://doi.org/10.1109/TCYB.2019.2952391">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:u-x6o8ySG0sC">Google Scholar ↗</a></div>
    </div>
  </article>
  <article class="publication-card">
    <a class="publication-card__visual" href="https://link.springer.com/chapter/10.1007/978-981-13-7780-8_9" aria-label="Open RiTA paper">
      <img src="{{ '/images/publications/rita.jpg' | relative_url }}" alt="Human–robot social interaction framework with sensory, recognition, language, memory, communication, and control modules" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">RiTA 2018</span>
      <h4>Human Robot Social Interaction Framework Based on Emotional Episodic Memory</h4>
      <p>W. H. Lee, <strong>S. M. Yoo</strong>, J. W. Choi, U. H. Kim, J. H. Kim</p>
      <div class="publication-card__links"><a href="https://link.springer.com/chapter/10.1007/978-981-13-7780-8_9">Paper ↗</a><a href="https://dblp.org/rec/conf/rita/LeeYCKK18">DBLP ↗</a></div>
    </div>
  </article>
</div>

### Preprint

<div class="publication-grid">
  <article class="publication-card">
    <a class="publication-card__visual" href="https://arxiv.org/pdf/2010.09236" aria-label="Open Continual UDA preprint">
      <img src="{{ '/images/publications/continual-uda.jpg' | relative_url }}" alt="Semantic segmentation results with and without target memory" loading="lazy" decoding="async">
    </a>
    <div class="publication-card__body">
      <span class="publication-card__meta">arXiv 2020</span>
      <h4>Continual Unsupervised Domain Adaptation for Semantic Segmentation</h4>
      <p>J. Kim<sup>*</sup>, <strong>S. M. Yoo<sup>*</sup></strong>, G. M. Park, J. H. Kim</p>
      <div class="publication-card__links"><a href="https://arxiv.org/abs/2010.09236">Paper ↗</a><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=YDQ6lwcAAAAJ&amp;citation_for_view=YDQ6lwcAAAAJ:2osOgNQ5qMEC">Google Scholar ↗</a></div>
    </div>
  </article>
</div>

<small><sup>*</sup> Equal contribution.</small>

## Education

- **Ph.D. in Electrical Engineering**, KAIST, 2022
- **M.S. in Electrical Engineering**, KAIST, 2018
- **B.S. in Electrical Engineering**, KAIST, 2017

<a id="patents"></a>
## Patents & IP

**12 patent applications and registrations** across efficient input systems, continual adaptation, generative vision, multimodal person clustering, and AI content recommendation. Five recent filings are listed by invention title while public patent-database indexing is pending.

<ol class="patent-list">
  <li><span class="patent-status">FILED · 2026</span><div><strong>Electronic Device for Providing Recommended Content and Operating Method for the Same</strong><code>KR10-2026-0113923 · public search pending</code></div></li>
  <li><span class="patent-status">FILED · 2026</span><div><strong>Method for Performing Face Feature Clustering and Electronic Device for Performing the Same</strong><code>KR10-2026-0034249 · public search pending</code></div></li>
  <li><span class="patent-status">FILED · 2026</span><div><strong>Method and Non-Transitory Computer-Readable Storage Medium for Clustering of Person</strong><code>application number not listed · public search pending</code></div></li>
  <li><span class="patent-status">FILED · 2025</span><div><strong>Electronic Device and Operating Method for the Same</strong><code>KR10-2025-0093322 · public search pending</code></div></li>
  <li><span class="patent-status">FILED · 2025</span><div><strong>Electronic Device Clustering Individuals Detected in Images and Method Thereof</strong><code>KR10-2025-0075023 · public search pending</code></div></li>
  <li><span class="patent-status">GRANTED · 2025</span><div><strong>Unsupervised Domain Adaptation System and Method</strong><code>KR10-2878012</code><a href="https://patents.google.com/patent/KR102878012B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2025</span><div><strong>Head Swapping Framework</strong><code>KR10-2859125</code><a href="https://patents.google.com/patent/KR102859125B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">International Patent Application · 2025</span><div><strong>Electronic Device and Operating Method for the Same</strong><code>PCT/KR2025/012452 · WO2026049388A1</code><code>Priority: KR10-2024-0114486</code><a href="https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2026049388&amp;_cid=P21-MUGLIE-03663-1">WIPO PATENTSCOPE ↗</a> <a href="https://patents.google.com/patent/WO2026049388A1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2024</span><div><strong>Image Processing Apparatus Comprising Face Swapping Framework and Method Thereof</strong><code>KR10-2692338</code><a href="https://patents.google.com/patent/KR102692338B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2022</span><div><strong>Apparatus for Analysing and Providing Soft Keyboard and Method Thereof</strong><code>KR10-2447469</code><a href="https://patents.google.com/patent/KR102447469B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2022</span><div><strong>Method and Apparatus for Face Swapping Using Deep Learning Network</strong><code>KR10-2409988</code><a href="https://patents.google.com/patent/KR102409988B1/en">Google Patents ↗</a></div></li>
  <li><span class="patent-status">GRANTED · 2022</span><div><strong>Decoder Architecture, Operation Method Thereof, and Virtual Keyboard Using Decoder</strong><code>KR10-2355890</code><a href="https://patents.google.com/patent/KR102355890B1/en">Google Patents ↗</a></div></li>
</ol>
