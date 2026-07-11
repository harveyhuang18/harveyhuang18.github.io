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

<!-- <span class=’anchor’ id=’about-me’></span> -->

<div class="section-card" style="margin-top: 24px;" markdown="1">
<h2>About Me</h2>
<div class="about-body">
I am currently a Ph.D. student (Sep. 2024 - Jun. 2028, expected) in the School of Information Science and Technology, Fudan University, supervised by Prof. <a href="https://eetchen.github.io/">Tao Chen</a>. I am also fortunate to work closely with Dr. Peng Ye from Shanghai AI Lab. Before this, I obtained my Master's and Bachelor's degrees from the School of Electronic Science and Engineering, Southeast University, supervised by Prof. Yuning Zhang. I’m currently working in the fields of vision-language models, on-policy distillation, multi-modal reasoning, and model merging.
</div>

<div style="margin-top: 18px; background: #f4f7ff; border: 1px solid #d8e3fb; border-radius: 12px; padding: 14px 18px;">
  <div style="font-size: 0.82em; font-weight: 700; color: #1a73e8; text-transform: uppercase; letter-spacing: 0.6px; margin-bottom: 10px;">Research Interests</div>
  <div class="research-tags" style="margin-top: 0;">
    <span class="research-tag">🔗 Model Merging</span>
    <span class="research-tag">👁️ Multimodal LLM</span>
    <span class="research-tag">📏 On-Policy Distillation</span>
    <span class="research-tag">🌐 Vision-Language Model</span>
  </div>
</div>

</div>

<div class="section-card" markdown="1">

# 🔥 News

<ul style="margin:0; padding-left:1.2em;">
  <li><p style='text-align:justify; margin:4px 0'><i>2026.5</i>: &nbsp;🎉🎉 FRISM is accepted by <span style="color:#c0392b; font-weight:600;">ICML 2026</span>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2026.1</i>: &nbsp;🎉🎉 Sci-Verifier is accepted by <span style="color:#c0392b; font-weight:600;">ICLR 2026</span>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2025.9</i>: &nbsp;🎉🎉 UltraDelta is accepted by <span style="color:#c0392b; font-weight:600;">NeurIPS 2025</span>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2025.2</i>: &nbsp;🎉🎉 DeRS is accepted by <span style="color:#c0392b; font-weight:600;">CVPR 2025</span>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2025.2</i>: &nbsp;🎉🎉 MoW-Merging is accepted by <span style="color:#c0392b; font-weight:600;">IEEE TCSVT</span>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2024.9</i>: &nbsp;🎉🎉 EMR-Merging is accepted by <span style="color:#c0392b; font-weight:600;">NeurIPS 2024 Spotlight</span>.</p></li>
</ul>






# 📝 Publications

<style>
.publication-list {
  margin: 8px 0 0 0;
  padding: 0;
  list-style: none;
}

.publication-item {
  border-bottom: 1px solid #efefef;
  padding: 18px 0;
}

.publication-item:first-child {
  padding-top: 4px;
}

.pub-title {
  font-size: 1.04em;
  font-weight: 700;
  line-height: 1.35;
}

.pub-title a {
  color: #00369f;
}

.pub-authors {
  margin-top: 6px;
  color: #333;
  line-height: 1.45;
}

.pub-venue {
  margin-top: 6px;
  color: #666;
  line-height: 1.4;
}

.pub-badge {
  display: inline-block;
  margin-right: 8px;
  padding: 2px 8px;
  border-radius: 4px;
  background: #eef4ff;
  color: #00369f;
  font-size: 0.82em;
  font-weight: 700;
  white-space: nowrap;
}
</style>

