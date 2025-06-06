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

I'm Zeming Wei (<font face=STKaiti>魏泽明</font>), an undergraduate at School of Mathematical Sciences, Peking University. I was also a visiting student at UC Berkeley in Fall, 2023. My research focuses on the trustworthiness of AI, specifically focusing on mechanism interpretability, adversarial robustness, and generative safety.  

If you are interested in collaborating (or just chatting) with me, feel free to email me.

## 🔥 News
- *2025.06*: &nbsp;🌟 3 new preprints exploring fresh paradigms in LLM safe alignment are available online, including safety [modeling](https://arxiv.org/pdf/2506.01770), [retrieval](https://arxiv.org/pdf/2505.15753), and [fine-tuning](https://arxiv.org/pdf/2505.16737).
- *2025.05*: &nbsp;🎉 1 Paper (as first author) accepted by **ICML 2025**.
- *2025.04*: &nbsp;🌟 Our new [preprint](https://openreview.net/pdf?id=xQI7dOlpmj) on discussing **Risks in LLM-based Agents** is available online.
- *2025.03*: &nbsp;🎖 I'm selected for the **Somersault Cloud Talent Program** (**筋斗云人才计划**) by ByteDance (internship track).
- *2024.12*: &nbsp;🎉 2 Papers (as corresponding author; 1 as **Oral**) accepted by **ICASSP 2025**.
- *2024.12*: &nbsp;🏅 I received the **Academic Rising Star Award (Top 5 undergraduates university-wide, [blog](https://mp.weixin.qq.com/s/NBrVYpFV5EyVCd0BaGRMyA))** by School of Computer Science, Peking University. 
- *2024.11*: &nbsp;🏅 I received the **May 4th Scholarship (<font color="#94070A">五四奖学金</font>, [blog](https://mp.weixin.qq.com/s/wmguSvRKHZkeFbszSwM1gw))**, which is **the highest honor scholarship** of Peking University (only 1 undergraduate awardee in School of Mathematical Sciences, **Top 0.1%**).
- *2024.10*: &nbsp;✨ My research grant (as **Principal Investigator**) is approved by **Beijing Natural Science Foundation**.
- *2024.09*: &nbsp;🎉 3 Papers accepted by **NeurIPS 2024**.
- *2024.07*: &nbsp;🎡 I attended **ICML 2024** at Vienna and illustrated our poster.
- *2024.05*: &nbsp;🎉 1 Paper (as corresponding author) accepted by **ICML 2024**.
- *2023.12*: &nbsp;💯 I achieved a **full GPA (4.0/4.0)** during my study at UC Berkeley (with 1 **A** and 2 **A+** grades).
- *2023.10*: &nbsp;🔗 I serve as a fellow of Berkeley AI Safety Initiative for Students (BASIS).
- *2023.09*: &nbsp;🏅 I received the **Exceptional Award for Academic Innovation** of Peking University (only 1 undergraduate awardee in School of Mathematical Sciences, **Top 0.1%**).
- *2023.08*: &nbsp;🎉 1 Paper (as first author) accepted by **Journal of Logical and Algebraic Methods in Programming**.
- *2023.06*: &nbsp;🍁 I attended **CVPR 2023** at Vancouver and illustrated our poster.
- *2023.05*: &nbsp;🥈 Won **Second prize** in Chinese Mathematics Competitions for Undergraduates **(National final, Top 0.2%)**.
- *2023.02*: &nbsp;🎉 1 Paper (as first author) accepted by **CVPR 2023**.
- *2022.12*: &nbsp;🥇 Won **First prize** in Chinese Mathematics Competitions for Undergraduates (Beijing Division), and qualified for the finals.

## 📝 Selected Preprints
### (${}^{\boldsymbol\dagger}$: Corresponding Author; \*: Equal Contribution)

- **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations**\\
**<u>Zeming Wei</u>**, Yifei Wang, Ang Li, Yichuan Mo, Yisen Wang\\
**_Preprint_ (Cited 200+ times)**\\
[[pdf](https://arxiv.org/pdf/2310.06387)]

- **Position: Agent-Specific Trustworthiness Risk as a Research Priority**\\
**<u>Zeming Wei</u>**, Tianlin Li, Xiaojun Jia, Yang Liu, Meng Sun\\
**_Preprint_**\\
[[pdf](https://openreview.net/pdf?id=xQI7dOlpmj)]

- **ReGA: Representation-Guided Abstraction for Model-based Safeguarding of LLMs**\\
**<u>Zeming Wei</u>**, Chengcan Wu, Meng Sun\\
**_Preprint_**\\
[[pdf](https://arxiv.org/pdf/2506.01770)]

- **Scalable Defense against In-the-wild Jailbreaking Attacks with Safety Context Retrieval**\\
Taiye Chen\*, **<u>Zeming Wei*</u>**, Ang Li, Yisen Wang\\
**_Preprint_**\\
[[pdf](https://arxiv.org/pdf/2505.15753)]


- **Mitigating Fine-tuning Risks in LLMs via Safety-Aware Probing Optimization**\\
Chengcan Wu\*, Zhixin Zhang\*, **<u>Zeming Wei*</u>**, Yihao Zhang, Meng Sun\\
**_Preprint_**\\
[[pdf](https://arxiv.org/pdf/2505.16737)]



## 📝 Selected Publications
### (${}^{\boldsymbol\dagger}$: Corresponding Author; \*: Equal Contribution)

- **Identifying and Understanding Cross-Class Features in Adversarial Training**\\
**<u>Zeming Wei</u>**, Yiwen Guo, Yisen Wang\\
**_ICML 2025_**\\
[[pdf](https://openreview.net/pdf?id=FvBYG5jA7k)] [[arxiv](https://arxiv.org/abs/2506.05032)] [[code](https://github.com/PKU-ML/Cross-Class-Features-AT)]

- **Boosting Jailbreak Attack with Momentum**\\
Yihao Zhang\*, **<u>Zeming Wei*${}^{\boldsymbol\dagger}$</u>**\\
**_ICASSP_ 2025 (Oral)**\\
[[pdf](https://ieeexplore.ieee.org/document/10888812)] [[arxiv](https://arxiv.org/abs/2405.01229)] [[code](https://github.com/weizeming/momentum-attack-llm)]

- **On the Duality Between Sharpness-Aware Minimization and Adversarial Training**\\
Yihao Zhang\*, Hangzhou He\*, Jingyu Zhu\*, Huanran Chen, Yifei Wang, **<u>Zeming Wei${}^{\boldsymbol\dagger}$</u>**\\
**_ICML 2024_**\\
[[pdf](https://arxiv.org/pdf/2402.15152.pdf)] [[arxiv](https://arxiv.org/abs/2402.15152)] [[code](https://github.com/weizeming/SAM_AT)]  

- **Weighted Automata Extraction and Explanation of Recurrent Neural Networks for Natural Language Tasks**\\
**<u>Zeming Wei</u>**, Xiyue Zhang, Yihao Zhang, Meng Sun\\
**_Journal of Logical and Algebraic Methods in Programming_**\\
[[pdf](https://linkinghub.elsevier.com/retrieve/pii/S2352220823000615)] [[arxiv](https://arxiv.org/abs/2306.14040)] [[code](https://github.com/weizeming/Extract_WFA_from_RNN_for_NL)]  

- **CFA: Class-wise Calibrated Fair Adversarial Training**\\
**<u>Zeming Wei</u>**, Yifei Wang, Yiwen Guo, Yisen Wang\\
**_CVPR 2023_**\\
[[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_CFA_Class-Wise_Calibrated_Fair_Adversarial_Training_CVPR_2023_paper.pdf)] [[arxiv](https://arxiv.org/abs/2303.14460)] [[code](https://github.com/PKU-ML/CFA)]  

## 💻 Projects
- **Adversarial Safety Testing and Defense of AI Foundation Models**\\
**Principal Investigator**, Beijing Natural Science Foundation (Grant No. QY24035)\\
*2024.10 - 2026.09*


## 🎖️ Talent Programs
- **Somersault Cloud Talent Program** (**筋斗云人才计划**), internship track, ByteDance
- **Elite Ph.D. Program in Mathematics**, Peking University
- **Elite Ph.D. Program in Applied Mathematics**, Center for Machine Learning Research, Peking University


## 🏅 Honors and Awards
- **Excellent Graduate of Beijing Municipal (Top 5%)**, Beijing Municipal Education Commission, *2025*
- **Excellent Graduate of Peking University**, Peking University, *2025*
- **May 4th Scholarship** (<b><font color="#94070A">五四奖学金</font></b>, **Top 0.1%**) [[blog](https://mp.weixin.qq.com/s/wmguSvRKHZkeFbszSwM1gw)], **the highest honor scholarship** of Peking University, *2024*
- **Academic Rising Star Award (Top 5 undergraduates university-wide)** [[blog](https://mp.weixin.qq.com/s/NBrVYpFV5EyVCd0BaGRMyA)], School of Computer Science, Peking University, *2024*
- **Merit Student (Top 10%)**, Peking University, *2024*
- **Spotlight Award (Best Paper)**, 1st ICML Workshop on In-Context Learning, *2024*
- **ICML Travel Award**, *2024*
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
- **Reviewer (Conference)**: NeurIPS, ICLR, ICML, AISTATS, ECCV, CVPR, AAAI
- **Reviewer (Journal)**: TIFS, TMLR
- **Reviewer (Workshop)**: XAIA (@NeurIPS 2023), ICL (@ICML 2024), IAI (@NeurIPS 2024)
- **Fellow**, Berkeley AI Safety Initiative for Students (BASIS), UC Berkeley

## 🔗 Links
(Alphabetical Order)
- 👨‍🏫 **Advisors & Senior Co-authors**: [Stefanie Jegelka](https://people.csail.mit.edu/stefje/) (MIT), [Yang Liu](https://personal.ntu.edu.sg/yangliu/) (NTU), [Jun Sun](https://sunjun.site/), [Meng Sun](https://www.math.pku.edu.cn/teachers/sunm/indexen.html), [David Wagner](https://people.eecs.berkeley.edu/~daw/) (UCB), [Yifei Wang](https://yifeiwang77.com) (MIT), [Yisen Wang](https://yisenwang.github.io/), [Xiyue Zhang](https://zhang-xiyue.github.io/)
- 🧑‍🎓 **Co-authors**: [Huanran Chen](https://huanranchen.github.io), [Hangzhou He](https://riverback.github.io/), [Yichuan Mo](https://scholar.google.com/citations?user=xvSYG1gAAAAJ&hl=en), [Julien Piet](https://people.eecs.berkeley.edu/~julien.piet/) (UCB), [Chawin Sitawarin](https://chawins.github.io/) (Google), [Yihao Zhang](https://zhang-yihao.github.io/), [Jingyu Zhu](https://scholar.google.com/citations?user=BA0BaS4AAAAJ&hl=en)
