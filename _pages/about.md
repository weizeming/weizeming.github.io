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

<style>
ul {
  line-height: 1.5;
}
</style>

<span class='anchor' id='about-me'></span>

I'm Zeming Wei (<font face=STKaiti>魏泽明</font>), an undergraduate at School of Mathematical Sciences, Peking University. I was also a visiting student at UC Berkeley in Fall, 2023. I am interested in improving the trustworthiness of Machine Learning, specifically focusing on mechanism interpretability, adversarial robustness, and generative AI safety.  <a href='https://scholar.google.com/citations?user=Kyn1zdQAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

If you are interested in collaborating with me, please send me an email.


## 🔥 News
- *2024.10*: &nbsp;🎖 I received the **May 4th Scholarship**, which is **the highest honor scholarship** of Peking University (only 1 awardee among undergraduates in School of Mathematical Sciences, **Top 0.1%**).
- *2024.09*: &nbsp;🎉 1 Paper (as first author) accepted by **SETTA 2024**.
- *2024.09*: &nbsp;🎉 3 Papers accepted by **NeurIPS 2024**.
- *2024.07*: &nbsp;🎡 I attended **ICML 2024** at Vienna and illustrated our poster.
- *2024.05*: &nbsp;🎉 1 Paper (as corresponding author) accepted by **ICML 2024**.
- *2024.04*: &nbsp;💫 I reached **100 citations** according to Google Scholar. Thanks all co-authors!
- *2024.03*: &nbsp;🎉 2 Papers (as corresponding author) accepted by **ICLR 2024 R2-FM Workshop**.
- *2023.12*: &nbsp;💯 I achieved a **full GPA (4.0/4.0)** during my study at UC Berkeley (with 1 **A** and 2 **A+** grades).
- *2023.11*: &nbsp;🎙 I gave a lightning talk on our LLM safety paper at Constellation, Berkeley.
- *2023.10*: &nbsp;🔗 I serve as a fellow of Berkeley AI Safety Initiative for Students (BASIS).
- *2023.09*: &nbsp;🎖 I received the **Exceptional Award for Academic Innovation** of Peking University (only 1 awardee among undergraduates in School of Mathematical Sciences, **Top 0.1%**).
- *2023.08*: &nbsp;🎉 1 Paper (as first author) accepted by **Journal of Logical and Algebraic Methods in Programming**.
- *2023.07*: &nbsp;🏖 I attended **ICML 2023** at Honolulu and illustrated our workshop poster.
- *2023.06*: &nbsp;🎉 1 Paper (as corresponding author) accepted by **ICML 2023 AdvML-Frontiers Workshop**.
- *2023.06*: &nbsp;🍁 I attended **CVPR 2023** at Vancouver and illustrated our poster.
- *2023.05*: &nbsp;🥈 Won **Second prize** in Chinese Mathematics Competitions for Undergraduates **(National final, Top 0.2%)**.
- *2023.05*: &nbsp;🎙 I gave a talk on our CVPR paper in **Safe & Responsible AI workshop** (ICLR 2023 social event) at Tsinghua University.
- *2023.02*: &nbsp;🎉 1 Paper (as first author) accepted by **CVPR 2023**.
- *2022.12*: &nbsp;🥇 Won **First prize** in Chinese Mathematics Competitions for Undergraduates (Beijing Division), and qualified for the finals.

