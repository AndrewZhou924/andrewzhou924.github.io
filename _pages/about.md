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

Hi there, I am Zhanke Zhou, a Ph.D. student at Trustworthy Machine Learning and Reasoning (TMLR) Group in the Department of Computer Science, Hong Kong Baptist University, advised by [Dr. Bo Han](https://bhanml.github.io/).

My research interests lie in **trustworthy machine reasoning** with structural data and foundation models for solving **complex problems** (e.g., combinatorial optimization and planning) and boosting **scientific discoveries** (e.g., math, biology, and chemistry).

<!-- *TODO: research belief and position.* -->

*Please feel free to [email me](mailto:cszkzhou@comp.hkbu.edu.hk) for research, collaborations, or a casual chat. My Wechat ID is zhouzhanke924.* 

<!-- *Please consider giving me [anonymous feedback](https://docs.google.com/forms/d/e/1FAIpQLSeE4_y14QlUtJ8MhltnGnWwco7J1sWprXnlGoFWFo002k26lw/viewform?usp=sf_link).* -->


# 📖 Educations
- *2022.09 - present*, Hong Kong Baptist University (HKBU), Ph.D. in Computer Science.
- *2017.09 – 2021.06*, Huazhong University of Science and Technology (HUST), B.E. in Electronics 
and Information Engineering (SeedClass).

<!-- # Research
TODO: a short summary of my research -->

# 📝 Selected Publications
\* Co-first author, ✉️ Corresponding author.

<!-- ICML 2023 - MC-GRA -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='/_pages/data/figures/MCGRA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

On Strengthening and Defending Graph Reconstruction Attack with Markov Chain Approximation.  
[[paper]](https://arxiv.org/pdf/2306.09104.pdf)
[[code]](https://github.com/tmlr-group/MC-GRA)
[[slides]](/_pages/data/slides-GRA.pdf)
[[poster]](/_pages/data/poster-GRA.pdf)
[[EN-video]](https://slideslive.com/39003755/on-strengthening-and-defending-graph-reconstruction-attack-with-markov-chain-approximation?ref=search-presentations)
[[CN-video]](https://www.bilibili.com/video/BV1ag4y1Q7ye/?t=7945)
[[CN-blog]](https://mp.weixin.qq.com/s/hKSEMuNx6-g5SXfLjveDlw)  
  **Zhanke Zhou**, Chenyu Zhou, Xuan Li, Jiangchao Yao✉️, Quanming Yao, Bo Han✉️.

<details>
<summary>Quick Introduction</summary>
Although powerful graph neural networks (GNNs) have boosted numerous real-world applications, the potential privacy risk is still under-explored. To close this gap, we perform the first comprehensive study of graph reconstruction attack that aims to reconstruct the adjacency of nodes.<br><br>

We show that a range of factors in GNNs can lead to the surprising leakage of private links. Especially by taking GNNs as a Markov chain and attacking GNNs via a flexible chain approximation, we systematically explore the underneath principles of graph reconstruction attack, and propose two information theory-guided mechanisms: (1) the chain-based attack method with adaptive designs for extracting more private information; (2) the chain-based defense method that sharply reduces the attack fidelity with moderate accuracy loss.<br><br>

Such two objectives disclose a critical belief that to recover better in attack, you must extract more multi-aspect knowledge from the trained GNN; while to learn safer for defense, you must forget more link-sensitive information in training GNNs. Empirically, we achieve state-of-the-art results on six datasets and three common GNNs.
</details>
</div>
</div>

<!-- NeurIPS 2023 - RGIB -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='/_pages/data/figures/RGIB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Combating Bilateral Edge Noise for Robust Link Prediction.  
[[paper]](https://arxiv.org/pdf/2311.01196.pdf)
[[code]](https://github.com/tmlr-group/RGIB)
[[slides]](/_pages/data/slides-RGIB.pdf)
[[poster]](/_pages/data/poster-RGIB.pdf)
[[EN-video]](https://slideslive.com/39010502/combating-bilateral-edge-noise-for-robust-link-prediction?ref=search-presentations)
[[CN-video]](https://www.bilibili.com/video/BV1cQ4y1x76L/?t=4490)
[[CN-blog]](https://mp.weixin.qq.com/s/0GypXaICRLrJFywLpdW8bA)  
  **Zhanke Zhou**, Jiangchao Yao✉️, Jiaxu Liu, Xiawei Guo, Quanming Yao, Li He, Liang Wang, Bo Zheng, Bo Han✉️.

<details>
<summary>Quick Introduction</summary>
Although link prediction on graphs has achieved great success with the development of graph neural networks (GNNs), the potential robustness under the edge noise is still less investigated.  To close this gap, we first conduct an empirical study to disclose that the edge noise bilaterally perturbs both input topology and target label, yielding severe performance degradation and representation collapse.<br><br> 

To address this dilemma, we propose an information-theory-guided principle, Robust Graph Information Bottleneck (RGIB), to extract reliable supervision signals and avoid representation collapse. Different from the basic information bottleneck, RGIB further decouples and balances the mutual dependence among graph topology, target labels, and representation, building new learning objectives for robust representation against the bilateral noise. <br><br>

Two instantiations, RGIB-SSL and RGIB-REP, are explored to leverage the merits of different methodologies, i.e., self-supervised learning and data reparameterization, for implicit and explicit data denoising, respectively. Extensive experiments on six datasets and three GNNs with diverse noisy scenarios verify the effectiveness of our RGIB instantiations.
</details>
</div>
</div>


<!-- ICLR 2024 - One-shot-subgraph -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='/_pages/data/figures/one-shot-subgraph.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Less is More: One-shot Subgraph Reasoning on Large-scale Knowledge Graphs.  
[[paper]](https://arxiv.org/pdf/2403.10231.pdf)
[[code]](https://github.com/tmlr-group/one-shot-subgraph)
[[slides]](/_pages/data/slides-one-shot-subgraph.pdf)
[[poster]](/_pages/data/poster-one-shot-subgraph.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/?share=92165&s=396ea382-bc2a-451b-8ee0-111e94581a7b)  
**Zhanke Zhou**, Yongqi Zhang, Jiangchao Yao, Quanming Yao, Bo Han✉️.

<details>
<summary>Quick Introduction</summary>
To deduce new facts on a knowledge graph (KG), a link predictor learns from the graph structure and collects local evidence to find the answer to a given query. However, existing methods suffer from a severe scalability problem due to the utilization of the whole KG for prediction, which hinders their promise on large-scale KGs and cannot be directly addressed by vanilla sampling methods.<br><br>

In this work, we propose the one-shot-subgraph link prediction to achieve efficient and adaptive prediction. The design principle is that, instead of directly acting on the whole KG, the prediction procedure is decoupled into two steps, i.e., (i) extracting only one subgraph according to the query and (ii) predicting on this single, query-dependent subgraph.<br><br> 

We reveal that  the non-parametric and computation-efficient heuristics Personalized PageRank (PPR) can effectively identify the potential answers and supporting evidence. With efficient subgraph-based prediction, we further introduce the automated searching of the optimal configurations in both data and model spaces. Empirically, we achieve promoted efficiency and leading performances on five large-scale benchmarks.
</details>
</div>
</div>


<!-- ICLR 2024 - Neural Atoms -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='/_pages/data/figures/neural-atoms.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Neural Atoms: Propagating Long-range Interaction in Molecular Graphs through Efficient Communication Channel.  
[[paper]](https://arxiv.org/pdf/2311.01276.pdf)
[[code]](https://github.com/tmlr-group/NeuralAtom)
[[slides]](/_pages/data/slides-neural-atoms.pdf)
[[poster]](/_pages/data/poster-neural-atoms.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/?share=92308&s=8e966150-4ba4-41b7-97d3-8ed0c1a1cd0c)
[[CN-video]](https://www.bilibili.com/video/BV1qH4y1L7mb/?share_source=copy_web&vd_source=65ec14228a98f635bf0406f14c7f8660&t=5342)  
  Xuan Li\*, **Zhanke Zhou\***, Jiangchao Yao, Yu Rong, Lu Zhang, Bo Han✉️.

<details>
<summary>Quick Introduction</summary>
Graph Neural Networks (GNNs) have been widely adopted for drug discovery with molecular graphs. Nevertheless, current GNNs mainly excel in leveraging short-range interactions (SRI) but struggle to capture long-range interactions (LRI), both of which are crucial for determining molecular properties.<br><br> 

To tackle this issue, we propose a method to abstract the collective information of atomic groups into a few Neural Atoms by implicitly projecting the atoms of a molecular. Specifically, we explicitly exchange the information among neural atoms and project them back to the atoms’ representations as an enhancement. With this mechanism, neural atoms establish the communication channels among distant nodes, effectively reducing the interaction scope of arbitrary node pairs into a single hop. <br><br>

To provide an inspection of our method from a physical perspective, we reveal its connection to the traditional LRI calculation method, Ewald Summation. The Neural Atom can enhance GNNs to capture LRI by approximating the potential LRI of the molecular. We conduct extensive experiments on four long-range graph benchmarks, covering graph-level and link-level tasks on molecular graphs. We achieve up to a 27.32\% and 38.27\% improvement in the 2D and 3D scenarios, respectively. Empirically, our method can be equipped with an arbitrary GNN to help capture LRI.
</details>
</div>
</div>


<!-- KDD 2023 - AdaProp -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2023</div><img src='/_pages/data/figures/AdaProp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Adaprop: Learning Adaptive Propagation for Graph Neural Network Based Knowledge Graph Reasoning.  
[[paper]](https://arxiv.org/pdf/2205.15319.pdf)
[[code]](https://github.com/LARS-research/AdaProp)
[[slides]](/_pages/data/slides-AdaProp.pdf)
[[poster]](/_pages/data/poster-AdaProp.pdf)
[[EN-video]](https://www.youtube.com/watch?v=4YggNGOcTOk)
[[CN-video]](https://www.bilibili.com/video/BV1EP411p7fP/?t=2078)  
  Yongqi Zhang\*, **Zhanke Zhou\***, Quanming Yao✉️, Xiaowen Chu, Bo Han.


<details>
<summary>Quick Introduction</summary>
Due to the popularity of Graph Neural Networks (GNNs),  various GNN-based methods have been designed to reason on knowledge graphs (KGs). An important design component of GNN-based KG reasoning methods is called the propagation path, which contains a set of involved entities in each propagation step. Existing methods use hand-designed propagation paths, ignoring the correlation between the entities and the query relation. In addition, the number of involved entities will explosively grow at larger propagation steps. <br><br>

In this work, we are motivated to learn an adaptive propagation path in order to filter out irrelevant entities while preserving promising targets. First, we design an incremental sampling mechanism where the nearby targets  and layer-wise connections can be preserved with linear complexity. Second, we design a learning-based sampling distribution to identify the semantically related entities. Extensive experiments show that our method is powerful, efficient and semantic-aware.
</details>
</div>
</div>


# 🎖 Awards
- *2024.06*, Best Poster Award by COMP of HKBU.
- *2024.05*, Best Research Performance Award by COMP of HKBU.
- *2023.11*, Research Excellence Award by COMP of HKBU.
- *2021.06*, Honorary degree of HUST (Top 2%, highest honour for undergrad).
- *2021.06*, Outstanding Graduate Award of HUST.

# 💬 Talks
- *2023.11*, Seminar on Trustworthy Machine Learning with Imperfect Data @TechBeat, Online.
[[Video]](https://www.bilibili.com/video/BV1cQ4y1x76L/?t=4490)
- *2023.11*, Youth PhD Talk on Trustworthy Machine Learning @AI Time, Online.
[[Video]](https://www.bilibili.com/video/BV1ag4y1Q7ye/?t=7945)

# 💻 Services
- Conference Reviewer for ICML, NeurIPS, ICLR, AISTATS, ACML, AAAI, IJCAI, COLM, CIKM, SIGKDD.
- Journal Reviewer for TMLR, NEUNET, TNNLS.

# 🏫 Teaching
- Teaching Assistant for COMP7250: Machine Learning.
- Teaching Assistant for COMP3015: Data Communications and Networking.
- Teaching Assistant for COMP7070: Advanced Topics in Artificial Intelligence and Machine Learning.

# 📖 Experiences
- *2022.09 - present*, PhD student @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Dr. Bo Han.
- *2022.02 - 2022.09*, Research assistant @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Dr. Bo Han and Dr. Jiangchao Yao.
- *2021.01 - 2022.02*, Research intern @THU-[LARS Group](https://lars-group.github.io/pages/group.html), advised by Dr. Quanming Yao and Dr. Yongqi Zhang.
- *2020.06 - 2020.09*, Research intern @SJTU-[MVIG Group](https://mvig.org/), advised by Dr. Cewu Lu and Dr. Yonglu Li.
- *2018.03 - 2021.01*, Core Member @HUST-[Dian Group](https://dian.org.cn/), advised by Dr. Yayu Gao, Dr. Chengwei Zhang, and Dr. Xiaojun Hei.

# 💻 Resources

*I hold that life's best resources, like air, should be free.*  
*Hence, I champion open-source research and hope the following resources can benefit you :)*

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