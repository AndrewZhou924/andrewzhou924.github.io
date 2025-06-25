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

Hi there, I am (Andrew) Zhanke Zhou, a Ph.D. student at [TMLR group](https://bhanml.github.io/group.html) of Hong Kong Baptist University, advised by [Prof. Bo Han](https://bhanml.github.io/) and working with [Prof. Jiangchao Yao](https://sunarker.github.io/).
Currently, I am a visiting student at [STAIR lab](https://stair.cs.stanford.edu/team/) of Stanford University, working with [Prof. Sanmi Koyejo](https://cs.stanford.edu/~sanmi/).
Prior to that, I was a visiting student at [LARS group](https://lars-group.github.io/pages/group.html) of Tsinghua University, working with [Prof. Quanming Yao](https://lars-group.github.io/) and [Prof. Yongqi Zhang](https://yzhangee.github.io/).

My research focuses on **trustworthy machine reasoning with foundation models** (LLMs, VLMs) to solve **complex problems** such as mathematics and coding, as well as to accelerate scientific discovery and application in fields like biology, chemistry, and healthcare. I believe that **reasoning** is the essential pathway to achieving AGI. Trustworthy machine reasoning encompasses properties such as reasoning power, robustness, safety, and explainability. 
My work involves developing methodologies, benchmarks, and theoretical foundations to advance these areas:
- Developing advanced trustworthy reasoning systems (incorporating RL and tool learning) [[AR-Bench]](https://arxiv.org/pdf/2506.08295) [[Landscape of thoughts]](https://arxiv.org/pdf/2503.22165) [[ECON]](https://arxiv.org/pdf/2506.08292)
- Comprehensive evaluation and benchmarking of foundation model trustworthiness [[NoRa]](https://arxiv.org/pdf/2410.23856) [[DeepInception]](https://arxiv.org/pdf/2311.03191) [[G-effect]](https://arxiv.org/pdf/2502.19301) [[NTTA]](https://arxiv.org/pdf/2502.14604) [[EOE]](https://arxiv.org/pdf/2406.00806)
- Trustworthy machine learning and reasoning on (knowledge) graphs [[GRA]](https://arxiv.org/pdf/2306.09104) [[RGIB]](https://arxiv.org/pdf/2311.01196) [[Subgraph]](https://arxiv.org/pdf/2403.10231) [[Neural Atoms]](https://arxiv.org/pdf/2311.01276) [[AdaProp]](https://arxiv.org/pdf/2205.15319) [[KGTuner]](https://arxiv.org/pdf/2205.02460)

I am leading the reasoning team in TMLR group and fortunately working with several talented researchers. **We welcome potential collaborations in various forms, including visiting PhD students, research assistants, and undergraduate trainees.** *Please feel free to [email me](mailto:cszkzhou@comp.hkbu.edu.hk) and [Prof. Bo Han](mailto:bhanml@comp.hkbu.edu.hk) to discuss collaboration opportunities.*
We are also organizing the [TMLR Young Scientist Seminars](https://tmlr-group.github.io/seminars/TMLR_YSS.html) and actively seeking researchers interested in sharing their work. If you would like to give a talk, we encourage you to reach out to us.

E-mail: cszkzhou [at] comp.hkbu.edu.hk / zhanke [at] cs.stanford.edu 


# 📖 Educations
- *2022.09 - present*, Hong Kong Baptist University (HKBU), Ph.D. in Computer Science.
- *2017.09 – 2021.06*, Huazhong University of Science and Technology (HUST), B.E. in Electronics 
and Information Engineering (SeedClass).

<!-- # Research
TODO: a short summary of my research -->

# 📝 Selected Publications
\* Co-first author, ✉️ Corresponding author.

<!-- ICML 2025 AR-Bench -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/AR-Bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

From Passive to Active Reasoning: Can Large Language Models Ask the Right Questions under Incomplete Information?  
**Zhanke Zhou\***, Xiao Feng\*, Zhaocheng Zhu, Jiangchao Yao, Sanmi Koyejo, Bo Han✉️  
ICML 2025.
[[paper]](https://arxiv.org/pdf/2506.08295)
[[code]](https://github.com/tmlr-group/AR-Bench)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
<!-- [[CN-blog]]() -->
<!-- [[twitter]]() -->
</div>
</div>


<!-- ICML 2025 ECON -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/ECON.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

From Debate to Equilibrium: Belief-Driven Multi-Agent LLM Reasoning via Bayesian Nash Equilibrium.  
Yi Xie\*, **Zhanke Zhou\***, Chentao Cao, Qiyu Niu, Tongliang Liu, Bo Han✉️  
ICML 2025.
[[paper]](https://arxiv.org/pdf/2506.08292)
[[code]](https://github.com/tmlr-group/ECON)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
<!-- [[CN-blog]]() -->
<!-- [[twitter]]() -->
</div>
</div>

<!-- Landscape of thoughts -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/Landscape.png' alt="sym" width="100%"></div></div>
<!-- <img src='/_pages/data/poster-landscape.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models.  
**Zhanke Zhou\***, Zhaocheng Zhu\*, Xuan Li\*, Mikhail Galkin, Xiao Feng, Sanmi Koyejo, Jian Tang, Bo Han✉️  
ICLR 2025 Workshop on Reasoning and Planning for Large Language Models.
[[paper]](https://arxiv.org/pdf/2503.22165)
[[code]](https://github.com/tmlr-group/landscape-of-thoughts)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
<!-- [[CN-blog]]() -->
<!-- [[twitter]]() -->
</div>
</div>


<!-- ICLR 2025 - G-effect -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/G-effect.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Rethinking LLM Unlearning Objectives: A Gradient Perspective and Go Beyond.  
Qizhou Wang, Jin Peng Zhou, **Zhanke Zhou**, Saebyeol Shin, Bo Han✉️, Kilian Q. Weinberger  
ICLR 2025.
[[paper]](https://arxiv.org/pdf/2502.19301)
[[code]](https://github.com/tmlr-group/G-effect)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
[[CN-blog]](https://www.jiqizhixin.com/articles/2025-04-28-10)
<!-- [[twitter]]() -->
</div>
</div>

<!-- ICLR 2025 - NTTA -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/NTTA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Noisy Test-Time Adaptation in Vision-Language Models.  
Chentao Cao, Zhun Zhong, **Zhanke Zhou**, Tongliang Liu, Yang Liu, Kun Zhang, Bo Han✉️  
ICLR 2025.
[[paper]](https://arxiv.org/pdf/2502.14604)
[[code]](https://github.com/tmlr-group/ZS-NTTA)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
<!-- [[CN-blog]]() -->
<!-- [[twitter]]() -->
</div>
</div>

<!-- NeurIPS 2024 - NoRa -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <img src='/_pages/data/figures/NoRa.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/poster-NoRa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Can Language Models Perform Robust Reasoning in Chain-of-thought Prompting with Noisy Rationales?  
**Zhanke Zhou**, Rong Tao, Jianing Zhu, Yiwen Luo, Zengmao Wang, Bo Han✉️  
NeurIPS 2024.
[[paper]](https://arxiv.org/pdf/2410.23856)
[[code]](https://github.com/tmlr-group/NoisyRationales)
[[slides]](/_pages/data/slides-NoRa.pdf)
[[poster]](/_pages/data/poster-NoRa.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/#/share?share=95130&s=5b5533e4-0c3e-45a1-83a7-87a2fd7b4f54)
[[CN-video]](https://www.bilibili.com/video/BV1vaUNYTEr3/?t=4700)
[[CN-blog]](https://mp.weixin.qq.com/s/7igsb3yOW5UYd_Ox47Q0wA)
[[twitter]](https://x.com/tmlrgroup/status/1877546137395278231)
</div>
</div>


<!-- Cross-domain Finetuning -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/CoPA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Mind the Gap Between Prototypes and Images in Cross-domain Finetuning.  
Hongduan Tian, Feng Liu, **Zhanke Zhou**, Tongliang Liu, Chengqi Zhang, Bo Han✉️  
NeurIPS 2024.
[[paper]](https://arxiv.org/pdf/2410.12474)
[[code]](https://github.com/tmlr-group/CoPA)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
<!-- [[CN-blog]]() -->
<!-- [[twitter]]() -->
</div>
</div>


<!-- DeepInception -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <img src='/_pages/data/figures/DeepInception.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/figures/DeepInception.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DeepInception: Hypnotize Large Language Model to Be Jailbreaker.  
Xuan Li\*, **Zhanke Zhou\***, Jianing Zhu\*, Jiangchao Yao, Tongliang Liu, Bo Han✉️  
NeurIPS 2024 SafeGenAI Workshop.
[[paper]](https://arxiv.org/pdf/2311.03191.pdf)
[[code]](https://github.com/tmlr-group/DeepInception)
<!-- [[website]](https://deepinception.github.io/) -->
[[slides]](./_pages/data/slides-DeepInception.pdf)
[[twitter]](https://twitter.com/Jianing9810/status/1721894260231098812)
[[CN-video]](https://www.bilibili.com/video/BV16N4y1i7Rw/?t=2477)
[[CN-blog]](https://mp.weixin.qq.com/s/PufSBheCrJsjzkC4LD20Nw)
[[DeepTech]](https://mp.weixin.qq.com/s/kN_tmAADSHLHEbgNB7Z3Ng)
</div>
</div>


<!-- ICML - EOE -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <img src='/_pages/data/figures/EOE.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/poster-EOE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Envisioning Outlier Exposure by Large Language Models for Out-of-Distribution Detection.  
Chentao Cao, Zhun Zhong, **Zhanke Zhou**, Yang Liu, Tongliang Liu, Bo Han✉️  
ICML 2024.
[[paper]](https://arxiv.org/pdf/2406.00806)
[[code]](https://github.com/tmlr-group/EOE/)
[[slides]](./_pages/data/slides-EOE.pdf)
[[poster]](/_pages/data/poster-EOE.pdf)
[[CN-video]](https://www.bilibili.com/video/BV1k4421X7zK?t=1272.0)
[[CN-blog]](https://www.jiqizhixin.com/articles/2024-07-01-16)
</div>
</div>

<!-- ICLR 2024 - One-shot-subgraph -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">ICLR 2024</div> -->
<!-- <img src='/_pages/data/figures/one-shot-subgraph.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/poster-one-shot-subgraph.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Less is More: One-shot Subgraph Reasoning on Large-scale Knowledge Graphs.  
**Zhanke Zhou**, Yongqi Zhang, Jiangchao Yao, Quanming Yao, Bo Han✉️.  
ICLR 2024.
[[paper]](https://arxiv.org/pdf/2403.10231.pdf)
[[code]](https://github.com/tmlr-group/one-shot-subgraph)
[[slides]](/_pages/data/slides-one-shot-subgraph.pdf)
[[poster]](/_pages/data/poster-one-shot-subgraph.pdf)
[[EN-video]](https://iclr.cc/virtual/2024/poster/18681)
</div>
</div>


<!-- ICLR 2024 - Neural Atoms -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">ICLR 2024</div> -->
<!-- <img src='/_pages/data/figures/neural-atoms.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/poster-neural-atoms.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Neural Atoms: Propagating Long-range Interaction in Molecular Graphs   
through Efficient Communication Channel.  
Xuan Li\*, **Zhanke Zhou\***, Jiangchao Yao, Yu Rong, Lu Zhang, Bo Han✉️.  
ICLR 2024.
[[paper]](https://arxiv.org/pdf/2311.01276.pdf)
[[code]](https://github.com/tmlr-group/NeuralAtom)
[[slides]](/_pages/data/slides-neural-atoms.pdf)
[[poster]](/_pages/data/poster-neural-atoms.pdf)
[[EN-video]](https://iclr.cc/virtual/2024/poster/19172)
[[CN-video]](https://www.bilibili.com/video/BV1qH4y1L7mb/?share_source=copy_web&vd_source=65ec14228a98f635bf0406f14c7f8660&t=5342)  
</div>
</div>

<!-- TMLR 2024 - Fairness Surrogate -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/fairness.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Understanding Fairness Surrogate Functions in Algorithmic Fairness.  
Wei Yao\*, **Zhanke Zhou\***, Zhicong Li, Bo Han, Yong Liu✉️.  
TMLR 2024.
[[paper]](https://arxiv.org/pdf/2310.11211.pdf)
[[code]](https://github.com/yw101004244/Understanding-Fairness-Surrogate-Functions)
</div>
</div>


<!-- Arxiv 2024 - Model Inversion Attacks -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/MIA-survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Model Inversion Attacks: A Survey of Approaches and Countermeasures.  
**Zhanke Zhou\***, Jianing Zhu\*, Fengfei Yu\*, Xuan Li, Xiong Peng, Tongliang Liu, Bo Han✉️  
Arxiv 2024.
[[paper]](https://arxiv.org/pdf/2411.10023)
[[code]](https://github.com/AndrewZhou924/Awesome-model-inversion-attack)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
[[CN-blog]](https://mp.weixin.qq.com/s/9B5tFIFfDpu0njeTGBGWxQ)
<!-- [[twitter]]() -->
</div>
</div>


<!-- NeurIPS 2023 - RGIB -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">NeurIPS 2023</div> -->
<!-- <img src='/_pages/data/figures/RGIB.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/poster-RGIB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Combating Bilateral Edge Noise for Robust Link Prediction.  
**Zhanke Zhou**, Jiangchao Yao✉️, Jiaxu Liu, Xiawei Guo, Quanming Yao,  
Li He, Liang Wang, Bo Zheng, Bo Han✉️.  
NeurIPS 2023.
[[paper]](https://arxiv.org/pdf/2311.01196.pdf)
[[code]](https://github.com/tmlr-group/RGIB)
[[slides]](/_pages/data/slides-RGIB.pdf)
[[poster]](/_pages/data/poster-RGIB.pdf)
[[EN-video]](https://slideslive.com/39010502/combating-bilateral-edge-noise-for-robust-link-prediction?ref=search-presentations)
[[CN-video]](https://www.bilibili.com/video/BV1cQ4y1x76L/?t=4490)
[[CN-blog]](https://mp.weixin.qq.com/s/0GypXaICRLrJFywLpdW8bA)  
</div>
</div>


<!-- ICML 2023 - MC-GRA -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">ICML 2023</div> -->
<!-- <img src='/_pages/data/figures/MCGRA.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/poster-GRA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

On Strengthening and Defending Graph Reconstruction Attack with Markov Chain Approximation.  
**Zhanke Zhou**, Chenyu Zhou, Xuan Li, Jiangchao Yao✉️, Quanming Yao, Bo Han✉️.  
ICML 2023.
[[paper]](https://arxiv.org/pdf/2306.09104.pdf)
[[code]](https://github.com/tmlr-group/MC-GRA)
[[slides]](/_pages/data/slides-GRA.pdf)
[[poster]](/_pages/data/poster-GRA.pdf)
[[EN-video]](https://slideslive.com/39003755/on-strengthening-and-defending-graph-reconstruction-attack-with-markov-chain-approximation?ref=search-presentations)
[[CN-video]](https://www.bilibili.com/video/BV1ag4y1Q7ye/?t=7945)
[[CN-blog]](https://mp.weixin.qq.com/s/hKSEMuNx6-g5SXfLjveDlw)  
</div>
</div>


<!-- KDD 2023 - AdaProp -->
<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">KDD 2023</div> -->
<!-- <img src='/_pages/data/figures/AdaProp.png' alt="sym" width="100%"></div></div> -->
<img src='/_pages/data/poster-AdaProp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Adaprop: Learning Adaptive Propagation for Graph Neural Network Based Knowledge Graph Reasoning.  
Yongqi Zhang\*, **Zhanke Zhou\***, Quanming Yao✉️, Xiaowen Chu, Bo Han.  
KDD 2023.
[[paper]](https://arxiv.org/pdf/2205.15319.pdf)
[[code]](https://github.com/LARS-research/AdaProp)
[[slides]](/_pages/data/slides-AdaProp.pdf)
[[poster]](/_pages/data/poster-AdaProp.pdf)
[[EN-video]](https://www.youtube.com/watch?v=4YggNGOcTOk)
[[CN-video]](https://www.bilibili.com/video/BV1EP411p7fP/?t=2078)  
</div>
</div>

<!-- ACL 2022 - KGTuner -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/KGTuner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

KGTuner: Efficient Hyper-parameter Search for Knowledge Graph Learning.  
Yongqi Zhang, **Zhanke Zhou**, Quanming Yao✉️, Yong Li.  
ACL 2022 (long paper).
[[paper]](https://arxiv.org/pdf/2205.02460.pdf)
[[code]](https://github.com/LARS-research/KGTuner)
[[slides]](/_pages/data/slides-KGTuner.pdf)
[[poster]](/_pages/data/poster-KGTuner.pdf)
[[EN-video]](https://www.youtube.com/watch?v=wSbJKPtUNjo/&t=1h52m)
[[CN-blog]](https://mp.weixin.qq.com/s/Pt9j7Zm0ujVQHzt650zYvA)  
</div>
</div>


# 🎖 Awards
- *2025.03*, Madam Hui Tang Shing Yan Fellowship (only two awardees in HKBU).
- *2024.11*, Research Performance Award by COMP of HKBU.
- *2024.10*, Excellent Research Gold Award of TMLR Group.
- *2024.06*, Best Poster Award by COMP of HKBU.
- *2024.05*, Best Research Performance Award by COMP of HKBU.
- *2023.11*, Research Excellence Award by COMP of HKBU.
- *2021.06*, Honorary degree of HUST (Top 2%, highest honour for undergrad).
- *2021.06*, Outstanding Graduate Award of HUST.

# 💬 Talks
- *2024.11*, Seminar on Trustworthy Machine Learning and Foundation Models @AI Time, Online.
[[Video]](https://www.bilibili.com/video/BV1vaUNYTEr3/?t=4700)
- *2023.11*, Seminar on Trustworthy Machine Learning with Imperfect Data @TechBeat, Online.
[[Video]](https://www.bilibili.com/video/BV1cQ4y1x76L/?t=4490)
- *2023.11*, Youth PhD Talk on Trustworthy Machine Learning @AI Time, Online.
[[Video]](https://www.bilibili.com/video/BV1ag4y1Q7ye/?t=7945)

# 💻 Services
- Conference Reviewer for ICML, NeurIPS, ICLR, AISTATS, ACML, AAAI, IJCAI, COLM, ARR, CIKM, SIGKDD.
- Journal Reviewer for TPAMI, TMLR, NEUNET, TNNLS, TKDE.

# 🏫 Teaching
- Teaching Assistant for COMP7250: Machine Learning.
- Teaching Assistant for COMP3015: Data Communications and Networking.
- Teaching Assistant for COMP7070: Advanced Topics in Artificial Intelligence and Machine Learning.

# 📖 Experiences
- *2022.09 - present*, PhD student @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Prof. Bo Han.
- *2025.01 - present*, Visiting student @Stanford-[STAIR Lab](https://cs.stanford.edu/~sanmi/), advised with Prof. Sanmi Koyejo.
- *2022.02 - 2022.09*, Research assistant @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Prof. Bo Han and Prof. Jiangchao Yao.
- *2021.01 - 2024.05*, Visiting student @THU-[LARS Group](https://lars-group.github.io/pages/group.html), advised by Prof. Quanming Yao and Prof. Yongqi Zhang.
- *2020.06 - 2020.09*, Research intern @SJTU-[MVIG Group](https://mvig.org/), advised by Prof. Cewu Lu and Prof. Yonglu Li.
- *2018.03 - 2021.01*, Core Member @HUST-[Dian Group](https://dian.org.cn/), advised by Prof. Yayu Gao, Prof. Chengwei Zhang, and Prof. Xiaojun Hei.

# 💻 Resources

I champion open-source research and hope the following resources can benefit you :)

## Projects
- [Awesome-model-inversion-attack](https://github.com/AndrewZhou924/Awesome-model-inversion-attack)
<img src="https://img.shields.io/github/stars/AndrewZhou924/Awesome-model-inversion-attack?color=yellow&label=Star" alt="Stars" >
- [DeepInception](https://github.com/tmlr-group/DeepInception)
<img src="https://img.shields.io/github/stars/tmlr-group/DeepInception?color=yellow&label=Star" alt="Stars" >
- [FLDRL-in-Wireless-Communication](https://github.com/Mauriyin/FLDRL-in-Wireless-Communication)
<img src="https://img.shields.io/github/stars/Mauriyin/FLDRL-in-Wireless-Communication?color=yellow&label=Star" alt="Stars" >
- [AutoSF](https://github.com/AutoML-4Paradigm/AutoSF)
<img src="https://img.shields.io/github/stars/AutoML-4Paradigm/AutoSF?color=yellow&label=Star" alt="Stars" >
- [MC-GRA](https://github.com/tmlr-group/MC-GRA)
<img src="https://img.shields.io/github/stars/tmlr-group/MC-GRA?color=yellow&label=Star" alt="Stars" >
- [RGIB](https://github.com/tmlr-group/RGIB)
<img src="https://img.shields.io/github/stars/tmlr-group/RGIB?color=yellow&label=Star" alt="Stars" >
- [AdaProp](https://github.com/LARS-research/AdaProp)
<img src="https://img.shields.io/github/stars/LARS-research/AdaProp?color=yellow&label=Star" alt="Stars" >
- [KGTuner](https://github.com/LARS-research/KGTuner)
<img src="https://img.shields.io/github/stars/LARS-research/KGTuner?color=yellow&label=Star" alt="Stars" >
- [graph-ood-detection](https://github.com/AndrewZhou924/graph-ood-detection)
<img src="https://img.shields.io/github/stars/AndrewZhou924/graph-ood-detection?color=yellow&label=Star" alt="Stars" >
- [one-shot-subgraph](https://github.com/tmlr-group/one-shot-subgraph)
<img src="https://img.shields.io/github/stars/tmlr-group/one-shot-subgraph?color=yellow&label=Star" alt="Stars" >
- [NeuralAtom](https://github.com/tmlr-group/NeuralAtom)
<img src="https://img.shields.io/github/stars/tmlr-group/NeuralAtom?color=yellow&label=Star" alt="Stars" >
- [Awesome-Graph-Prompting](https://github.com/AndrewZhou924/Awesome-Graph-Prompting)
<img src="https://img.shields.io/github/stars/AndrewZhou924/Awesome-Graph-Prompting?color=yellow&label=Star" alt="Stars" >


## Source Files of My Talks or Posters
- All my posters are here.
[[slides-pdf]](/_pages/data/all-the-posters.pdf)
[[slides-pptx]](/_pages/data/all-the-posters.pptx)
- 20240420: Less is more: One-shot subgraph reasoning on large-scale knowledge graphs.
[[slides-pdf]](/_pages/data/talks/20240420-one-shot-subgraph.pdf)
[[slides-pptx]](/_pages/data/talks/20240420-one-shot-subgraph.pptx)
- 20240327: Experience sharing on my research career.
[[slides-pdf]](/_pages/data/talks/20240327-experience-sharing.pdf)
[[slides-pptx]](/_pages/data/talks/20240327-experience-sharing.pptx)
- 20231214: Robust graph information bottleneck.
[[slides-pdf]](/_pages/data/talks/20231214-robust-GIB.pdf)
[[slides-pptx]](/_pages/data/talks/20231214-robust-GIB.pptx)
- 20231114: Graph reconstruction attack.
[[slides-pdf]](/_pages/data/talks/20231114-graph-reconstruction-attack.pdf)
[[slides-pptx]](/_pages/data/talks/20231114-graph-reconstruction-attack.pptx)
- 20231109: Recent advances on LLM reasoning with graphs.
[[slides-pdf]](/_pages/data/talks/20231109-Recent-Advances-on-LLM-Reasoning-with-Graphs.pdf)
[[slides-pptx]](/_pages/data/talks/20231109-Recent-Advances-on-LLM-Reasoning-with-Graphs.pptx)
- 20230705: Paper reading of [AAGOD](http://shichuan.org/doc/150.pdf).
[[slides-pdf]](/_pages/data/talks/20230705-paper-reading-AAGOD.pdf)
[[slides-pptx]](/_pages/data/talks/20230705-paper-reading-AAGOD.pptx)
- 20230705: Paper reading of [CFLP](https://proceedings.mlr.press/v162/zhao22e/zhao22e.pdf).
[[slides-pdf]](/_pages/data/talks/20230209-paper-reading-CFLP.pdf)
[[slides-pptx]](/_pages/data/talks/20230209-paper-reading-CFLP.pptx)
- 20230207: Model inversion attack: From images to graphs.
[[slides-pdf]](/_pages/data/talks/20230207-model-inversion-attack.pdf)
[[slides-pptx]](/_pages/data/talks/20230207-model-inversion-attack.pptx)
- 20221028: A review of GNN explanation methods.
[[slides-pdf]](/_pages/data/talks/20221028-explainable-GNN.pdf)
[[slides-pptx]](/_pages/data/talks/20221028-explainable-GNN.pptx)
- 20221026: Paper reading of [CoLE](https://arxiv.org/pdf/2208.09828.pdf).
[[slides-pdf]](/_pages/data/talks/20221026-paper-reading-CoLE.pdf)
[[slides-pptx]](/_pages/data/talks/20221026-paper-reading-CoLE.pptx)
- 20220630: Paper reading of [GSAT](https://arxiv.org/pdf/2201.12987.pdf).
[[slides-pdf]](/_pages/data/talks/20220630-paper-reading-GSAT.pdf)
[[slides-pptx]](/_pages/data/talks/20220630-paper-reading-GSAT.pptx)
- 20220325: Learning query-dependent propagation for knowledge graph reasoning.
[[slides-pdf]](/_pages/data/talks/20220325-structual-learning.pdf)
[[slides-pptx]](/_pages/data/talks/20220325-structual-learning.pptx)
- 20211112: Paper reading of [GraIL](http://proceedings.mlr.press/v119/teru20a/teru20a.pdf).
[[slides-pdf]](/_pages/data/talks/20211112-paper-reading-GraIL.pdf)
[[slides-pptx]](/_pages/data/talks/20211112-paper-reading-GraIL.pptx)
- 20210709: Understanding and benchmarking model search for knowledge graph embedding.
[[slides-pdf]](/_pages/data/talks/20210709-benchmarking-KGE.pdf)
[[slides-pptx]](/_pages/data/talks/20210709-benchmarking-KGE.pptx)
- 20211112: Paper reading of [interstellar](https://neurips.cc/virtual/2020/public/poster_722caafb4825ef5d8670710fa29087cf.html).
[[slides-pdf]](/_pages/data/talks/20210401-paper-reading-interstellar.pdf)
[[slides-pptx]](/_pages/data/talks/20210401-paper-reading-interstellar.pptx)
- 20201213: Paper reading of [UAMT](https://arxiv.org/pdf/1907.07034).
[[slides-pdf]](/_pages/data/talks/20201213-paper-reading-UAMT.pdf)
[[slides-pptx]](/_pages/data/talks/20201213-paper-reading-UAMT.pptx)


<!-- ## References
I benefit a lot from these awesome materials. Thanks!
- TODO -->



<!-- <div align=center> -->
<!-- <a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=400&t=tt&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a> -->
<a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=a&t=m&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a>
<!-- </div> -->