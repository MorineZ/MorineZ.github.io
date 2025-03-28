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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 😊 About Me

- I am a fourth-year Ph.D candidate at School of Biomedical Engineering, University of Science and Technology of China ([USTC](http://bme.ustc.edu.cn/)), supervised by Prof. [S. Kevin Zhou](https://sz.ustc.edu.cn/en/en_research_show/42.html).
- I received my bachelor degree and master degree (Supervisor: [Zhongze Gu](https://bme.seu.edu.cn/2011/1017/c463a12264/page.psp)) from Southeast University ([SEU](https://www.seu.edu.cn)) in 2018 and 2021, respectively.
- My research interests mainly focus on **algorithm fairness** and trustworthy in medical image analysis.

# 🔥 News

<!-- - <span style="color:red;">I am seeking for postdoctoral positions in the field of medical image analysis starting in fall 2025. If you have interest in my research, please feel free to contact me</span>. -->
- *2025.3*： &nbsp; One paper accepted to MIDL-2025 <span style="color:red;">(Oral)</span>.
- *2024.10*: &nbsp; One paper accepted to npj Digital Medicine.
- *2024.09*: &nbsp; One paper accepted to NeurIPS-24.
- *2024.05*: &nbsp; One paper accepted to MICCAI-24.
- *2023.02*: &nbsp; Two papers accepted to MIDL-24.
- *2023.05*: &nbsp; One paper accepted to MICCAI-23.

# 📝 Publications

(Selected publications, `*` indicates equal contribution and ✉️ represents corresponding author.)

### Algorithm Fairness

- `npj Digit. Med.` [Addressing Fairness Issues in Deep Learning-Based Medical Image Analysis: A Systematic Review](https://www.nature.com/articles/s41746-024-01276-5)\
**Zikang Xu**, Jun Li, Qingsong Yao, Han Li, Mingyue Zhao, and S. Kevin Zhou✉️&nbsp;&nbsp;[![](https://img.shields.io/github/stars/XuZikang/FairAdaBN.svg?label=Stars&style=social)](https://github.com/XuZikang/Awesome-MedIA-Fairness)[[code](https://github.com/XuZikang/Awesome-MedIA-Fairness)][[Nature](https://www.nature.com/articles/s41746-024-01276-5)]

- `NeurIPS 2024` [FairMedFM: Fairness Benchmarking for Medical Imaging Foundation Models](https://openreview.net/forum?id=CyrKKKN3fs&referrer=%5Bthe%20profile%20of%20Yuan%20Zhong%5D(%2Fprofile%3Fid%3D~Yuan_Zhong5))\
**Ruinan Jin\***, **Zikang Xu\***, **Yuan Zhong\***, Qingsong Yao, Qi Dou✉️, S. Kevin Zhou✉️, Xiaoxiao Li✉️&nbsp;&nbsp;[![](https://img.shields.io/github/stars/FairMedFM/FairMedFM.svg?label=Stars&style=social)](https://github.com/FairMedFM/FairMedFM)[[code](https://github.com/FairMedFM/FairMedFM)][[OpenReview](https://openreview.net/forum?id=CyrKKKN3fs&referrer=%5Bthe%20profile%20of%20Yuan%20Zhong%5D(%2Fprofile%3Fid%3D~Yuan_Zhong5))]

- `MICCAI 2023` [FairAdaBN: Mitigating unfairness with adaptive batch normalization and its application to dermatological disease classification](https://arxiv.org/pdf/2303.08325)\
**Zikang Xu**, Shang Zhao, Quan Quan, Qingsong Yao, S. Kevin Zhou✉️&nbsp;&nbsp;[![](https://img.shields.io/github/stars/XuZikang/Awesome-MedIA-Fairness.svg?label=Stars&style=social)](https://github.com/XuZikang/FairAdaBN)[[code](https://github.com/XuZikang/FairAdaBN)][[Springer](https://link.springer.com/chapter/10.1007/978-3-031-43895-0_29)]

- `arXiv 2024` [APPLE: Adversarial Privacy-aware Perturbations on Latent Embedding for Unfairness Mitigation](https://arxiv.org/abs/2403.05114)\
**Zikang Xu**, Fenghe Tang, Quan Quan, Qingsong Yao, S. Kevin Zhou✉️ &nbsp;&nbsp;[![](https://img.shields.io/github/stars/XuZikang/APPLE.svg?label=Stars&style=social)](https://github.com/XuZikang/APPLE)[[code](https://github.com/XuZikang/APPLE)][[arXiv](https://arxiv.org/abs/2403.05114)]

- `arXiv 2023` [Inspecting Model Fairness in Ultrasound Segmentation Tasks](https://arxiv.org/abs/2312.02501)\
**Zikang Xu**, Fenghe Tang, Quan Quan, Jianrui Ding, Chunping Ning, S. Kevin Zhou✉️ &nbsp;&nbsp;[[arXiv](https://arxiv.org/abs/2312.02501)]

### Landmark Detection

- `MICCAI 2024` [SIX-Net: Spatial-Context Information miX-up for Electrode Landmark Detection <span style="color:red;">(Early Accept)</span>](https://link.springer.com/chapter/10.1007/978-3-031-72378-0_32)\
Xinyi Wang, **Zikang Xu**, Heqin Zhu, Qingsong Yao, Yiyong Sun, S. Kevin Zhou✉️ &nbsp;&nbsp;[[Springer](https://link.springer.com/chapter/10.1007/978-3-031-72378-0_32)]

- `MIDL 2024` [OFELIA: Optical Flow-based Electrode LocalIzAtion](https://openreview.net/pdf?id=8245ExLB4I)\
Xinyi Wang, **Zikang Xu**, Qingsong Yao, Yiyong Sun, S. Kevin Zhou✉️ &nbsp;&nbsp;[[OpenReview](https://openreview.net/pdf?id=8245ExLB4I)]

### Medical Image Segmentation

- `Med. Image Anal. 2024` [LACOSTE: Exploiting stereo and temporal contexts for surgical instrument segmentation](https://www.sciencedirect.com/science/article/pii/S0956566322008120)\
Qiyuan Wang, Shang Zhao, **Zikang Xu**, S. Kevin Zhou✉️ &nbsp;&nbsp;[[ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0956566322008120)]

- `MIDL 2024` [Slide-SAM: Medical SAM Meets Sliding Window <span style="color:red;">(Oral)</span>](https://openreview.net/forum?id=LNdU9RTv3L&referrer=%5Bthe%20profile%20of%20Fenghe%20Tang%5D(%2Fprofile%3Fid%3D~Fenghe_Tang1))\
Quan Quan\*, Fenghe Tang\*, **Zikang Xu**, Heqin Zhu, S. Kevin Zhou✉️ &nbsp;&nbsp;[![](https://img.shields.io/github/stars/Curli-quan/Slide-SAM.svg?label=Stars&style=social)](https://github.com/Curli-quan/Slide-SAM)[[code](https://github.com/Curli-quan/Slide-SAM)][[arXiv](https://arxiv.org/abs/2311.10121v3)]

### MISC

- `MIDL 2025` [Style-Aligned Image Composition for Robust Detection of Abnormal Cells in Cytopathology <span style="color:red;">(Oral)</span>](https://openreview.net/forum?id=VQrbxORlvv#discussion))\
Qiuyi Qi\*, Xin Li\*, Ming Kong, Zikang Xu, Bingdi Chen, Qiang Zhu✉️, S Kevin Zhou✉️ &nbsp;&nbsp;[![](https://img.shields.io/github/stars/Joey-Qi/SAIC.svg?label=Stars&style=social)](https://github.com/Joey-Qi/SAIC)[[code](https://github.com/Curli-quan/Slide-SAM)][[OpenReview](https://openreview.net/pdf?id=VQrbxORlvv)]

# 🎖 Honors and Awards

- *2021, 2023, 2024*: Academic First Class Scholarship in USTC
- *2022*: Academic Second Class Scholarship in USTC
- *2021*: Suzhou Industrial Park Scholarship

# 📖 Educations

- *2021.09 - (now)*, Ph.D. student, Suzhou Institute for Advanced Research, University of Science and Technology of China ([USTC](http://en.ustc.edu.cn/)), Suzhou, China
- *2018.09 - 2021.06*, Master, School of Biological Science and Medical Engineering, Southeast University ([SEU](https://bme.seu.edu.cn)), Nanjing, China
- *2016.09 - 2018.06*, Undergraduate, School of Biological Science and Medical Engineering, Southeast University ([SEU](https://bme.seu.edu.cn)), Nanjing, China
- *2014.09 - 2016.06*, Undergraduate, Chien-Shiung Wu College (honors college), Southeast University ([SEU](https://wjx.seu.edu.cn)), Nanjing, China
  
# 💬 Professional Services

*Journal Reviewers:*

- IEEE Transactions on Medical Imaging
- ACM Transactions on Computing for Healthcare

*Conference Reviewers:*

- International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI 2024)
- International Conference on Bioinformatics and Biomedicine (BIBM 2024)
- IEEE International Symposium on Biomedical Imaging (ISBI 2025)

*Teaching Assistant:*

- *2022 Fall*, USTC, Medical Image Computing (BMED6208P.01_152261)
- *2023 Fall*, USTC, Medical Image Computing (BMED6208P.01_152261)

# 💬 Invited Talks

- *2024.10*, **Benchmarking Fairness in Medical Foundation Models.** IEEE International Conference on Universal Village (IEEE UV 2024)

# 💻 Internships

- *2023.06 - 2023.10*, Fuwai Hospital, Chinese Academy of Medical Sciences, Beijing, China
