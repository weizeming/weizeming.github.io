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

I'm Zeming Wei (<font face=STKaiti>魏泽明</font>), a third-year undergraduate at School of Mathematical Sciences, Peking University. I was also a visiting student at UC Berkeley in Fall, 2023. I am interested in improving the trustworthiness of Machine Learning, specifically focusing on mechanism interpretability, adversarial robustness, and generative AI safety.  <a href='https://scholar.google.com/citations?user=Kyn1zdQAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

If you are interested in collaborating with me, please send me an email.


# 🔥 News
- *2024.05*: &nbsp;🎉 1 Paper (as corresponding author) accepted by **ICML 2024**.
- *2024.04*: &nbsp;💫 I reached **100 citations** according to Google Scholar. Thanks all co-authors!
- *2024.03*: &nbsp;🎉 2 Papers (as corresponding author) accepted by **ICLR 2024 R2-FM Workshop**.
- *2023.12*: &nbsp;💯 I achieved a **full GPA (4.0/4.0)** during my study at UC Berkeley (with 1 **A** and 2 **A+** grades).
- *2023.11*: &nbsp;🎙 I gave a lightning talk on our LLM safety paper at Constellation, Berkeley.
- *2023.10*: &nbsp;🔗 I serve as a fellow of Berkeley AI Safety Initiative for Students (BASIS).
- *2023.09*: &nbsp;🎖 I received the **Exceptional Award for Academic Innovation** in the academic year of 2022-2023 (**only 1 awardee** among undergraduates in School of Mathematical Sciences, Peking University, **Top 0.1%**).
- *2023.08*: &nbsp;🎉 1 Paper (as first author) accepted by **Journal of Logical and Algebraic Methods in Programming**.
- *2023.07*: &nbsp;🏖 I attended **ICML 2023** at Honolulu and illustrated our workshop poster.
- *2023.06*: &nbsp;🎉 1 Paper (as corresponding author) accepted by **ICML 2023 AdvML-Frontiers Workshop**.
- *2023.06*: &nbsp;🍁 I attended **CVPR 2023** at Vancouver and illustrated our poster.
- *2023.05*: &nbsp;🥈 Won **Second prize** in Chinese Mathematics Competitions for Undergraduates **(National final)**.
- *2023.05*: &nbsp;🎙 I gave a talk on our CVPR paper in **Safe & Responsible AI workshop** (ICLR 2023 social event) at Tsinghua University.
- *2023.02*: &nbsp;🎉 1 Paper (as first author) accepted by **CVPR 2023**.
- *2022.12*: &nbsp;🥇 Won **First prize** in Chinese Mathematics Competitions for Undergraduates (Beijing Division), and qualified for the finals.

# 📝 First-Author Papers
  
- Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations (Preprint)

&emsp;**Zeming Wei**, Yifei Wang, Yisen Wang  

