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

Hello! 👋 I am an incoming MPhil student at **CUHK-SZ**, fortunately advised by [Prof. Xiaoying Tang](https://scholar.google.com/citations?user=S1a25sEAAAAJ&hl=en&oi=ao). Prior to this, I received my B.Eng. in Electronic and Information Engineering from *UESTC*. My research broadly focuses on **LVLMs**. Specifically, I am interested in **Trustworthy AI, Safety Alignment**, and **LVLM SFT/RL**. Earlier, I explored Industrial LVLMs (wafer defect diagnosis) and cross-domain fault diagnosis.

⭐ **I am currently in a gap period and actively seeking research internship opportunities (industry/academia) in LVLMs or AI safety/alignment.** I am **available immediately** for onsite roles! Please feel free to contact me via email: `ChenxiLi_lcx@outlook.com` or WeChat: `chenxi_yef`. I warmly welcome potential collaborations and look forward to connecting!


# 🔥 News
* **2026.03:** 📝 Submitted one **first author** paper on LVLM hallucination mitigation to **ECCV 2026** (currently under review).
* **2026.02:** 🎉 One **first author** paper on black-box jailbreaking for LVLMs was accepted to **CVPR 2026**! This work was completed during my second internship for AI safety research.
* **2025.07:** 🎉 Invited to serve as a reviewer for **AAAI 2026**.
* **2025.06:** 🚀 Started my journey at DAIL Tech as a Research Intern. The AI startup is founded by my peer [Xiande Huang](https://scholar.google.com/citations?user=dEBN9PoAAAAJ&hl=en).
* **2025.06:** 🎓 Graduated from UESTC with a **First-Class Honours** degree (joint program with UoG).
* **2024.11:** 🏆 Awarded the **Academic Scholarship** (Top 5%, 30,000 RMB).
* **2024.07:** 🎉 One **co-first author** paper accepted to **IEEE Transactions on Industrial Informatics (SCI Q1)**, completed during my first research internship in industrial LVLMs for smart manufacturing.
* **2024.04:** 🎉 One **first author** paper accepted to **IEEE Transactions on Reliability (SCI Q1)**, completed during my first research internship in transfer learning for smart manufacturing, and underwent a year of review.
* **2022.10:** 🌱 The starting point of my academic journey! Joined **Tsinghua University** as a research assistant.

# 📝 Publications & Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/StructAttack_CVPR2026.png' alt="StructAttack" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Models as Lego Builders: Assembling Malice from Benign Blocks via Semantic Blueprints](https://arxiv.org/pdf/2603.07590)

**Chenxi Li\***, Xianggan Liu\*, Dake Shen, Yaosong Du, Zhibo Yao, Hao Jiang, Linyi Jiang, Chengwei Cao, Jingzhe Zhang, RanYi Peng, Peiling Bai, Xiande Huang

[**PDF**](https://arxiv.org/pdf/2603.07590) [**Github**](https://github.com/Yef23/StructAttack) <strong><span class='show_paper_citations' data='YOUR_GOOGLE_SCHOLAR_ID'></span></strong>
- 🔥 **TL;DR:** Proposed *StructAttack*, a black-box one-shot jailbreak framework utilizing semantic slot filling, achieving highly efficient attacks against LVLMs with minimal overhead.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><img src='images/MAP_ECCV2026.png' alt="MAP Architecture" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAP: Mitigating Hallucinations in Large Vision-Language Models with Map-Level Attention Processing](https://arxiv.org/abs/2508.01653)

**Chenxi Li\***, Yichen Guo\*, Benfang Qian, Jinhao You, Kai Tang, Yaosong Du, Zonghao Zhang, Xiande Huang

[**PDF**](https://arxiv.org/pdf/2508.01653) [**Github**](https://github.com/Yef23/MAP) <strong><span class='show_paper_citations' data='YOUR_GOOGLE_SCHOLAR_ID'></span></strong>
- 🔥 **TL;DR:** Proposed *MAP*, a training-free decoding framework that treats hidden states as a 2D semantic map, utilizing Layer-Wise Criss-Cross Attention and logit fusion to effectively mitigate LVLM hallucinations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TII 2024</div><img src='images/DefectGLM_TII2024.png' alt="DefectGLM Architecture" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Large-Scale Visual Language Model Boosted by Contrast Domain Adaptation for Intelligent Industrial Visual Monitoring](https://ieeexplore.ieee.org/abstract/document/10666846/)

**Chenxi Li\***, Huan Wang\*, Yan-Fu Li

[**PDF**](https://ieeexplore.ieee.org/abstract/document/10666846/) [**Github (100+ ⭐)**](https://github.com/WH-HuanWang/Defect-GLM) <strong><span class='show_paper_citations' data='YOUR_GOOGLE_SCHOLAR_ID'></span></strong>
- 🔥 **TL;DR:** Proposed *DefectGLM*, the first LVLM tailored for industrial visual monitoring. It leverages a novel multimodal wafer dataset, LoRA-based contrast visual adaptation, and instruction tuning for highly accurate defect diagnosis.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TRel 2024</div><img src='images/DSPCA_TRel2024.png' alt="DSPC-A Architecture" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Subdomain Pseudolabel Correction and Adaptation Framework for Multiscenario Mechanical Fault Diagnosis](https://ieeexplore.ieee.org/abstract/document/10543130)

**Chenxi Li**, Huan Wang, Te Han

[**PDF**](https://ieeexplore.ieee.org/abstract/document/10543130) <strong><span class='show_paper_citations' data='YOUR_GOOGLE_SCHOLAR_ID'></span></strong>
- 🔥 **TL;DR:** Proposed *DSPC-A*, an end-to-end framework that integrates an auxiliary network to learn clean label distributions from noisy pseudo-labels, enabling precise subdomain alignment for cross-domain fault diagnosis.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TICPS 2024</div><img src='images/IVMMF_TICPS2024.png' alt="IVMMF Architecture" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Intelligent Industrial Visual Monitoring and Maintenance Framework Empowered by Large-Scale Visual and Language Models](https://ieeexplore.ieee.org/abstract/document/10557154)

Huan Wang, **Chenxi Li**, Yan-Fu Li, Fugee Tsung

[**PDF**](https://ieeexplore.ieee.org/abstract/document/10557154) <strong><span class='show_paper_citations' data='YOUR_GOOGLE_SCHOLAR_ID'></span></strong>
- 🔥 **TL;DR:** Proposed *IVMMF*, a comprehensive framework integrating large visual models for defect identification and local-knowledge-augmented LLMs to provide professional maintenance suggestions for engineers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/AIVA_arXiv2025.png' alt="AIVA Architecture" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AIVA: An AI-based Virtual Companion for Emotion-aware Interaction](https://arxiv.org/abs/2509.03212)

**Chenxi Li**

[**PDF**](https://arxiv.org/pdf/2509.03212) <strong><span class='show_paper_citations' data='YOUR_GOOGLE_SCHOLAR_ID'></span></strong>
- 🔥 **TL;DR:** Proposed *AIVA*, an AI virtual companion framework integrating a Multimodal Sentiment Perception Network (MSPN) and emotion-aware prompt engineering to enable empathetic and emotionally aligned human-computer interaction.
</div>
</div>

# 🎖 Honors and Awards
* **[2025]** **Honors Research Degree** (awarded to exceptional graduates for research excellence)
* **[2024]** **Academic Scholarship** (Top 5%, 30,000 RMB)
* **[2024]** **James Watt Innovation Scholarship** 
* **[2024]** **First-Class Scholarship for Outstanding Students** (Top 10%)

# 📖 Educations
* **2026.09 - 2028.06 (Expected)**, MPhil in Computer and Information Engineering, **School of Science and Engineering**, The Chinese University of Hong Kong, Shenzhen (CUHK-SZ)
* **2021.09 - 2025.06**, B.Eng. in Electronic and Information Engineering, **Glasgow College**, University of Electronic Science and Technology of China (UESTC)

# 💻 Internships
- **2025.06 - 2026.02**, Research Intern, [DAIL Tech], China.
- **2022.10 - 2024.04**, Research Assistant, [Tsinghua University], China.