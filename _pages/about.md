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
- *2023.02*: &nbsp;🎉 1 Paper (as first author) accepted by **CVPR 2023**
- *2022.12*: &nbsp;🏆 Won **First prize** in Chinese Mathematics Competitions for College Students (Beijing Division), and qualified for the finals

# 📝 Research Publications

## CFA: Class-wise Calibrated Fair Adversarial Training (CVPR 2023)
**Zeming Wei**, Yifei Wang, Yiwen Guo, Yisen Wang
- Theoretically and empirically investigate the preference of different classes for adversarial configurations in Adversarial Training (AT)
- Propose a CFA framework which customizes specific training configurations for each class automatically
- CFA improves both overall robustness and fairness, and can be easily incorporated into other AT variants
- [[pdf](https://arxiv.org/pdf/2303.14460)] [[arviv](https://arxiv.org/abs/2303.14460)] [[code](https://github.com/PKU-ML/CFA)]

## Extracting Weighted Finite Automata from Recurrent Neural Networks for Natural Languages (ICFEM 2022)
**Zeming Wei**, Xiyue Zhang, Meng Sun
- Identify the transition sparsity and the context dependency problem in WFA extraction from RNNs in natural language tasks
- Propose an extraction approach which complement the missing rules and enhance the context-aware ability
- Our extraction framework is scalable to natural language tasks and of better extration precision
- [[pdf](https://arxiv.org/pdf/2206.14621)] [[arviv](https://arxiv.org/abs/2206.14621)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]

# 💡 Patents
## An image classification method based on fair and robust neural networks *(patent pending)*
Yisen Wang and **Zeming Wei**

# 💻 Projects

## Using Z3 for Formal Modeling and Verification of FNN Global Robustness
- Course project for ''Techniques and Methods for Programming'' 
- Propose a complete specification and implementation of FNN Global Robustness verification utilizing the SMT solver Z3
- One paper accepted by SEKE 2023
- [[pdf](https://arxiv.org/pdf/2304.10558.pdf)] [[arxiv](https://arxiv.org/abs/2304.10558.pdf)] [[code](https://github.com/weizeming/Z3_for_Verification_of_FNN_Global_Robustness)]

# 🎖 Honors and Awards
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
- Conference Reviewer: NeurIPS 2023
