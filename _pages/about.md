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

I am a fourth-year PhD Candidate in DEEP Lab at the Department of Computing, The Hong Kong Polytechnic University, supervised by [Prof. Xiao HUANG](https://www4.comp.polyu.edu.hk/~xiaohuang/index.html) and co-supervised by [Prof. Jiannong CAO](https://www4.comp.polyu.edu.hk/~csjcao/). Prior to that, I obtained my B.E. from [The Northwestern Polytechnical University](https://www.nwpu.edu.cn/).

My research interests include **Knowledge Graphs, Retrieval-Augmented Generation,** and **Large Language Models**, with the latest research presented at NeurIPS, ICML, KDD, ACL, etc.. Currently, I am working on **GraphRAG and Long CoT Reasoning** for specialized domains.

# 🎉 News
- [*2025.08*] Our paper [FaithfulRAG](https://arxiv.org/abs/2506.08938) has been selected for the **SAC Highlights Award** at [ACL'25](https://2025.aclweb.org/program/awards/#sac-highlights).
- [*2025.06*] We released GraphRAG-Bench to evaluate GraphRAG models. [[Paper](https://arxiv.org/abs/2506.05690)\|[Code](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)\|[Slides](https://docs.google.com/presentation/d/1q8K2RgsDYktkEIDp9Lqpb9WwBCBHT_L5/edit?slide=id.p1#slide=id.p1)] [![](https://img.shields.io/github/stars/GraphRAG-Bench/GraphRAG-Benchmark)](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)
- [*2025.05*] I passed the Ph.D. oral defense! Huge thanks to my supervisor and committee members!
- [*2025.05*] Our work FaithfulRAG is accepted to ACL'25. [[Paper](https://arxiv.org/abs/2506.08938)\|[Code](https://github.com/XMUDeepLIT/Faithful-RAG)] [![](https://img.shields.io/github/stars/XMUDeepLIT/Faithful-RAG)](https://github.com/XMUDeepLIT/Faithful-RAG)
- [*2025.05*] Our work SGU-SQL is accepted to ICML'25. [[Paper](https://arxiv.org/abs/2402.13284)\|[Code](https://github.com/Qing145/Text-to-SQL)] 
- [*2025.04*] We released NPPC, an ever-scaling reasoning benchmark for LLMs. [[Paper](https://arxiv.org/abs/2504.11239)\|[Code](https://github.com/SMU-DIGA/nppc)]
- [*2025.01*] Our survey on GraphRAG is released! [[Paper](https://arxiv.org/abs/2501.13958)\|[Github awesome-list](https://github.com/DEEP-PolyU/Awesome-GraphRAG)] [![](https://img.shields.io/github/stars/DEEP-PolyU/Awesome-GraphRAG)](https://github.com/DEEP-PolyU/Awesome-GraphRAG)
- [*2024.09*] Three papers are accepted to NeurIPS'24 and one paper is accepted to KDD'24.

# 📔 Selected Publications 
**[†]**: Co-first Author, **[‡]**: Corresponding Author

- [arXiv 2025] **Qinggang Zhang†**, Shengyuan Chen†, Yuanchen Bei†, Zheng Yuan, Huachi Zhou, Zijin Hong, Junnan Dong, Jinsong Su, Hao Chen, Yi Chang, Xiao Huang‡. A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models.
- **[ICML 2025]** **Qinggang Zhang**, Hao Chen, Junnan Dong, Shengyuan Chen‡, Feiran Huang, Xiao Huang. Structure-Guided Large Language Models for Text-to-SQL Generation.
- **[ACL 2025]** **Qinggang Zhang†**, Zhishang Xiang†, Yilin Xiao, Le Wang, Junhui Li, Xinrun Wang, Jinsong Su‡.
FaithfulRAG: Fact-Level Conflict Modeling for Context-Faithful Retrieval-Augmented Generation.
- **[KDD 2024]** **Qinggang Zhang**, Keyu Duan, Junnan Dong, Pai Zheng, Xiao Huang†. Logical Reasoning with Relation Network for Inductive Knowledge Graph Completion.
- **[NeurIPS 2024]** **Qinggang Zhang†**, Junnan Dong†, Hao Chen, Daochen Zha, Zailiang Yu, Xiao Huang‡. KnowGPT: Knowledge Graph based Prompting for Large Language Models.
- **[TKDE 2023]** **Qinggang Zhang**, Junnan Dong, Qiaoyu Tan, Xiao Huang‡. Integrating Entity Attributes for Error-Aware Knowledge Graph Embedding.
-**[CIKM 2022]** **Qinggang Zhang**, Junnan Dong, Keyu Duan, Xiao Huang‡, Yezi Liu, Linchuan Xu. Contrastive Knowledge Graph Error Detection.
- [ACL 2024] Junnan Dong†, **Qinggang Zhang†**, Huachi Zhou, Daochen Zha, Pai Zheng, Xiao Huang‡. Modality-Aware Integration with LLMs for Knowledge-based Visual Question Answering. 
- **[WWW 2023]** Junnan Dong†, **Qinggang Zhang†**, Xiao Huang‡, Keyu Duan, Qiaoyu Tan, Zhimeng Jiang. Hierarchy-Aware Multi-Hop Question Answering over Knowledge Graphs.
- [arXiv 2025] Luyao Zhuang, **Qinggang Zhang‡**, Huachi Zhou, Juhua Liu, Li Qing, Xiao Huang. LoSemB: Logic-Guided Semantic Bridging for Inductive Tool Retrieval.
- [arXiv 2025] Shengyuan Chen, Zheng Yuan, **Qinggang Zhang‡**, Wen Hua, Xiao Huang. Neuro-Symbolic Entity Alignment via Variational Inference.
- [arXiv 2025] Zhishang Xiang, Chuanjie Wu, **Qinggang Zhang‡**, Shengyuan Chen, Zijin Hong, Xiao Huang, Jinsong Su#, When to use Graphs in RAG: A Comprehensive Analysis for Graph Retrieval-Augmented Generation.
- [arXiv 2025] Yilin Xiao, Chuang Zhou, **Qinggang Zhang‡**, Su Dong, Shengyuan Chen, Xiao Huang. LAG: Logic-Augmented Generation from a Cartesian Perspective.
- [arXiv 2025] Shengyuan Chen†, Chuang Zhou†, Zheng Yuan, **Qinggang Zhang‡**, Zeyang Cui, Hao Chen, Yilin Xiao, Jiannong Cao, Xiao Huang. You Don't Need Pre-built Graphs for RAG: Retrieval Augmented Generation with Adaptive Reasoning Structures.


# 💼 Academic Service

- **Program Committee:** NeurIPS (2024-2025), ICLR (2025), ICML (2025), KDD (2024-2026), ACL (2025)

- **Reviewer:** TPAMI (2024-2025), TKDE (2023-2025)
  
- **Volunteer:** ICDM'23, WSDM'23, KDD'24

<!-- - **Teaching Assistant:** Big Data Analytics (2023 Spring/ 2022 Spring); Object-oriented Programming (2022 Fall); Discrete Mathematics (2021 Fall); Human Computer Interaction (2021 Spring); Computer Networking (2020 Spring); Information Systems (2019 Fall) -->

# 🏆 Honors and Awards
- [*2025*] SAC Highlights Award at ACL2025
- [*2024*] KDD Student Travel Grant
- [*2024*] Best Presentation Award of COMP 50th Anniversary Research Student Conference
- [*2022*] SIGIR Student Travel Grant
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