[[pdf](https://arxiv.org/pdf/2310.06387)] [[arxiv](https://arxiv.org/abs/2310.06387)] [[code](https://github.com/PKU-ML/adv-icl)] [[website](https://adv-icl.github.io/)]  


## CFA: Class-wise Calibrated Fair Adversarial Training (CVPR 2023)
- **Zeming Wei**, Yifei Wang, Yiwen Guo, Yisen Wang
- [[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_CFA_Class-Wise_Calibrated_Fair_Adversarial_Training_CVPR_2023_paper.pdf)] [[arxiv](https://arxiv.org/abs/2303.14460)] [[code](https://github.com/PKU-ML/CFA)]   

## Weighted Automata Extraction and Explanation of Recurrent Neural Networks for Natural Language Tasks (Journal of Logical and Algebraic Methods in Programming)
- **Zeming Wei**, Xiyue Zhang, Yihao Zhang, Meng Sun
- [[pdf](https://arxiv.org/pdf/2306.14040)] [[arxiv](https://arxiv.org/abs/2306.14040)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]  

## Extracting Weighted Finite Automata from Recurrent Neural Networks for Natural Languages (ICFEM 2022)
- **Zeming Wei**, Xiyue Zhang, Meng Sun
- [[pdf](https://arxiv.org/pdf/2206.14621)] [[arxiv](https://arxiv.org/abs/2206.14621)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]  


# 📝 Corresponding-Author Papers
(\*: Equal Contribution; ${}^\dagger$: Corresponding Author)

## On the Duality Between Sharpness-Aware Minimization and Adversarial Training (ICML 2024)
- Yihao Zhang\*, Hangzhou He\*, Jingyu Zhu\*, Huanran Chen, Yifei Wang, **Zeming Wei${}^{\boldsymbol\dagger}$**
- [[pdf](https://arxiv.org/pdf/2402.15152.pdf)] [[arxiv](https://arxiv.org/abs/2402.15152)] [[code](https://github.com/weizeming/SAM_AT)]  

## Exploring the Robustness of In-Context Learning with Noisy Labels (ICLR 2024 R2-FM Workshop)
- Chen Cheng\*, Xinzhi Yu\*, Haodong Wen\*, Jingsong Sun, Guanzhang Yue, Yihao Zhang, **Zeming Wei${}^{\boldsymbol\dagger}$**
- [[pdf](https://arxiv.org/pdf/2404.18191)] [[arxiv](https://arxiv.org/abs/2404.18191)] [[code](https://github.com/InezYu0928/in-context-learning)]  

## Boosting Jailbreak Attack with Momentum (ICLR 2024 R2-FM Workshop)
- Yihao Zhang\*, **Zeming Wei\*${}^{\boldsymbol\dagger}$**
- TBA

## Sharpness-Aware Minimization Alone can Improve Adversarial Robustness (ICML 2023 AdvML-Frontiers Workshop)
- **Zeming Wei\*${}^{\boldsymbol\dagger}$**, Jingyu Zhu\*, Yihao Zhang\*
- [[pdf](https://arxiv.org/pdf/2305.05392)] [[arxiv](https://arxiv.org/abs/2305.05392)] [[code](https://github.com/weizeming/SAM_AT)]  


# 💡 Patents
## An image classification method based on fair and robust neural networks *(patent pending)*
Yisen Wang and **Zeming Wei**
- Publication ID: CN116091838A
- [[Publication announcement](http://epub.cnipa.gov.cn/patent/CN116091838A)]

# 🎖 Honors and Awards
- **Exceptional Award for Academic Innovation (Top 0.1%)**, Peking University, *2023*
- **Merit Student (Top 10%)**, Peking University, *2023*
- **University Scholarship**, Peking University, *2023*
- **Second prize**, Chinese Mathematics Competitions for Undergraduates (National Final), *2023*
- **First prize**, Chinese Mathematics Competitions for Undergraduates (Beijing Division), *2022*
- **Merit Student (Top 10%)**, Peking University, *2022*
- **University Scholarship**, Peking University, *2022*
- **Award for Contribution in Student Organizations**, Peking University, *2021*
- **University Scholarship**, Peking University, *2021*

# 📖 Educations
- *2023.08 - 2023.12*, Visiting Student, University of California Berkeley
- *2021.06 - 2025.06 (expected)*, Undergraduate Student, School of Mathematical Sciences, Peking University
- *2020.09 - 2021.06*, Undergraduate Student, College of Engineering, Peking University
- *2017.09 - 2020.06*, Senior High School Student, Beijing No.4 High School

# 💼 Academic Service
- **Journal Reviewer**: TMLR
- **Conference Reviewer**: NeurIPS 2023, ICLR 2024, AISTATS 2024, ICML 2024, ECCV 2024
- **Workshop Reviewer**: XAIA (@NeurIPS 2023)
- **Fellow**, Berkeley AI Safety Initiative for Students (BASIS), UC Berkeley

# 🔗 Links
(Alphabetical Order)
- 👨‍🏫 **Advisors**: [Meng Sun](https://www.math.pku.edu.cn/teachers/sunm/indexen.html), [David Wagner](https://people.eecs.berkeley.edu/~daw/) (UCB), [Yifei Wang](https://yifeiwang77.com) (MIT), [Yisen Wang](https://yisenwang.github.io)
- 🧑‍🎓 **Co-authors**: [Huanran Chen](https://huanranchen.github.io), [Julien Piet](https://people.eecs.berkeley.edu/~julien.piet/), [Xiyue Zhang](https://zhang-xiyue.github.io/), [Yihao Zhang](https://zhang-yihao.github.io/)
