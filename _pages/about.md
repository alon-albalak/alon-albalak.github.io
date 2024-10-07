---
permalink: /
title: "About Me - Alon Albalak"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am the Data Team Lead at [SynthLabs](https://www.synthlabs.ai/), where we focus on post-training for large foundation models. I received my Ph.D. in the [NLP Group](http://nlp.cs.ucsb.edu/) at the University of California, Santa Barbara, advised by professors [William Yang Wang](https://sites.cs.ucsb.edu/~william/) and [Xifeng Yan](https://sites.cs.ucsb.edu/~xyan/). During the first year of my Ph.D. I was gratefully supported by an NSF IGERT Fellowship. While pursuing my Ph.D. I took a year off from research to work at a financial technology startup, [Theta Lake](https://thetalake.com/). Prior to my Ph.D. I received my B.S. in mathematics at Wayne State University, with research advised by [Gang George Yin](https://scholar.google.com/citations?user=nlZ0o_4AAAAJ).

**The primary focus of my research has been on applying ML methods to NLP to improve data efficiency and model performance**. In my research I have explored the use of methods including multi-armed bandits, data selection, multitask learning, transfer learning, reinforcement learning, and neuro-symbolic methods. Additionally, I have a wide array of interests in other topics including model efficiency, logic and reasoning, conversational AI, and multilingual models.

<!--
efficient data selection methods (see [my most recent work](https://arxiv.org/abs/2302.00674)).
However my research has generally touched on finding new methods of *efficiently using limited amounts of task-specific data*. In my path to improving data efficiency I have utilized:
1. Multitask learning ([1](https://arxiv.org/abs/2302.00674),[2](https://neurips2022-enlsp.github.io/papers/paper_50.pdf))
2. Transfer learning ([1](https://aclanthology.org/2022.emnlp-main.751/),[2](https://aclanthology.org/2022.nlp4convai-1.4/),[3](https://assets.amazon.science/80/f0/ad9a999f4562b6e80186a5df00e6/making-something-out-of-nothing-building-robust-task-oriented-dialogue-systems-from-scratch.pdf)),
3. Data augmentation ([1](https://assets.amazon.science/80/f0/ad9a999f4562b6e80186a5df00e6/making-something-out-of-nothing-building-robust-task-oriented-dialogue-systems-from-scratch.pdf),[2](https://aclanthology.org/2023.eacl-demo.1/)),
4. Neuro-symbolic methods ([1](https://arxiv.org/abs/2205.14268), [2](https://openreview.net/pdf?id=8ZIJa8Z__5L), [3](https://arxiv.org/abs/2207.07238), [4](http://arxiv.org/abs/2305.12295)).
-->

<br>

## \*\* NEWS \*\*

### \[09/2024\] ["DataComp-LM: In search of the next generation of training sets for language models"](https://www.datacomp.ai/dclm/) will be presented at NeurIPS 2024

### \[08/2024\] ["Eagle and Finch: RWKV with Matrix-Valued States and Dynamic Recurrence"](https://arxiv.org/abs/2404.05892) will be presented at COLM 2024

### \[07/2024\] ["A Survey on Data Selection for Language Models"](https://arxiv.org/abs/2402.16827) will appear in the Transactions of Machine Learning Research (TMLR)
<span style="font-size:0.85em;">This survey presents a comprehensive review of data selection methods and related areas, providing a taxonomy of existing approaches that allows us to point at holes in research, and propose promising avenues for future research. The aim of this resource is to accelerate progress on data-cenrtic research, for both new and established researchers!<br>
We also compiled a [paper list](https://github.com/alon-albalak/data-selection-survey).
</span>

### \[04/2024\] I started as the Data Team Lead, and Member of Technical Staff at [SynthLabs](https://www.synthlabs.ai/)

### \[04/2024\] My dissertation: ["Understanding and Improving Language Models Through a Data-Centric Lens"](https://www.proquest.com/openview/dba1a30ede6747ee6b8bd206d65a61ed/1?pq-origsite=gscholar&cbl=18750&diss=y) was accepted by the University of California, Santa Barbara!

### \[02/2024\] New resource on foundation model best practices, [The Foundation Model Development Cheatsheet](https://fmcheatsheet.org/)
<span style="font-size:0.85em;">This cheatsheet compiles resources and tools for the full lifecycle of model development including: data collection, preprocessing, and documentation; model pretraining and finetuning; environmental impact estimation; assessing risks and harms; as well as model documentation, release, and licensing.<br>
Check out my [blog](http://nlp.cs.ucsb.edu/blog/a-new-guide-for-the-responsible-development-of-foundation-models.html) for more details!<br>
Also, check out the [up-to-date cheatsheet here](https://fmcheatsheet.org/), or a [static pdf of the cheatsheet here](https://github.com/allenai/fm-cheatsheet/blob/main/app/resources/paper.pdf).
</span>

### \[10/2023\] "Efficient Online Data Mixing For Language Model Pre-Training" was accepted as a spotlight to the [r0-FoMo](https://sites.google.com/view/r0-fomo/home) workshop at NeurIPS
<span style="font-size:0.85em;">This work presents an extremely efficient online data mixing algorithm that reaches the same model perplexity of the next best method ([DoReMi](https://arxiv.org/abs/2305.10429)) with 19% fewer iterations, and improves downstream performance by 1.9% while adding a miniscule 0.000007% overhead.<br>
Check out the [pre-print](https://arxiv.org/abs/2312.02406)
</span>

### \[10/2023\] Accepted to EMNLP 2023 - "RWKV: Reinventing RNNs for the Transformer Era"
<span style="font-size:0.85em;">RWKV is a new model architecture that combines the efficient parallelizable training of Transformers with the efficient inference of RNNs.<br>
Check out the [paper](https://arxiv.org/abs/2305.13048) and [code](https://github.com/BlinkDL/RWKV-LM) for more information.
</span>

### \[10/2023\] Accepted at EMNLP 2023 - "Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning"
<span style="font-size:0.85em;">This work demonstrates that combining Large Language Models (LLMs) with symbolic solvers makes for a strong method for solving logical problems.<br>
Check out the [paper](http://arxiv.org/abs/2305.12295) and the [code](https://github.com/teacherpeterpan/Logic-LLM).
</span>

### \[09/2023\] Accepted to NeurIPS 2023 - "Improving Few-shot Generalization by Exploring and Exploiting Auxiliary Data"
<span style="font-size:0.85em;">This work presents 2 methods of few-shot learning with auxiliary data, inspired by multi-armed bandits. These methods show significant improvement over multi-tasking followed by fine tuning (9% improvement).<br>
Check out the [paper](https://arxiv.org/abs/2302.00674) and the [code](https://github.com/alon-albalak/FLAD) for more information.
</span>

### \[05/2023\] Accepted to ACL 2023 - "Modeling Utterance-level Causality in Conversations"
<span style="font-size:0.85em;">Check out the [paper](https://arxiv.org/abs/2212.10515) for more details.
</span>

### \[04/2023\] Accepted at IJCAI 2023 - "NeuPSL: Neural Probabilistic Soft Logic"
<span style="font-size:0.85em;">NeuPSL is a neuro-symbolic framework that unites the powerful symbolic reasoning of PSL with the representation learning of deep neural networks.<br>
Check out the [paper](https://arxiv.org/pdf/2205.14268.pdf) for more.
</span>

### \[02/2023\] The FETA benchmark on task transfer will be a shared task at the [NLP for ConvAI](https://sites.google.com/view/5thnlp4convai/home) workshop at ACL '23!
<span style="font-size:0.85em;">**\*Awards\*** The FETA benchmark will have prizes for top scorers and most innovative approaches!<br><br>
**\*Purpose\*** The FETA benchmark shared task aims to bring together researchers from a variety of backgrounds and compare their best ideas for task transfer. The benchmark allows for comparing many different methods including: instruction/prompt fine-tuning, source-task selection, multitask learning, continued pre-training, meta-learning, and many more!<br><br>
See detailed rules, starter code, and submission instructions on [the website](https://alon-albalak.github.io/feta-website/).
</span>

### \[02/2023\] "Addressing Issues of Cross-Linguality in Open-Retrieval Question Answering Systems For Emergent Domains" was accepted at EACL 2023!
<span style="font-size:0.85em;">This work addresses the low-resource question-answering setting where supporting documents may not be in the same language as the query, cross-lingual Open-retrieval QA. In particular, this is an important problem in emergent domains, where the majority of supporting documents are more likely to be in a limited number of languages.
Check out the [paper](https://aclanthology.org/2023.eacl-demo.1/) and [code](https://github.com/alon-albalak/XOR-COVID) for more information.
</span>

### \[01/2023\] The Transfer Learning for NLP Workshop (TL4NLP) workshop is available to watch!
<span style="font-size:0.85em;">TL4NLP explored insights and advances on transfer learning, including insightful talks from our guest speakers and hot takes from our debaters.<br>
TL4NLP features talks from **Mike Lewis**, **Percy Liang**/**Ananya Kumar**, **Graham Neubig**, **David Adelani**, and **Jonas Pfeiffer**<br>
as well as a debate between **Sara Hooker** and **Kyunghyun Cho**.<br>
Check out the talks, topics, and more at [tl4nlp.githb.io](https://tl4nlp.github.io).<br>
[Find recorded talks here](https://tl4nlp.github.io/Program/).
</span>

<!--
https://neurips.cc/virtual/2022/workshop/50006
Starting Timestamps:
Jonas Pfeiffer - 36:55
Graham Neubig - 1:30:45 (describes my current project at 2:10:50-2:11:40)
Percy Liang & Ananya Kumar - 2:13:33
Sara Hooker and Kyunghyun Cho - 3:13:19
David Adelani - 5:42:45
Mike Lewis - 6:25:46
-->


### \[10/2022\] My paper on benchmarking task transfer will be at EMNLP '22: [FETA](https://aclanthology.org/2022.emnlp-main.751/)
<span style="font-size:0.85em;">FETA is the largest NLP benchmark for intra-dataset task transfer, where task transfer is isolated from domain shift.<br>
Check out the [paper](https://aclanthology.org/2022.emnlp-main.751/), and our [github repo](https://github.com/alon-albalak/TLiDB) for more.
</span>

<!--
### \[10/2022\] My work on data effiency for small(-ish) language models will be presented an ENLSP '22: [Paper](https://neurips2022-enlsp.github.io/papers/paper_50.pdf)

### \[05/2022\] I will join Meta as a Research Science Intern for summer 2022!

### \[05/2022\] The UCSB [GauchoBot](https://www.amazon.science/alexa-prize/teams/university-of-california-santa-barbara-team-gauchobot) has advanced to the finals of the Alexa Prize Taskbot Challenge!

### \[04/2022\] [D-REX](https://aclanthology.org/2022.nlp4convai-1.4/) accepted to ConvAI workshop, co-located with ACL 2022
-->
