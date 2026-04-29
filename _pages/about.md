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

<div class="profile-hero">
  <p>
    Hi, I am <strong>Yi Su (苏仪)</strong>. I am a <strong>Senior Researcher</strong> at
    <a href="https://www.tencent.com/en-us/">Tencent</a>, working at the
    <strong>Hunyuan AI Infra</strong> Department in Shanghai through
    <strong>Tencent Project UP (青云计划)</strong>.
  </p>
  <p>
    I am also completing my M.S. at Soochow University, supervised by Assoc. Prof.
    <a href="https://lijuntaopku.github.io">Juntao Li</a> and Prof.
    <a href="https://zhangminsuda.github.io/cn_homepage/News/">Min Zhang</a>.
    My work focuses on efficient training and deployment of Large Language Models, especially through
    quantization, KV-cache optimization, efficient attention, and other acceleration techniques.
  </p>
  <div class="profile-tags">
    <span>Efficient LLMs</span>
    <span>Quantization</span>
    <span>KV Cache Optimization</span>
    <span>Efficient Attention</span>
  </div>
</div>

# 🔥 News
- *2026.04*: &nbsp;Release a light-weight 2-bit translation model: [Hy-MT1.5-1.8B-2bit](https://huggingface.co/AngelSlim/Hy-MT1.5-1.8B-2bit).
- *2026.04*: &nbsp;MY previous work in KuaiShou, [Kwai Summary Attention Technical Report](https://arxiv.org/abs/2604.24432) is released.
- *2026.04*: &nbsp;One paper is accepted by ACL2026: [General-RL](https://arxiv.org/abs/2503.23829).
- *2026.03*: &nbsp;I join Tencent Hunyuan AI Infra Department as a Senior Researcher through Tencent Project UP (青云计划).
- *2026.03*: &nbsp;Release new works on efficiency: [LongFlow](https://arxiv.org/abs/2603.11504), [DapQ](https://arxiv.org/abs/2603.11564), and [Quantized Inference for OneRec-V2](https://arxiv.org/abs/2603.11486).
- *2025.10*: &nbsp;Release [OneRec-Think](https://arxiv.org/abs/2510.11639), bringing explicit reasoning into generative recommendation.
- *2025.08*: &nbsp;Our work at KuaiShou, [OneRec-V2 Technical Report](https://arxiv.org/abs/2508.20900), is released.
- *2025.06*: &nbsp;I join Kuaishou OneRec Team as a Research Intern through KuaiShou Kwai-Star Project (快Star-X).
- *2025.05*: &nbsp;Two paper are accepted by ACL 2025: [OTT](https://arxiv.org/abs/2505.10938) and [OPT-Tree](https://arxiv.org/abs/2406.17276).

# 📖 Education
<div class="timeline-card">
  <div class="timeline-logo">
    <img src="/images/logos/soochow.png" alt="Soochow University logo">
  </div>
  <div class="timeline-body">
    <div class="timeline-title">Soochow University</div>
    <div class="timeline-meta">M.S. in Artificial Intelligence · Institute of Computer Science and Technology · Suzhou</div>
    <div class="timeline-date">2023.09 - 2026.07</div>
    <p>Supervised by Assoc. Prof. Juntao Li and Prof. Min Zhang. Researching Efficient LLMs.</p>
  </div>
</div>

<div class="timeline-card">
  <div class="timeline-logo">
    <img src="/images/logos/soochow.png" alt="Soochow University logo">
  </div>
  <div class="timeline-body">
    <div class="timeline-title">Soochow University</div>
    <div class="timeline-meta">B.Eng. in Computer Science · Institute of Computer Science and Technology · Suzhou</div>
    <div class="timeline-date">2019.09 - 2023.06</div>
  </div>
</div>

# 💼 Work Experiences
<div class="experience-grid">
  <div class="experience-card highlight">
    <div class="company-logo">
      <img src="/images/logos/hunyuan.svg" alt="Tencent Hunyuan logo">
    </div>
    <div class="experience-content">
      <div class="experience-header">
        <div>
          <div class="experience-company">Tencent · Hunyuan AI Infra Department</div>
          <div class="experience-role">Senior Researcher · Tencent Project UP (青云计划)</div>
        </div>
        <div class="experience-date">2026.03 - Present · Shanghai</div>
      </div>
      <ul>
        <li>Build efficient LLM serving systems around quantization, model compression, and KV-cache optimization for production-scale Hunyuan models.</li>
        <li>Explore efficient attention architectures to reduce latency and memory pressure in long-context serving.</li>
        <li>Develop and maintain AngelSlim, an open-source model compression toolkit for practical LLM deployment.</li>
      </ul>
    </div>
  </div>

  <div class="experience-card">
    <div class="company-logo">
      <img src="/images/logos/kuaishou.svg" alt="Kuaishou logo">
    </div>
    <div class="experience-content">
      <div class="experience-header">
        <div>
          <div class="experience-company">Kuaishou · OneRec Team</div>
          <div class="experience-role">Research Intern · Kuai Star (快-Star)</div>
        </div>
        <div class="experience-date">2025.06 - 2026.02 · Beijing</div>
      </div>
      <ul>
        <li>Low-precision training and inference for OneRec-V2, adapting LLM compression techniques to industrial generative recommendation.</li>
        <li>Design efficient attention mechanisms, including <a href="https://arxiv.org/abs/2604.24432">Kwai Summary Attention</a>, for scalable recommendation foundation models.</li>
      </ul>
    </div>
  </div>

  <div class="experience-card">
    <div class="company-logo">
      <img src="/images/logos/tencent.svg" alt="Tencent logo">
    </div>
    <div class="experience-content">
      <div class="experience-header">
        <div>
          <div class="experience-company">Tencent AI Lab</div>
          <div class="experience-role">Research Intern</div>
        </div>
        <div class="experience-date">2024.11 - 2025.06 · Shenzhen</div>
      </div>
      <ul>
        <li>Improve LLM reasoning capabilities through algorithmic pipelines for general-domain inference and alignment.</li>
        <li>Design reward signals for applying reinforcement learning beyond verifiable tasks.</li>
      </ul>
    </div>
  </div>

  <div class="experience-card">
    <div class="company-logo">
      <img src="/images/logos/huawei.svg" alt="Huawei logo">
    </div>
    <div class="experience-content">
      <div class="experience-header">
        <div>
          <div class="experience-company">Huawei Cloud · AI System Innovation Lab</div>
          <div class="experience-role">Research Intern</div>
        </div>
        <div class="experience-date">2024.08 - 2024.11 · Hangzhou</div>
      </div>
      <ul>
        <li>Research KV-cache quantization and compression algorithms for efficient LLM inference.</li>
        <li>Brought KV-cache quantization techniques into Ascend-vLLM for deployment on Ascend NPUs.</li>
      </ul>
    </div>
  </div>
</div>

# 📝 Selected Publications
Full list is available on my [Google Scholar](https://scholar.google.com/citations?user=YAvMAQwAAAAJ&hl=en&oi=ao).

<div class="publication-list">
  <div class="publication-item">
    <span class="pub-badge">arXiv 2026</span>
    <a href="https://arxiv.org/abs/2604.24432">Kwai Summary Attention Technical Report</a>
    <p>KuaiShou OneRec Team</p>
  </div>
<div class="publication-list">
  <div class="publication-item">
    <span class="pub-badge">arXiv 2026</span>
    <a href="https://arxiv.org/abs/2603.11486">Quantized Inference for OneRec-V2</a>
    <p><strong>Yi Su</strong>, Xinchen Luo, Hongtao Cheng, Ziteng Shu,..., Ruiming Tang</p>
  </div>
  <div class="publication-item">
    <span class="pub-badge">arXiv 2026</span>
    <a href="https://arxiv.org/abs/2603.11504">LongFlow: Efficient KV Cache Compression for Reasoning Models</a>
    <p><strong>Yi Su</strong>, Zhenxu Tian, Dan Qiao, Yuechi Zhou, Juntao Li, Min Zhang</p>
  </div>
  <div class="publication-item">
    <span class="pub-badge">arXiv 2025</span>
    <a href="https://arxiv.org/abs/2508.20900">OneRec-V2 Technical Report</a>
    <p>KuaiShou OneRec Team</p>
  </div>
  <div class="publication-item">
    <span class="pub-badge">ACL 2026</span>
    <a href="https://arxiv.org/abs/2503.23829">Crossing the Reward Bridge: Expanding RL with Verifiable Rewards Across Diverse Domains</a>
    <p><strong>Yi Su</strong>, Dian Yu, Linfeng Song, Juntao Li, Haitao Mi, Zhaopeng Tu, Min Zhang, Dong Yu</p>
  </div>
  <div class="publication-item">
    <span class="pub-badge">ACL 2025</span>
    <a href="https://arxiv.org/abs/2505.10938">Accurate KV Cache Quantization with Outlier Tokens Tracing</a>
    <p><strong>Yi Su</strong>, Yuechi Zhou, Quantong Qiu, Juntao Li, Qingrong Xia, Ping Li, Xinyu Duan, Zhefeng Wang, Min Zhang</p>
  </div>
  <div class="publication-item">
    <span class="pub-badge">ACL 2025</span>
    <a href="https://arxiv.org/abs/2406.17276">OPT-Tree: Speculative Decoding with Adaptive Draft Tree Structure</a>
    <p>Jikai Wang*, <strong>Yi Su*</strong>, Juntao Li, Qingrong Xia, Zi Ye, Xinyu Duan, Zhefeng Wang, Min Zhang</p>
  </div>
  <div class="publication-item">
    <span class="pub-badge">ACL 2024</span>
    <a href="https://aclanthology.org/2024.findings-acl.846.pdf">Demonstration Augmentation for Zero-shot In-context Learning</a>
    <p><strong>Yi Su</strong>, Yunpeng Tai, Yixin Ji, Juntao Li, Bowen Yan, Min Zhang</p>
  </div>
  <div class="publication-item">
    <span class="pub-badge">EMNLP 2023</span>
    <a href="https://aclanthology.org/2023.emnlp-main.803.pdf">Beware of Model Collapse! Fast and Stable Test-time Adaptation for Robust Question Answering</a>
    <p><strong>Yi Su</strong>, Yixin Ji, Juntao Li, Hai Ye, Min Zhang</p>
  </div>
</div>


<h1>🎖 Honors and Awards</h1>
<ul>
  <li><em>2025</em>: &nbsp;Soochow University National Scholarship for Graduate Students</li>
  <li><em>2025</em>: &nbsp;Soochow University Graduate Outstanding Scholarship</li>
  <li><em>2024</em>: &nbsp;Soochow University Diligence and Encouragement Scholarship</li>
  <li><em>2023</em>: &nbsp;Soochow University Excellent Graduation Thesis for Undergraduate Students</li>
  <li><em>2023</em>: &nbsp;Soochow University Outstanding Graduate Student</li>
  <li><em>2022</em>: &nbsp;Champion of Huawei Shengsi Model Development Challenge Competition</li>
</ul>