<ol class="publication-list">
  <li class="publication-item">
    <div class="pub-title"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=EKto99gAAAAJ&citation_for_view=EKto99gAAAAJ:zYLM7Y9cAGgC">EMR-Merging: Tuning-free high-performance model merging</a></div>
    <div class="pub-authors"><strong><u>C Huang</u></strong>, P Ye, T Chen, T He, X Yue, W Ouyang</div>
    <div class="pub-venue"><span class="pub-badge">NeurIPS 2024 Spotlight</span> Advances in Neural Information Processing Systems, 2024</div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=EKto99gAAAAJ&citation_for_view=EKto99gAAAAJ:LkGwnXOMwfcC">FRISM: Fine-Grained Reasoning Injection via Subspace-Level Model Merging for Vision-Language Models</a></div>
    <div class="pub-authors"><strong><u>C Huang</u></strong>, P Ye, X Tan, J Mu, S Zheng, L Shen, T Chen</div>
    <div class="pub-venue"><span class="pub-badge">ICML 2026</span> arXiv preprint arXiv:2601.21187</div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=EKto99gAAAAJ&citation_for_view=EKto99gAAAAJ:Tyk-4Ss8FVUC">Dynamic model merging with mixture of weights</a></div>
    <div class="pub-authors">P Ye, <strong><u>C Huang</u></strong>, M Shen, T Chen, Y Huang, W Ouyang</div>
    <div class="pub-venue"><span class="pub-badge">TCSVT 2025</span> IEEE Transactions on Circuits and Systems for Video Technology, 2025</div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=EKto99gAAAAJ&citation_for_view=EKto99gAAAAJ:Y0pCki6q_DkC">DeRS: Towards extremely efficient upcycled mixture-of-experts models</a></div>
    <div class="pub-authors">Y Huang, P Ye, <strong><u>C Huang</u></strong>, J Cao, L Zhang, B Li, G Yu, T Chen</div>
    <div class="pub-venue"><span class="pub-badge">CVPR 2025</span> Proceedings of the Computer Vision and Pattern Recognition, 2025</div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=EKto99gAAAAJ&citation_for_view=EKto99gAAAAJ:Se3iqnhoufwC">Sci-verifier: Scientific verifier with thinking</a></div>
    <div class="pub-authors">S Zheng, <strong><u>C Huang</u></strong>, F Yu, J Yao, J Ye, T Chen, Y Luo, N Ding, L Bai, G Cui, ...</div>
    <div class="pub-venue"><span class="pub-badge">ICLR 2026</span> arXiv preprint arXiv:2509.24285</div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=EKto99gAAAAJ&citation_for_view=EKto99gAAAAJ:roLk4NBRz8UC">Breaking the compression ceiling: Data-free pipeline for ultra-efficient delta compression</a></div>
    <div class="pub-authors">X Wang, P Ye, <strong><u>C Huang</u></strong>, S Zheng, B Zhang, L Bai, W Ouyang, T Chen</div>
    <div class="pub-venue"><span class="pub-badge">NeurIPS 2025</span> Advances in Neural Information Processing Systems 38, 23167-23195</div>
  </li>
</ol>

