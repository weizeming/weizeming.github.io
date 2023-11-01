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

I am a third-year undergraduate at School of Mathematical Sciences, Peking University.
Currently, I am a visiting student at UC Berkeley.
I am interested in improving the trustworthiness of Machine Learning, specifically focusing on adversarial robustness and explainability.

# 🔥 News
- *2023.10*: &nbsp;✨ New [preprint](https://arxiv.org/abs/2310.06387) on **LLM Safety** is available at arxiv.
- *2023.09*: &nbsp;🎖 I won the **Award for Academic Innovation** in the academic year 2022-2023 (**only 1 awardee** among undergraduates in School of Mathematical Sciences, Peking University, **Top 0.1%**).
- *2023.08*: &nbsp;🎉 1 Paper (as first author) accepted by **Journal of Logical and Algebraic Methods in Programming**.
- *2023.08*: &nbsp;🏫 I started a visiting student program at **UC Berkeley** in Fall 2023.
- *2023.07*: &nbsp;🏖 I attended **ICML 2023** at Honolulu and illustrated our workshop poster.
- *2023.07*: &nbsp;🔍 I reviewed 11 papers for **NeurIPS 2023** (9 regular + 2 ethics).
- *2023.06*: &nbsp;🎉 1 Paper (as first author & corresponding author) accepted by **ICML 2023 AdvML-Frontiers Workshop**.
- *2023.06*: &nbsp;🍁 I attended **CVPR 2023** at Vancouver and illustrated our poster.
- *2023.05*: &nbsp;🥈 Won **Second prize** in Chinese Mathematics Competitions for College Students **(National final)**.
- *2023.05*: &nbsp;🎙 I gave a talk on our CVPR paper in **Safe & Responsible AI workshop** (ICLR 2023 social event) at Tsinghua University.
- *2023.02*: &nbsp;🎉 1 Paper (as first author) accepted by **CVPR 2023**.
- *2022.12*: &nbsp;🥇 Won **First prize** in Chinese Mathematics Competitions for College Students (Beijing Division), and qualified for the finals.

# 📝 Selected Papers
(\*: Equal Contribution; ${}^\dagger$: Corresponding Author)

## Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations (Preprint)
**Zeming Wei**, Yifei Wang, Yisen Wang${}^\dagger$
- Uncover the vulnerability and robustness of aligned language models under only few in-context demonstrations without fine-tuning
- Propose In-Context Attack (ICA) and In-Context Defense (ICD) to jailbreak and guard aligned language models
- Shed light on the potential of in-context learning (ICL) to manipulate the alignment of LLMs
- [[pdf](https://arxiv.org/pdf/2310.06387)] [[arxiv](https://arxiv.org/abs/2310.06387)]

## CFA: Class-wise Calibrated Fair Adversarial Training (CVPR 2023)
**Zeming Wei**, Yifei Wang, Yiwen Guo, Yisen Wang${}^\dagger$
- Theoretically and empirically investigate the preference of different classes for adversarial configurations in Adversarial Training (AT)
- Propose a CFA framework that customizes specific training configurations for each class automatically
- CFA improves both overall robustness and fairness, and can be easily incorporated into other AT variants
- [[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_CFA_Class-Wise_Calibrated_Fair_Adversarial_Training_CVPR_2023_paper.pdf)] [[arxiv](https://arxiv.org/abs/2303.14460)] [[code](https://github.com/PKU-ML/CFA)]

## Sharpness-Aware Minimization Alone can Improve Adversarial Robustness (ICML 2023 Workshop)
**Zeming Wei\*${}^{\boldsymbol\dagger}$**, Jingyu Zhu\*, Yihao Zhang\*
- Theoretically show that using Sharpness-Aware Minimization (SAM) can improve adversarial robustness
- Empirically illustrate that SAM can improve robustness with a friendly computational cost and no decrease in natural accuracy
- Propose that SAM can be regarded as a lightweight substitute for AT under certain requirements
- [[pdf](https://arxiv.org/pdf/2305.05392)] [[arxiv](https://arxiv.org/abs/2305.05392)] [[code](https://github.com/weizeming/SAM_AT)]

## Weighted Automata Extraction and Explanation of Recurrent Neural Networks for Natural Language Tasks (Journal of Logical and Algebraic Methods in Programming)
**Zeming Wei**, Xiyue Zhang, Yihao Zhang, Meng Sun${}^\dagger$
- Extending WFA extraction methods of RNNs from formal to natural language tasks by identifying transition sparsity and context dependency problems
- Propose an RNN interpretation framework with a transition-based word embedding of the extracted automata  
- Further propose two applications (pretraining and adversarial attack) on RNNs with the embedding
- [[pdf](https://arxiv.org/pdf/2306.14040)] [[arxiv](https://arxiv.org/abs/2306.14040)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]


# 💡 Patents
## An image classification method based on fair and robust neural networks *(patent pending)*
Yisen Wang and **Zeming Wei**
- Publication ID: CN116091838A
- [[Publication announcement](http://epub.cnipa.gov.cn/patent/CN116091838A)]

# 🎖 Honors and Awards
- **Award for Academic Innovation (Top 0.1%)**, Peking University, *2023*
- **Merit Student (Top 10%)**, Peking University, *2023*
- **University Scholarship**, Peking University, *2023*
- **Second prize**, Chinese Mathematics Competitions for Undergraduates (National Final), *2023*
- **First prize**, Chinese Mathematics Competitions for Undergraduates (Beijing Division), *2022*
- **Merit Student (Top 10%)**, Peking University, *2022*
- **University Scholarship**, Peking University, *2022*
- **Award for Contribution in Student Organizations**, Peking University, *2021*
- **University Scholarship**, Peking University, *2021*

# 📖 Educations
- *2023.08 - 2023.12 (expected)*, Visiting Student, University of California Berkeley
- *2021.06 - 2025.06 (expected)*, Undergraduate Student, School of Mathematical Sciences, Peking University
- *2020.09 - 2021.06*, Undergraduate Student, College of Engineering, Peking University
- *2017.09 - 2020.06*, Senior High School Student, Beijing No.4 High School

# 💼 Academic Service
- **Journal Reviewer**: TMLR
- **Conference Reviewer**: NeurIPS 2023, ICLR 2024, AISTATS 2024
- **Workshop Reviewer**: XAIA (@NeurIPS 2023)
- **Fellow**, Berkeley AI Safety Initiative for Students (BASIS), UC Berkeley

# 🔗 Links
(Alphabetical Order)
- 👨‍🏫 **Advisors**: [Meng Sun](https://www.math.pku.edu.cn/teachers/sunm/indexen.html), [Yisen Wang](https://yisenwang.github.io)
- 🧑‍🎓 **Co-authors**: [Huanran Chen](https://huanranchen.github.io), [Yifei Wang](https://yifeiwang77.com), [Xiyue Zhang](https://zhang-xiyue.github.io/), [Yihao Zhang](https://zhang-yihao.github.io/)

