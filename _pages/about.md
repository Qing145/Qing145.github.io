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

I am a Postdoctoral Fellow at the Hong Kong Polytechnic University. I earned my Ph.D. from the same institution under the supervision of [Prof. Xiao HUANG](https://www4.comp.polyu.edu.hk/~xiaohuang/index.html) with co-supervision by [Prof. Jiannong CAO](https://www4.comp.polyu.edu.hk/~csjcao/). Before that, I obtained my B.E. from Northwestern Polytechnical University.

My research interests include Knowledge Graph (KG), Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG). Currently, I focus on GraphRAG and Long-CoT Reasoning for specialized domains, with the latest research presented at NeurIPS, ICML, KDD, ACL, etc.

# 🎉 News
- [*2025.09*] Our survey on [LLM-based Text-to-SQL](https://arxiv.org/abs/2406.08426) is accepted by IEEE TKDE.
- [*2025.08*] Our works [FILM](https://dl.acm.org/doi/10.1145/3763789) and [RAWM](https://openreview.net/pdf?id=m7GgZ9S8nx) are accepted by ACM TOIS and EMNLP'25, respectively.
- [*2025.08*] Our paper FaithfulRAG has been selected for the **SAC Highlights Award** at [ACL'25](https://2025.aclweb.org/program/awards/#sac-highlights).
- [*2025.08*] We released Mol-R1, a long-CoT reasoning model for molecule discovery. [[Paper](https://arxiv.org/abs/2508.08401)\|[Huggingface](https://huggingface.co/papers/2508.08401)]
- [*2025.06*] We released GraphRAG-Bench for Graph-based RAG evaluation. [[Paper](https://arxiv.org/abs/2506.05690)\|[Github](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)\|[Slides](https://docs.google.com/presentation/d/1q8K2RgsDYktkEIDp9Lqpb9WwBCBHT_L5/edit?slide=id.p1#slide=id.p1)] [![](https://img.shields.io/github/stars/GraphRAG-Bench/GraphRAG-Benchmark)](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)
- [*2025.05*] I passed the Ph.D. oral defense! Huge thanks to my supervisor and committee members!
- [*2025.05*] Our work, FaithfulRAG, is accepted to ACL'25. [[Paper](https://arxiv.org/abs/2506.08938)\|[Github](https://github.com/XMUDeepLIT/Faithful-RAG)] [![](https://img.shields.io/github/stars/XMUDeepLIT/Faithful-RAG)](https://github.com/XMUDeepLIT/Faithful-RAG)
- [*2025.05*] Our work SGU-SQL is accepted to ICML'25. [[Paper](https://arxiv.org/abs/2402.13284)\|[Github](https://github.com/Qing145/Text-to-SQL)] 
- [*2025.04*] We released NPPC, an ever-scaling reasoning benchmark for LLMs. [[Paper](https://arxiv.org/abs/2504.11239)\|[Github](https://github.com/SMU-DIGA/nppc)]
- [*2025.01*] Our survey on GraphRAG is released! [[Paper](https://arxiv.org/abs/2501.13958)\|[Github awesome-list](https://github.com/DEEP-PolyU/Awesome-GraphRAG)] [![](https://img.shields.io/github/stars/DEEP-PolyU/Awesome-GraphRAG)](https://github.com/DEEP-PolyU/Awesome-GraphRAG)
- [*2024.09*] Three papers are accepted to NeurIPS'24 and one paper is accepted to KDD'24.

# 📔 Selected Publications ([Full List](https://scholar.google.com/citations?user=eF8PATI7r3IC&hl=en))
<span style="color: #a39274">**[†]: Co-first Author**</span>, <span style="color: #7A9D96">**[‡]: Corresponding Author**</span>

## Preprint:
- **[arXiv 2025]** **Qinggang Zhang†**, Shengyuan Chen†, Yuanchen Bei†, Zheng Yuan, Huachi Zhou, Zijin Hong, Yilin Xiao, Chuang Zhou, Hao Chen, Yi Chang, Xiao Huang‡. [A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models](https://arxiv.org/abs/2501.13958).
- **[arXiv 2025]** Luyao Zhuang, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Huachi Zhou, Juhua Liu, Li Qing, Xiao Huang. [LoSemB: Logic-Guided Semantic Bridging for Inductive Tool Retrieval](https://arxiv.org/abs/2508.07690).
- **[arXiv 2025]** Shengyuan Chen, Zheng Yuan, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Wen Hua, Xiao Huang. [Neuro-Symbolic Entity Alignment via Variational Inference](https://arxiv.org/abs/2410.04153).
- **[arXiv 2025]** Zhishang Xiang†, Chuanjie Wu†, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Shengyuan Chen, Zijin Hong, Xiao Huang, Jinsong Su‡. [When to use Graphs in RAG: A Comprehensive Analysis for Graph Retrieval-Augmented Generation](https://arxiv.org/abs/2506.05690).
- **[arXiv 2025]** Yilin Xiao, Chuang Zhou, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Su Dong, Shengyuan Chen, Xiao Huang. [LAG: Logic-Augmented Generation from a Cartesian Perspective](https://arxiv.org/abs/2508.05509).
- **[arXiv 2025]** Yilin Xiao, Chuang Zhou, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Bo Li, Qing Li, Xiao Huang. [Reliable Reasoning Path: Distilling Effective Guidance for LLM Reasoning with Knowledge Graphs](https://arxiv.org/abs/2506.10508).
- **[arXiv 2025]** Shengyuan Chen, Chuang Zhou, Zheng Yuan, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Zeyang Cui, Hao Chen, Yilin Xiao, Jiannong Cao, Xiao Huang. [You Don't Need Pre-built Graphs for RAG: Retrieval Augmented Generation with Adaptive Reasoning Structures](https://arxiv.org/abs/2508.06105).
- **[arXiv 2025]** Jiatong LI†, Weida Wang†, <span style="color: #a39274">**Qinggang Zhang†**</span>, Changmeng Zheng, Junxian Li, Di Zhang, Shufei Zhang, Xiaoyong Wei, Li Qing‡. [Mol-R1: Towards Explicit Long-CoT Reasoning in Molecule Discovery](https://arxiv.org/abs/2508.08401). 

## Published:
- **[IEEE TKDE]** Zijin Hong, Zheng Yuan, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Hao Chen, Junnan Dong, Feiran Huang, Xiao Huang. [Next-Generation Database Interfaces: A Survey of LLM-based Text-to-SQL](https://arxiv.org/abs/2406.08426).
- **[ACM TOIS]** Huachi Zhou, Kaijing Yu, <span style="color: #7A9D96">**Qinggang Zhang‡**</span>, Hao Chen, Daochen Zha, Anthony Kong, Wenqi Pei, Xiao Huang. [Self-Monitoring Large Language Models for Click-Through Rate Prediction](https://dl.acm.org/doi/10.1145/3763789).
- **[ICML'25]** **Qinggang Zhang**, Hao Chen, Junnan Dong, Shengyuan Chen‡, Feiran Huang, Xiao Huang. [Structure-Guided Large Language Models for Text-to-SQL Generation](https://arxiv.org/abs/2402.13284).
- **[ACL'25]** **Qinggang Zhang†**, Zhishang Xiang†, Yilin Xiao, Le Wang, Junhui Li, Xinrun Wang, Jinsong Su‡. [FaithfulRAG: Fact-Level Conflict Modeling for Context-Faithful Retrieval-Augmented Generation](https://arxiv.org/abs/2506.08938).
- **[KDD'24]** **Qinggang Zhang**, Keyu Duan, Junnan Dong, Pai Zheng, Xiao Huang†. [Logical Reasoning with Relation Network for Inductive Knowledge Graph Completion](https://dl.acm.org/doi/abs/10.1145/3637528.3671911).
- **[NeurIPS'24]** **Qinggang Zhang†**, Junnan Dong†, Hao Chen, Daochen Zha, Zailiang Yu, Xiao Huang‡. [KnowGPT: Knowledge Graph based Prompting for Large Language Models](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0b8705a611ed1ce19cdb759031078705-Abstract-Conference.html).
- **[IEEE TKDE]** **Qinggang Zhang**, Junnan Dong, Qiaoyu Tan, Xiao Huang‡. [Integrating Entity Attributes for Error-Aware Knowledge Graph Embedding](https://ieeexplore.ieee.org/abstract/document/10239484).
- **[ACL'24]** Junnan Dong†, <span style="color: #a39274">**Qinggang Zhang†**</span>, Huachi Zhou, Daochen Zha, Pai Zheng, Xiao Huang‡. [Modality-Aware Integration with LLMs for Knowledge-based Visual Question Answering](https://arxiv.org/abs/2402.12728). 
- **[WWW'23]** Junnan Dong†, <span style="color: #a39274">**Qinggang Zhang†**</span>, Xiao Huang‡, Keyu Duan, Qiaoyu Tan, Zhimeng Jiang. [Hierarchy-Aware Multi-Hop Question Answering over Knowledge Graphs](https://dl.acm.org/doi/abs/10.1145/3543507.3583376).
- **[CIKM'22]** **Qinggang Zhang**, Junnan Dong, Keyu Duan, Xiao Huang‡, Yezi Liu, Linchuan Xu. [Contrastive Knowledge Graph Error Detection](https://dl.acm.org/doi/abs/10.1145/3511808.3557264).



# 🏆 Honors and Awards
- [*2025*] SAC Highlights Award at ACL'25
- [*2024*] KDD Student Travel Grant in 2024
- [*2024*] Best Presentation Award of COMP 50th Anniversary Research Student Conference
- [*2022*] SIGIR Student Travel Grant in 2022
- [*2021*] Vector Scholarship in Artificial Intelligence
- [*2019*] Outstanding graduate award (undergraduate in NPU)
- [*2015-2018*] National scholarships ~ Twice
- [*2017*] Champion in 2017 China Robot Competition
- [*2017*] Champion in the 2017 international Underwater Robot competition
- [*2017*] Honorable Mention in the 2017 Interdisciplinary Contest in Modeling
- [*2016*] The CCF Outstanding Undergraduate Award
- [*2016*] Champion in “WRC2016” international Underwater Robot competition
- [*2016*] Champion at 21th FIRA RoboWorld Cup 2016, Beijing, China
- [*2016*] Champion in 2016 China Robot Competition

# 💼 Academic Service

- **Program Committee:** NeurIPS (2024-2025), ICLR (2025), ICML (2025), KDD (2024-2026), ACL (2025)

- **Reviewer:** TPAMI (2024-2025), TKDE (2023-2025)
  
- **Volunteer:** ICDM (2023), WSDM (2023), KDD (2024)

<!-- - **Teaching Assistant:** Big Data Analytics (2023 Spring/ 2022 Spring); Object-oriented Programming (2022 Fall); Discrete Mathematics (2021 Fall); Human Computer Interaction (2021 Spring); Computer Networking (2020 Spring); Information Systems (2019 Fall) -->