</div><!-- end section-card: publications -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<style>
.timeline {
  position: relative;
  padding: 0;
  list-style: none;
  margin: 16px 0 0 0;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 7px;
  top: 6px;
  bottom: 6px;
  width: 2px;
  background: linear-gradient(to bottom, #1a73e8 0%, #c5d8fb 100%);
  border-radius: 2px;
}

.timeline li {
  position: relative;
  padding: 0 0 22px 32px;
  margin: 0;
  font-size: 1em;
}

.timeline li:last-child {
  padding-bottom: 4px;
}

.timeline li::before {
  content: '';
  position: absolute;
  left: 0;
  top: 6px;
  width: 16px;
  height: 16px;
  border-radius: 50%;
  background: #fff;
  border: 2.5px solid #1a73e8;
  box-shadow: 0 0 0 3px rgba(26,115,232,0.12);
  z-index: 1;
}

.timeline li.tl-current::before {
  background: #1a73e8;
  box-shadow: 0 0 0 4px rgba(26,115,232,0.18);
}

.tl-period {
  display: inline-block;
  font-size: 0.78em;
  font-weight: 600;
  color: #1a73e8;
  background: rgba(26,115,232,0.08);
  border-radius: 4px;
  padding: 1px 8px;
  margin-bottom: 3px;
  letter-spacing: 0.2px;
}

.tl-period.tl-now {
  background: rgba(26,115,232,0.15);
}

.tl-body {
  color: #333;
  margin-top: 2px;
  line-height: 1.5;
}

.tl-body a {
  color: #1a73e8;
}

.tl-sub {
  color: #888;
  font-size: 0.88em;
  margin-top: 1px;
}
</style>

<div style='margin-top: 30pt'></div>

<div class="section-card" markdown="1">

# 📖 Educations

<ul class="timeline">
  <li class="tl-current">
    <span class="tl-period tl-now">2024.09 — Present</span>
    <div class="tl-body">Ph.D. Candidate · School of Information Science and Technology</div>
    <div class="tl-sub"><a href="https://www.fudan.edu.cn/">Fudan University</a></div>
    <div class="tl-sub">Supervised by: Prof.<a href="https://scholar.google.com/citations?user=w3OoFL0AAAAJ&hl=zh-CN">Tao Chen</a></div>
  </li>
  <li>
    <span class="tl-period">2021.09 — 2024.06</span>
    <div class="tl-body">Master of Electronic Science and Technology</div>
    <div class="tl-sub"><a href="https://www.seu.edu.cn/">Southeast University</a></div>
    <div class="tl-sub">Supervised by: Prof.<a href="https://scholar.google.com/citations?user=0jajoYwAAAAJ&hl=zh-CN">Yuning Zhang</a></div>
  </li>
  <li>
    <span class="tl-period">2017.09 — 2021.06</span>
    <div class="tl-body">Bachelor of Electronic Science and Technology</div>
    <div class="tl-sub"><a href="https://www.seu.edu.cn/">Southeast University</a></div>
  </li>
</ul>


</div>

<div class="section-card" markdown="1">

# 💬 Invited Talks

<ul class="timeline">
  <li>
    <span class="tl-period">2025.04</span>
    <div class="tl-body"><strong>EMR-Merging: Tuning-Free High-Performance Model Merging</strong></div>
    <div class="tl-sub"><a href="https://www.bilibili.com/video/BV1iko7Y4Eao/?spm_id_from=333.1387.search.video_card.click">▶ Watch Video</a></div>
  </li>
</ul>

<div class="section-card" markdown="1">

# Honors and Awards

<div style="margin-top: 0.8rem; margin-bottom: 2.2rem;">
  <div style="padding: 1rem 1.2rem; border-left: 4px solid #4f8cff; background: #f8fafc; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.04);">
    <div style="font-weight: 600; font-size: 1.02rem; margin-bottom: 0.25rem;">
      National Scholarship
    </div>
    <div style="color: #666; font-size: 0.95rem;">
      2023
    </div>
  </div>
</div>

# Academic Services

<div style="margin-top: 0.8rem; margin-bottom: 2.2rem;">
  <p style="margin-bottom: 0.7rem;">
    Serving as a reviewer for:
  </p>

  <div style="display: flex; flex-wrap: wrap; gap: 0.55rem 0.65rem;">
    <span style="padding: 0.35rem 0.75rem; background: #f3f6fb; border: 1px solid #e3e8f0; border-radius: 999px;">NeurIPS</span>
    <span style="padding: 0.35rem 0.75rem; background: #f3f6fb; border: 1px solid #e3e8f0; border-radius: 999px;">ECCV</span>
    <span style="padding: 0.35rem 0.75rem; background: #f3f6fb; border: 1px solid #e3e8f0; border-radius: 999px;">CVPR</span>
    <span style="padding: 0.35rem 0.75rem; background: #f3f6fb; border: 1px solid #e3e8f0; border-radius: 999px;">ICML</span>
    <span style="padding: 0.35rem 0.75rem; background: #f3f6fb; border: 1px solid #e3e8f0; border-radius: 999px;">IEEE T-CSVT</span>
  </div>
</div>
