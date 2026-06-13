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

I am a **2025 master's graduate from the University of Chinese Academy of Sciences (UCAS)**, currently a **Research Intern at the Max Planck Institute for Security and Privacy (MPI-SP)**, working under the supervision of [**Prof. Thorsten Holz**](https://www.mpi-sp.org/holz).

My research investigates the **safety, robustness, and trustworthiness of LLM-integrated systems**, with a focus on **multi-agent architectures** and **adversarial evaluation**. I am particularly interested in characterizing attacks along a continuous **syntactic–semantic spectrum** and developing adaptive defenses that respond to the interpretation depth each threat requires. A representative line of work is the **"Capability Paradox"** in hierarchical multi-agent systems — showing that *stronger* auditor LLMs can paradoxically *reduce* overall system security by expanding the attack surface through cross-context instruction handling.

This security focus is grounded in an extensive engineering background in **generative AI**. Through research and internships at **China Telecom (TeleAI)**, **Alibaba**, and **Meizu**, I have built and fine-tuned diffusion and video-synthesis models (CogVideoX, SDXL, DiT) and vision-language models (Qwen-VL-Chat, GLM4V) at scale — giving me a deep, systems-level understanding of the very models I now aim to secure.

<img src="https://img.shields.io/endpoint?url={{ url }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026 (Under Review)</div><img src='images/mamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

The Capability Paradox: How Smarter Auditors Make Multi-Agent Systems Less Secure

**Qiqi Liu**, Thorsten Holz, Runhan Song, Shilin Ye

*Submitted to NeurIPS 2026 — LLM Robustness & Multi-Agent Security.* Lead & corresponding author: proposed the capability paradox framework, and led experimental design, evaluation, and writing.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIFS (Under Revision)</div><img src='images/mamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MIDS: Monitoring Anomalies with Bidirectional Mamba

**Qiqi Liu**, Yuyan Sun, Runhan Song, Heng Zhang, Limin Sun

[**Project**](https://github.com/vrmei/CAN-Tampering) [**Dataset**](https://drive.google.com/drive/folders/1I9uHpOG8W_Fb9ShoNn6pQB_5Xm83wMww)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Computer Networks (Under Review)</div><img src='images/mo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MGCL: Tor Website Fingerprinting for Reload Scenario

Runhan Song, **Qiqi Liu**, Jiawei Yin, Liang Meng, Lei Cui, Wei Wang, Zhi Ding, Lun Li, Zhuo Hao
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WCMC 2021</div><img src='images/privacy.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Privacy Protection Scheme for IoT Big Data Based on Time and Frequency Limitation](https://onlinelibrary.wiley.com/doi/10.1155/2021/5545648)

Lei Zhang, Yu Huo, Qiang Ge, Yuxiang Ma, **Qiqi Liu**, Wenlei Ouyang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICPADS 2023</div><img src='images/ICAPDS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Binary Malware Detection via Heterogeneous Information Deep Ensemble Learning](https://ieeexplore.ieee.org/document/10475976)

Runhan Song, Lun Li, Lei Cui, **Qiqi Liu**, Jin Gao
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WAC 2021</div><img src='images/bin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Binary Vulnerability Mining Based on Long Short-Term Memory Network](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9559467)

Wenlei Ouyang, Meng Li, **Qiqi Liu**, Jianchao Wang
</div>
</div>

# 📖 Professional Service
- Reviewer, IEEE Transactions on Information Forensics and Security (TIFS), 2024–2025 (2 papers)
- Reviewer, IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2024–2025 (2 papers)
- Reviewer, IEEE Transactions on Multimedia (TMM), 2024–2025 (1 paper)

# 📖 Educations
- *2022.09 - 2025.07*: M.Sc. in Electronic Information, University of Chinese Academy of Sciences (Recommended Admission). GPA 3.64/4.00, Top 15%.
- *2018.09 - 2022.07*: B.Eng. in Information Security, Henan University. Top 5%.

# 🔬 Research Experience
- *2026.02 - Present*, **Max Planck Institute for Security and Privacy (MPI-SP)**, Research Intern (Remote). Advisor: Prof. Thorsten Holz. Multi-agent system security & adversarial evaluation of tool-integrated LLM agents.
- *2024.10 - 2025.04*, **China Telecom (TeleAI), EVOL Lab**, AIGC Research Intern. Depth-conditioned, fidelity-preserving video synthesis; ControlNeXt + CogVideoX on 720K clips (~7TB), distributed training on 4×8×H100.
- *2024.06 - 2024.10*, **Alibaba Group, AI Algorithm Department**, AIGC Research Intern. Style-image synthesis and multimodal fine-tuning (SDXL, DiT); LoRA on image–text pairs.
- *2024.03 - 2024.06*, **Meizu Technology, AI Vision Algorithm Department**, AI Algorithm Intern. Assistive phone-UI agents; vision-language models (Qwen-VL-Chat, GLM4V) and a verifiable OCR + detection + LLM framework.

# 💻 Industry Experience
- *2025.04 - 2025.12*, **Zseads Technology**, AIGC Algorithm Engineer (Intern → Full-time). Flux-Fill restoration LoRA framework (memory down to ~25%, ZeRO-3); SOTA-level hand-restoration pipeline based on Wan2.1.

# 🏆 Selected Projects & Competitions
- **Project 3DTS — Diffusion-Based Long-term Time Series Synthesis.** A diffusion probabilistic framework for time-series modeling that addresses the scalability bottleneck of Transformer-based models over extended horizons, with a custom refinement network for temporal stability.
- 2023, 8th Place Nationwide, DataCon Data Integrity and Reliability Competition.
- 2019, First Prize, ISCC National Information Protection and Technical Excellence Competition.
