# LLM4Opt
## Collection on Large Language Models for Optimization (LLM4Opt)

Applying Large language models (LLMs) for diverse optimization tasks (Opt) is an emerging research area. This is a collection of references and papers of LLM4Opt. The Papers are sorted by time (first publicly available). Any suggestions and pull requests are welcome.

It is far from a comprehensive list. If you want to update the list:

+ Fork, Add, and Merge
+ Report an [issue](https://github.com/FeiLiu36/LLM4Opt/issues)
+ Contact Fei Liu (fliu36-c@my.cityu.edu.hk)
  
The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact us.

## Overview
* [Platform](https://github.com/FeiLiu36/LLM4Opt#Platform)
* [Tutorial](https://github.com/FeiLiu36/LLM4Opt#Tutorial&Workshop)
* [Competition](https://github.com/FeiLiu36/LLM4Opt#Competition)
* [Research Papers](https://github.com/FeiLiu36/LLM4Opt#Papers)
  * [Review]
  * [Position Paper]
  * [AI, Algorithm Design]
  * [LLM as optimizer]
  * [Machine Learning]
  * [Science]
  * [...]
 
## Platform
+ [EoH (Evolution of Heuristics)](https://github.com/FeiLiu36/EoH) (optimization, mathematics, machine learning, etc)
+ [OpenELM](https://github.com/CarperAI/OpenELM) (robots, image, programming puzzles, etc)

## Tutorial&Workshop
+ NeurIPS 2023 [Workshop: Foundation Models for Decision Making](https://nips.cc/virtual/2023/workshop/66525)
+ GECCO 2024 [Workshop: Large Language Models for and with Evolutionary Computation (LLMfwEC)](https://sites.google.com/view/llmfwec-2024)
+ GECCO 2024 [Workshop: EGML-EC — 3rd GECCO workshop on Enhancing Generative Machine Learning with Evolutionary Computation (EGML-EC) 2024](https://sites.google.com/view/egml-ec2024)
+ GECCO 2024 [Tutorial: Using Large Language Models for Evolutionary Search](https://gecco-2024.sigevo.org/Tutorials) || [Tutorial Report: Evolving Code with A Large Language Model](https://arxiv.org/pdf/2401.07102)
+ PPSN 2024 [Tutorial: Large Language Models as Tools for Metaheuristic Design: Exploring Challenges and Opportunities](https://ppsn2024.fh-ooe.at/program/)
+ KDD 2024 [Tutorial: NL2Code-Reasoning and Planning with LLM for Code Development](https://kdd2024.kdd.org/workshops/), [DEEP LEARNING AND LARGE LANGUAGE MODELS FOR KNOWLEDGE GRAPHS](https://genetasefa.github.io/dl4kg2024/)
+ ICML 2024 [Workshop: AI for Math](https://sites.google.com/view/ai4mathworkshopicml2024)

## Competition
+ AAAI 2024 [Global Competition on Math Problem Solving and Reasoning](https://ai4ed.cc/competitions/aaai2024competition)
+ ICML 2024 [Challenges on Automated Math Reasoning](https://sites.google.com/view/ai4mathworkshopicml2024/challenges)

## Papers
### Review
+ Evolutionary Computation in the Era of Large Language Model: Survey and Roadmap, Arxiv, Jan 2024, [code], [paper](https://arxiv.org/abs/2401.10034)
+ A Survey of Neural Code Intelligence: Paradigms, Advances and Beyond, Arxiv, Mar. 2024, [code], [paper](https://arxiv.org/abs/2403.14734)
+ When Large Language Model Meets Optimization, Arxiv, May 2024, [code], [paper](http://www.arxiv.org/pdf/2405.10098)

### Position paper
+ The Era OF Semantic Decoding, Arxiv, Mar. 2024, [code], [paper](https://arxiv.org/pdf/2403.14562)
+ Leveraging Foundational Models for Black-Box Optimization: Benefits, Challenges, and Future Directions, **ICML 2024** , May 2024, [code], [paper](https://arxiv.org/abs/2405.03547)

### Algorithm Design
+ Algorithm Evolution using Large Language Model, Arxiv, Nov 2023, [code](https://github.com/FeiLiu36/eoh),[paper](https://arxiv.org/abs/2311.15249) 
+ Mathematical discoveries from program search with large language models, **Nature**, Dec 2023, [code](https://github.com/google-deepmind/funsearch),[paper](https://www.nature.com/articles/s41586-023-06924-6)
+ Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model, **ICML, 2024**, [code](https://github.com/FeiLiu36/EoH), [paper](https://arxiv.org/abs/2401.02051)
+ ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution, Arxiv, Feb 2024, [code](https://github.com/ai4co/LLM-as-HH), [paper](https://arxiv.org/abs/2402.01145)
+ Discovering More Effective Tensor Network Structure Search Algorithms via Large Language Models (LLMs), [code], [paper](https://arxiv.org/abs/2402.02456)
+ AutoSAT: Automatically Optimize SAT Solvers via Large Language Models, Arxiv, Feb 2024, [code], [paper](https://arxiv.org/abs/2402.10705)
+ Large Language Models tO Enhance Bayesian Optimization, Arxiv Feb 2024, **ICLR 2024** [code], [paper](https://openreview.net/pdf?id=OOxotBmGol)
+ On the Self-Verification Limitations of Large Language Models on Reasoning and Planning Tasks, Arxiv, Feb 2024, [code], [paper](https://arxiv.org/abs/2402.08115)
+ How Can LLM Guide RL? A Value-Based Approach, Arxiv, Feb 2024, [code](https://github.com/agentification/Language-Integrated-VI), [paper](https://arxiv.org/abs/2402.16181)
+ Evolve Cost-aware Acquisition Functions Using Large Language Models, Arxiv, April 2024, [code], [paper](https://arxiv.org/abs/2404.16906)
+ Benchmarking ChatGPT on Algorithmic Reasoning, Arxiv, April 2024, [code], [paper](https://arxiv.org/abs/2404.03441)
+ How Multimodal Integration Boost the Performance of LLM for Optimization: Case Study on Capacitated Vehicle Routing Problems, Arxiv, March 2024, [code], [paper](https://arxiv.org/abs/2403.01757)
+ LLM-ABR: Designing Adaptive Bitrate Algorithms via Large Language Models, Arxiv, April 2024, [code], [paper](https://arxiv.org/abs/2404.01617)
+ Constrained Neural Networks for Interpretable Heuristic Creation to Optimise Computer Algebra Systems, Arxiv, April 2024, [code], [paper](https://arxiv.org/abs/2404.17508)
+ GLHF: General Learned Evolutionary Algorithm Via Hyper Functions, Arxiv [code] [paper](https://arxiv.org/pdf/2405.03728)


### LLM as optimizer
+ Large Language Models as Optimizers, Arxiv, Sep 2023, [code](https://github.com/google-deepmind/opro), [paper](https://arxiv.org/abs/2309.03409)
+ Large language model for multi-objective evolutionary optimization, Arxiv, Oct. 2023, [code](https://github.com/FeiLiu36/LLM4MOEA), [paper](https://arxiv.org/abs/2310.12541)
+ Large Language Models as Evolutionary Optimizers, Arxiv, Oct. 2023, [code], [paper](https://arxiv.org/abs/2310.19046)
+ Using Large Language Models for Hyperparameter Optimization, **NeurIPS 2023**, [code], [paper](https://arxiv.org/abs/2312.04528)
+ Large Language Models As Evolution Strategies, Arxiv, Feb. 2024, [code], [paper](https://arxiv.org/abs/2402.18381)
+ Large Language Model-based Evolutionary Optimizer: Reasoning with Elitism, Arxiv, Mar. 2024, [code], [paper](https://arxiv.org/abs/2403.02054)
+ Large Language Model-Aided Evolutionary Search for Constrained Multiobjective Optimization, Arxiv, May 9, 2024, [code], [paper](https://arxiv.org/pdf/2401.03038)

### Code Generation
+ L2MAC: LARGE LANGUAGE MODEL AUTOMATIC COMPUTER FOR EXTENSIVE CODE GENERATION, Arxiv Oct 2023, **ICLR 2024**, [code] [paper](https://arxiv.org/abs/2310.02003)
+ 


### Prompt Opt
+ Connecting Large Language Models with Evolutionary Algorithms Yields Powerful Prompt Optimizers, Arxiv Sep 2023, **ICLR 2024** [code], [paper](https://arxiv.org/abs/2309.03409)
+ PromptAgent: Strategic Planning with Language Models Enables Expert-level Prompt Optimization, Arxiv Oct 2023, **ICLR 2024** [code], [paper](https://arxiv.org/abs/2310.16427)

### Machine Learning
+ Evolution through Large Models, Arxiv, June 2022, [code](https://github.com/CarperAI/OpenELM), [arxiv paper](https://arxiv.org/abs/2206.08896), [chapter](https://link.springer.com/chapter/10.1007/978-981-99-3814-8_11)
+ Evoprompting: Language models for code-level neural architecture search, **NeuIPS 2023**, [code], [paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/184c1e18d00d7752805324da48ad25be-Paper-Conference.pdf)
+ Eureka: Human-Level Reward Design via Coding Large Language Models, **ICLR 2024**, [code](https://github.com/eureka-research/Eureka), [paper](https://arxiv.org/abs/2310.12931)
+ LANGUAGE MODEL DECODING AS DIRECT METRICS OPTIMIZATION, Arxiv, Oct 2023, **ICLR 2024**, [code], [paper](https://arxiv.org/abs/2310.01041)
+ Label-free Node Classification on Graphs with Large Language Models (LLMS), Arxiv, Oct 2023, **ICLR 2024**, [code], [paper](https://arxiv.org/abs/2310.04668)
+ L-AutoDA: Leveraging Large Language Models for Automated Decision-based Adversarial Attacks, **GECCO 2024**, Jan 2024 [code], [paper](https://arxiv.org/abs/2401.15335)
+ Data-driven Discovery with Large Generative Models, Arxiv, Feb. 2024, [code], [paper](https://arxiv.org/abs/2402.13610)
+ Large Language Model-driven Meta-structure Discovery in Heterogeneous Information Network, Arxiv, Feb. 2024, [code], [paper](https://arxiv.org/abs/2402.11518)
+ LLM Guided Evolution-The Automation of Models Advancing Models, Arxiv, Mar. 2024, [code], [paper](https://arxiv.org/pdf/2403.11446)
+ Identify Critical Nodes in Complex Network with Large Language Models, Arxiv, Mar. 2024, [code], [paper](https://arxiv.org/abs/2403.03962)
+ Evolving Interpretable Visual Classifiers with Large Language Models, Arxiv, April 2024, [code], [paper](https://arxiv.org/abs/2404.09941)



### Science
+ A Prompt-Engineered Large Language Model, Deep Learning Workflow for Materials Classification, Arxiv, Jan 2024, [code], [paper](https://arxiv.org/abs/2401.17788)
+ LLM-SR: Scientific Equation Discovery via Programming with Large Language Models, Arxiv, April 2024, [code], [paper](https://arxiv.org/pdf/2404.18400)
+ Large Language Model Agent as a Mechanical Designer, Arxiv, April 2024, [code], [paper](https://arxiv.org/abs/2404.17525)

### Industry
+ Large Language Models for Supply Chain Optimization, Arxiv, July 2023, [code], [paper](https://arxiv.org/abs/2307.03875)
+ LLM4EDA: Emerging Progress in Large Language Models for Electronic Design Automation, Arxiv, Dec. 2023, [code], [paper](https://arxiv.org/abs/2401.12224)


## Related Collections
+ [Foundation Models for Combinatorial Optimization](https://github.com/ai4co/awesome-fm4co)
+ [MOO-ML-Papers](https://github.com/xzhang2523/awesome-moo-ml-papers)
+ [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM)