## 📝 Selected Papers
### (${}^{\boldsymbol\dagger}$: Corresponding Author; \*: Equal Contribution)
- **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations**\\
**Zeming Wei**, Yifei Wang, Ang Li, Yichuan Mo, Yisen Wang\\
**_Preprint_**\\
[[pdf](https://arxiv.org/pdf/2310.06387)] [[arxiv](https://arxiv.org/abs/2310.06387)] [[code](https://github.com/PKU-ML/adv-icl)] 

- **MILE: A Mutation Testing Framework of In-Context Learning Systems**\\
**Zeming Wei**, Yihao Zhang, Meng Sun\\
**_SETTA 2024_**\\
[[pdf](https://arxiv.org/pdf/2409.04831.pdf)] [[arxiv](https://arxiv.org/abs/2409.04831)] [[code](https://github.com/weizeming/MILE)]  
  
- **On the Duality Between Sharpness-Aware Minimization and Adversarial Training**\\
Yihao Zhang\*, Hangzhou He\*, Jingyu Zhu\*, Huanran Chen, Yifei Wang, **Zeming Wei${}^{\boldsymbol\dagger}$**\\
**_ICML 2024_**\\
[[pdf](https://arxiv.org/pdf/2402.15152.pdf)] [[arxiv](https://arxiv.org/abs/2402.15152)] [[code](https://github.com/weizeming/SAM_AT)]  

- **Boosting Jailbreak Attack with Momentum**\\
Yihao Zhang\*, **Zeming Wei\*${}^{\boldsymbol\dagger}$**\\
**_ICLR 2024 R2-FM Workshop_**\\
[[pdf](https://arxiv.org/pdf/2405.01229)] [[arxiv](https://arxiv.org/abs/2405.01229)] [[code](https://github.com/weizeming/momentum-attack-llm)]

- **Exploring the Robustness of In-Context Learning with Noisy Labels**\\
Chen Cheng\*, Xinzhi Yu\*, Haodong Wen\*, Jingsong Sun, Guanzhang Yue, Yihao Zhang, **Zeming Wei${}^{\boldsymbol\dagger}$**\\
**_ICLR 2024 R2-FM Workshop_**\\
[[pdf](https://arxiv.org/pdf/2404.18191)] [[arxiv](https://arxiv.org/abs/2404.18191)] [[code](https://github.com/InezYu0928/in-context-learning)]
  
- **Weighted Automata Extraction and Explanation of Recurrent Neural Networks for Natural Language Tasks**\\
**Zeming Wei**, Xiyue Zhang, Yihao Zhang, Meng Sun\\
**_Journal of Logical and Algebraic Methods in Programming_**\\
[[pdf](https://arxiv.org/pdf/2306.14040)] [[arxiv](https://arxiv.org/abs/2306.14040)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]  

- **CFA: Class-wise Calibrated Fair Adversarial Training**\\
**Zeming Wei**, Yifei Wang, Yiwen Guo, Yisen Wang\\
**_CVPR 2023_**\\
[[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_CFA_Class-Wise_Calibrated_Fair_Adversarial_Training_CVPR_2023_paper.pdf)] [[arxiv](https://arxiv.org/abs/2303.14460)] [[code](https://github.com/PKU-ML/CFA)]  

- **Sharpness-Aware Minimization Alone can Improve Adversarial Robustness**\\
**Zeming Wei\*${}^{\boldsymbol\dagger}$**, Jingyu Zhu\*, Yihao Zhang\*\\
**_ICML 2023 AdvML-Frontiers Workshop_**\\
[[pdf](https://arxiv.org/pdf/2305.05392)] [[arxiv](https://arxiv.org/abs/2305.05392)] [[code](https://github.com/weizeming/SAM_AT)]  

- **Extracting Weighted Finite Automata from Recurrent Neural Networks for Natural Languages**\\
**Zeming Wei**, Xiyue Zhang, Meng Sun\\
**_ICFEM 2022_**\\
[[pdf](https://arxiv.org/pdf/2206.14621)] [[arxiv](https://arxiv.org/abs/2206.14621)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]  

## 💡 Patents
- **An image classification method based on fair and robust neural networks (patent pending)**\\
Yisen Wang and **Zeming Wei**\\
Publication ID: CN116091838A\\
[[Publication announcement](http://epub.cnipa.gov.cn/patent/CN116091838A)]

## 🎖 Honors and Awards
- **May 4th Scholarship (Top 0.1%)**, **the highest honor scholarship** of Peking University, *2024*
- **Merit Student (Top 10%)**, Peking University, *2024*
- **Spotlight Award (Best Paper)**, 1st ICML Workshop on In-Context Learning, *2024*
- **Exceptional Award for Academic Innovation (Top 0.1%)**, Peking University, *2023*
- **Merit Student (Top 10%)**, Peking University, *2023*
- **Second prize**, Chinese Mathematics Competitions for Undergraduates (**National Final, Top 0.2%**), *2023*
- **First prize**, Chinese Mathematics Competitions for Undergraduates (Beijing Division), *2022*
- **Merit Student (Top 10%)**, Peking University, *2022*
- **Award for Contribution in Student Organizations**, Peking University, *2021*

## 📖 Educations
- *2023.08 - 2023.12*, Visiting Student, University of California Berkeley
- *2021.06 - 2025.06 (expected)*, Undergraduate Student, School of Mathematical Sciences, Peking University
- *2020.09 - 2021.06*, Undergraduate Student, College of Engineering, Peking University
- *2017.09 - 2020.06*, Senior High School Student, Beijing No.4 High School

## 💼 Academic Service
- **Conference Reviewer**: NeurIPS (2023, 2024), ICLR (2024, 2025), ICML 2024, AISTATS (2024, 2025), ECCV 2024, AAAI 2025
- **Workshop Area Chair**: SeT-LLM (@ICLR 2024)
- **Workshop Reviewer**: XAIA (@NeurIPS 2023), ICL (@ICML 2024), IAI (@NeurIPS 2024)
- **Journal Reviewer**: TMLR
- **Ethics Reviewer**: NeurIPS 2023 Dataset & Benchmark Track, NeurIPS 2024
- **Fellow**, Berkeley AI Safety Initiative for Students (BASIS), UC Berkeley

## 🔗 Links
(Alphabetical Order)
- 👨‍🏫 **Advisors & Senior Co-authors**: [Stefanie Jegelka](https://people.csail.mit.edu/stefje/) (MIT), [Jun Sun](https://sunjun.site/) (SMU), [Meng Sun](https://www.math.pku.edu.cn/teachers/sunm/indexen.html), [David Wagner](https://people.eecs.berkeley.edu/~daw/) (UCB) , [Yisen Wang](https://yisenwang.github.io)
- 🧑‍🎓 **Co-authors**: [Huanran Chen](https://huanranchen.github.io), [Julien Piet](https://people.eecs.berkeley.edu/~julien.piet/) (UCB), [Chawin Sitawarin](https://chawins.github.io/) (Meta), [Yifei Wang](https://yifeiwang77.com) (MIT), [Xiyue Zhang](https://zhang-xiyue.github.io/) (Oxford), [Yihao Zhang](https://zhang-yihao.github.io/)
