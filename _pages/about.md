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

I am a second-year undergraduate student in School of Mathematical Sciences, Peking University.
I am interested in improve the trustworthiness of Machine Learning, specifically focus on adversarial robustness and explanability.

# 🔥 News
- *2023.06*: &nbsp;🎉 1 Paper (as first author & corresponding author) accepted by **ICML 2023 AdvML-Frontiers Workshop**
- *2023.06*: &nbsp;🇨🇦 I attended **CVPR 2023** at Vancouver and illustrated our poster
- *2023.05*: &nbsp;🥈 Won **Second prize** in Chinese Mathematics Competitions for College Students **(National final)**
- *2023.05*: &nbsp;💡 Our patent *An image classification method based on fair and robust neural networks* has been published
- *2023.05*: &nbsp;🎙 I gave a talk on our CVPR paper in **Safe & Responsible AI workshop** (ICLR 2023 social event) at Tsinghua University.
- *2023.02*: &nbsp;🎉 1 Paper (as first author) accepted by **CVPR 2023**
- *2022.12*: &nbsp;🏅️ Won **First prize** in Chinese Mathematics Competitions for College Students (Beijing Division), and qualified for the finals

# 📝 Papers
(\*: Equal Contribution; ${}^\dagger$: Corresponding Author)

## CFA: Class-wise Calibrated Fair Adversarial Training (CVPR 2023)
**Zeming Wei**, Yifei Wang, Yiwen Guo, Yisen Wang${}^\dagger$
- Theoretically and empirically investigate the preference of different classes for adversarial configurations in Adversarial Training (AT)
- Propose a CFA framework which customizes specific training configurations for each class automatically
- CFA improves both overall robustness and fairness, and can be easily incorporated into other AT variants
- [[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_CFA_Class-Wise_Calibrated_Fair_Adversarial_Training_CVPR_2023_paper.pdf)] [[arviv](https://arxiv.org/abs/2303.14460)] [[code](https://github.com/PKU-ML/CFA)]

## Sharpness-Aware Minimization Alone can Improve Adversarial Robustness (ICML 2023 AdvML-Frontiers Workshop)
**Zeming Wei\*${}^{\boldsymbol\dagger}$**, Jingyu Zhu\*, Yihao Zhang\*
- Theoretically show that using Sharpness-Aware Minimization (SAM) can improve adversarial robustness
- Empirically illustrate that SAM can improve robustness with a friendly computational cost and no decrease in natural accuracy
- Propose that SAM can be regarded as a lightweight substitute for AT under certain requirements
- [[pdf]] [[arxiv]] [[code](https://github.com/weizeming/SAM_AT)]


## Extracting Weighted Finite Automata from Recurrent Neural Networks for Natural Languages (ICFEM 2022)
**Zeming Wei**, Xiyue Zhang, Meng Sun${}^\dagger$
- Identify the transition sparsity and the context dependency problem in WFA extraction from RNNs in natural language tasks
- Propose an extraction approach which complement the missing rules and enhance the context-aware ability
- Our extraction framework is scalable to natural language tasks and of better extration precision
- [[pdf](https://arxiv.org/pdf/2206.14621)] [[arviv](https://arxiv.org/abs/2206.14621)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]


## Weighted Automata Extraction and Explanation of Recurrent Neural Networks for Natural Language Tasks (Preprint)
**Zeming Wei**, Xiyue Zhang, Yihao Zhang, Meng Sun${}^\dagger$
- Extended version for ICFEM 2022 paper
- Propose leveraging the extracted automata for explaining Recurrent Neural Networks with a transition-based word embedding
- [[pdf](https://arxiv.org/pdf/2306.14040)] [[arviv](https://arxiv.org/abs/2306.14040)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]


# 💡 Patents
## An image classification method based on fair and robust neural networks *(patent pending)*
Yisen Wang and **Zeming Wei**
- [[publish announcement](http://epub.cnipa.gov.cn/patent/CN116091838A)]

# 🎖 Honors and Awards
- **Second prize**, Chinese Mathematics Competitions for College Students (National Finals), *2023*
- **First prize**, Chinese Mathematics Competitions for College Students (Beijing Division), *2022*
- **Merit Student**, Peking University, *2022*
- **Huatai Science and Technology Scholarship**, Peking University, *2022*
- **Award for Contributon in Student Organizations**, Peking University, *2021*
- **Yang Fuqing & Wang Yangyuan Academician Scholarship**, Peking Univeristy, *2021*

# 📖 Educations
- *2021.06 - present*, Undergraduate Student, School of Mathematical Sciences, Peking University
- *2020.09 - 2021.06*, Undergraduate Student, College of Engineering, Peking University
- *2017.09 - 2020.06*, Senior High School Student, Beijing No.4 High School

# 💼 Academic Service
- Conference Reviewer: **NeurIPS** 2023

# 🔗 Links
(Alphabetical Order)
- 👨‍🏫 Advisors: [Meng Sun](https://www.math.pku.edu.cn/teachers/sunm/indexen.html), [Yisen Wang](https://yisenwang.github.io)
- 🧑‍🎓 Co-authors: [Yifei Wang](https://yifeiwang.me), [Xiyue Zhang](https://zhang-xiyue.github.io/), [Yihao Zhang](https://zhang-yihao.github.io/)
- 💟 Personal Reference: [Huanran Chen](https://huanranchen.github.io)

