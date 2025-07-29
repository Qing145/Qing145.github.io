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

# 🎓 About Me

I am a Postdoc with [Prof. Jiannong CAO](https://www4.comp.polyu.edu.hk/~csjcao/) (since 2024) at the Department of Computing, Hong Kong Polytechnic University. I earned my Ph.D. from the same department under the supervision of [Prof. Xiao HUANG](https://www4.comp.polyu.edu.hk/~xiaohuang/index.html) (2021–2024). Prior to that, I obtained my B.E. from [Fudan University](https://www.fudan.edu.cn/).

My research interests include **graph learning, reasoning**, and **Large Language Models**, with latest research presented at NeurIPS, ICML, TKDE, ACL, CIKM, etc.. Currently, I am working on **Graph-based Retrieval-Augmented Generation for LLMs (graphRAG).** 

# 🎉 News
- [*2025.07*] 🔥🔥🔥 Our NeurIPS'24 paper [LLM4EA](https://openreview.net/forum?id=qfCQ54ZTX1) ranks **#1st** in Google Scholar search results for "entity alignment" papers in the past two years (2024-2025)!
- [*2025.06*] Released a GraphRAG benchmark: [[Homepage](https://graphrag-bench.github.io/)\|[Paper](https://arxiv.org/abs/2506.05690)\|[Code](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)\|[Slides](https://docs.google.com/presentation/d/1q8K2RgsDYktkEIDp9Lqpb9WwBCBHT_L5/edit?slide=id.p1#slide=id.p1)] [![](https://img.shields.io/github/stars/GraphRAG-Bench/GraphRAG-Benchmark)](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)
- [*2025.05*] Our work [SKETCH](https://openreview.net/forum?id=WlEJovnbXc) is accepted to ACL (main track).
- [*2025.05*] Our work SGU-SQL is accepted to ICML. [[Paper](https://openreview.net/forum?id=gT8JSEFqaS)\|[Code](https://github.com/Qing145/Text-to-SQL)] 
- [*2025.01*] Our survey on graphRAG is released! [[Paper](https://arxiv.org/abs/2501.13958)\|[Github awesome-list](https://github.com/DEEP-PolyU/Awesome-GraphRAG)] [![](https://img.shields.io/github/stars/DEEP-PolyU/Awesome-GraphRAG)](https://github.com/DEEP-PolyU/Awesome-GraphRAG)
- [*2024.12*] One paper accepted to TKDE.
- [*2024.09*] Our work LLM4EA is accepted to NeurIPS. [[Paper](https://openreview.net/forum?id=qfCQ54ZTX1)\|[Code](https://github.com/chensyCN/llm4ea_official)] 
- [*2023.09*] Our work [DiffLogic](https://openreview.net/forum?id=bETvUctiTR) is accepted to NeurIPS.

# 📔 Selected Publications 
<span style="color: #006400">**[Green]**</span>: Corresponding Author, <span style="color: #000080">**[Blue]**</span>: Co-first Author
- Zhishang Xiang, Chuanjie Wu, Qinggang Zhang, **Shengyuan Chen**, Zijin Hong, Xiao Huang, Jinsong Su, [When to use Graphs in RAG: A Comprehensive Analysis for Graph Retrieval-Augmented Generation](https://arxiv.org/abs/2506.05690), preprint, 2025.
- Chuang Zhou, Zhu Wang, <span style="color: #006400">**Shengyuan Chen**</span>, Jiahe Du, Qiyuan Zheng, Zhaozhuo Xu, Xiao Huang, [Taming Language Models for Text-attributed Graph Learning with Decoupled Aggregation](https://openreview.net/forum?id=WlEJovnbXc), ACL (main track), 2025.
- Qinggang Zhang, Hao Chen, Junnan Dong,  <span style="color: #006400">**Shengyuan Chen**</span>, Feiran Huang, Xiao Huang, [Structure-Guided Large Language Models for Text-to-SQL Generation](https://openreview.net/forum?id=gT8JSEFqaS), ICML, 2025.
- Qinggang Zhang, <span style="color: #000080">**Shengyuan Chen**</span>, Yuanchen Bei, Zheng Yuan, Huachi Zhou, Zijin Hong, Junnan Dong, Hao Chen, Yi Chang, Xiao Huang, [A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models](https://arxiv.org/abs/2501.13958), preprint, 2025
- Hao Chen, Yuanchen Bei, Wenbing Huang, **Shengyuan Chen**, Feiran Huang, Xiao Huang, [Graph Cross-Correlated Network for Recommendation](https://ieeexplore.ieee.org/document/10759834), TKDE, 2024
- **Shengyuan Chen**, Qinggang Zhang, Junnan Dong, Wen Hua, Qing Li, Xiao Huang, [Entity Alignment with Noisy Annotations from Large Language Models](https://openreview.net/forum?id=qfCQ54ZTX1), NeurIPS, 2024
- **Shengyuan Chen**, Yunfeng Cai, Huang Fang, Xiao Huang, Mingming Sun, [Differentiable Neuro-Symbolic Reasoning on Large-Scale Knowledge Graphs](https://openreview.net/forum?id=bETvUctiTR), NeurIPS, 2023
- Yuanchen Bei, Hao Chen, **Shengyuan Chen**, Xiao Huang, Sheng Zhou, Feiran Huang, [Non-Recursive Cluster-Scale Graph Interacted Model for Click-Through Rate Prediction](https://dl.acm.org/doi/10.1145/3583780.3615180), CIKM, 2023
- Zirui Liu, **Shengyuan Chen**, Kaixiong Zhou, Daochen Zha, Xiao Huang, Xia Hu, [RSC: Accelerating Graph Neural Networks Training via Randomized Sparse Computation](https://openreview.net/forum?id=GnsqiJwDzN), ICML, 2023

# 💼 Academic Service

- **Program Committee:** NeurIPS (2024-2025); ICML (2025); AISTATS (2025); ICLR (2025); AAAI (2026)

- **Reviewer:** TNNLS (2024-2025); TKDD

<!-- - **Teaching Assistant:** Big Data Analytics (2023 Spring/ 2022 Spring); Object-oriented Programming (2022 Fall); Discrete Mathematics (2021 Fall); Human Computer Interaction (2021 Spring); Computer Networking (2020 Spring); Information Systems (2019 Fall) -->

# 🏆 Honors and Awards
- [*2025*] Postdoc Matching Fund ~ Two Years
- [*2023*] Departmental Top Conference Grant
- [*2022*] Winner of "Most Appreciated Teaching Assistant" (~$30,000HKD)
- [*2018*] Shanghai 'TI Cup' Undergraduate Electronic Design Contest ~ Second Price
- [*2015-2018*] Fudan University Scholarship for Outstanding Students ~ Three Times
- [*2018*] SCSK Corporation Scholarship
- [*2015-2017*] National Scholarship of Encouragement and Support ~ Twice

# 🎨 Miscellaneous

In my leisure time, I am passionate about cooking, fishing, photography, and sports including hiking and jogging. I proudly completed a half marathon in 2019!