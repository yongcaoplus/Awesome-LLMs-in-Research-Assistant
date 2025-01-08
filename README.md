<p align="left">
    <a href="README_zh.md">中文</a>&nbsp ｜ &nbspEnglish&nbsp
</p>

# 📚 Awesome LLMs in Research Assistant

![](./img/logo.png)

With the powerful capabilities of LLMs in understanding and processing scientific documents, their application as research assistants has become increasingly promising. In this repo, we aim to provide **a comprehensive overview of the latest awesome works that leverage LLMs as research assistants**. We also include platforms, tutorials, and workshops to help you get started with your relevant projects.

Any contributions and discussions are welcome! 

![Awesome](https://img.shields.io/badge/Awesome-LLMs%20in%20Research%20Assistant-blue) 

---

## Contents

1. [Survey](#1-survey)
2. [Tasks](#2-tasks)
   * [Scientific Impact Prediction](#21-scientific-impact-prediction)      
   * [Scientific Question Answering](#22-scientific-question-answering)
   * [Data Analysis and Visualization](#23-data-analysis-and-visualization) 
   * [Research Code](#24-research-code)
   * [Peer-Review](#25-peer-review)
   * [Literature Review and Summarization](#26-literature-review-and-summarization) 
   * [Writing Assistance](#27-writing-assistance) 
   * [Idea and Novelty Generation](#28-idea-and-novelty-generation)  
   * [Representation Learning](#29-representation-learning)
3. [Techniques](#3-techniques)
   * [Prompt Engineering](#31-prompt-engineering)   
   * [Few-Shot Learning](#32-few-shot-learning) 
   * [Single Agent](#33-single-agent)   
   * [RAG](#34-rag)
4. [Dataset](#4-dataset)  
5. [Evaluation](#5-evaluation)  
6. [Platforms](#6-platforms)  
   * [Personalized Recommendation](#61-personalized-recommendation)  
   * [PaperChat](#62-paperchat)    
   * [Writing Assistant](#63-writing-assistant)   
   * [Integrated](#64-Integrated)
7. [Workshops and Tutorials](#7-workshops-and-tutorials)  

---

## 1. Survey

* **A Comprehensive Survey of Scientific Large Language Models and Their Applications in Scientific Discovery**, 11.2024, *EMNLP main 2024*. [[Paper]](https://aclanthology.org/2024.emnlp-main.498/), [[Code]](https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models).

* **Topics, Authors, and Institutions in Large Language Model Research: Trends from 17K arXiv Papers**, 6.2024, *NAACL main 2024*, [[Paper]](https://aclanthology.org/2024.naacl-long.67/), [[Code]](https://github.com/rmovva/LLM-publication-patterns-public).

* **Scientific Fact-Checking: A Survey of Resources and Approaches**, 7.2023, *ACL findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-acl.387/).  


## 2. Tasks

### 2.1 Scientific Impact Prediction

* **From Words to Worth: Newborn Article Impact Prediction with LLM**, 12.2024, *AAAI 2025*, [[Paper]](https://arxiv.org/abs/2408.03934), [[Code]](https://github.com/ssocean/NAIP).

* **HLM-Cite: Hybrid Language Model Workflow for Text-based Scientific Citation Prediction**, 10.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2410.09112), [[Code]](https://github.com/tsinghua-fib-lab/H-LM). 

* **CausalCite: A Causal Formulation of Paper Citations**, 8.2024, *ACL Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.497/), [[Code]](https://github.com/causalNLP/causal-cite).  

* **Detecting Impact Relevant Sections in Scientific Research**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.424).  

* **Realistic Citation Count Prediction Task for Newly Published Papers**, 5.2023, *EACL Findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-eacl.84).  


### 2.2 Scientific Question Answering

* **M3SciQA: A Multi-Modal Multi-Document Scientific QA Benchmark for Evaluating Foundation Models**, 11.2024, *EMNLP Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.904/), [[Code]](https://github.com/yale-nlp/M3SciQA).  

* **DALK: Dynamic Co-Augmentation of LLMs and KG to Answer Alzheimer’s Disease Questions with Scientific Literature**, 11.2024, *EMNLP Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.119).  

* **KIWI: A Dataset of Knowledge-Intensive Writing Instructions for Answering Research Questions**, 8.2024, *ACL Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.770), [[Code]](https://www.cs.utexas.edu/~fxu/kiwi/). 

* **SciQAG: A Framework for Auto-Generated Science Question Answering Dataset with Fine-grained Evaluation**, 07.2024, arxiv,[[Paper]](https://arxiv.org/abs/2405.09939).


* **SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers**, 7.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2407.09413), [[Code]](https://github.com/google/spiqa).  

* **cPAPERS: A Dataset of Situated and Multimodal Interactive Conversations in Scientific Papers**, 6.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2406.08398), [[Code]](https://github.com/jxu81/cPAPERS?tab=readme-ov-file).  

* **A Question Answering Framework for Decontextualizing User-Facing Snippets from Scientific Documents**, 12.2023, *EMNLP Main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.193), [[Code]](https://github.com/bnewm0609/qa-decontext/tree/emnlp).  

* **Multi2Claim: Generating Scientific Claims from Multi-Choice Questions for Scientific Fact-Checking**, 5.2023, *EACL Main 2023*, [[Paper]](https://aclanthology.org/2023.eacl-main.194/), [[Code]](https://github.com/taneset/Multi2Claim).  

* **Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering**, 10.2022, *NeurIPS 2022*, [[Paper]](https://arxiv.org/abs/2209.09513), [[Code]](https://github.com/lupantech/ScienceQA), [[Dataset]](https://scienceqa.github.io/#dataset), [[Website]](https://scienceqa.github.io/#home/)  

### 2.3 Data Analysis and Visualization  

* **SciDoc2Diagrammer-MAF: Towards Generation of Scientific Diagrams from Documents Guided by Multi-Aspect Feedback Refinement**, 11.2024, *EMNLP Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.780), [[Code]](https://github.com/Ishani-Mondal/SciDoc2DiagramGeneration).  

* **Is GPT-4V(ision) All You Need for Automating Academic Data Visualization? Exploring Vision-Language Models’ Capability in Reproducing Academic Charts**, 11.2024, *EMNLP Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.485), [[Code]](https://github.com/zzh-SJTU/AcademiaChart).  

* **MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization**, 8.2024, *ACL Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.701), [[Code]](https://github.com/thunlp/MatPlotAgent). 

* **CiteME: Can Language Models Accurately Cite Scientific Claims?**, 7.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2407.12861), [[Code]](https://github.com/bethgelab/CiteME).  

* **Can Large Language Models Discern Evidence for Scientific Hypotheses? Case Studies in the Social Sciences**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.248), [[Code]](https://github.com/SaiDileepKoneru/ScientificHypothesisEvidencing).  

* **On an Intermediate Task for Classifying URL Citations on Scholarly Papers**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.1082/), [[Code]](https://github.com/matsubara-labo/URL_Citation_Classification_Intermediate).  

* **SciFIBench: Benchmarking Large Multimodal Models for Scientific Figure Interpretation**, 5.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2405.08807), [[Code]](https://github.com/jonathan-roberts1/SciFIBench).  

* **DeTikZify: Synthesizing Graphics Programs for Scientific Figures and Sketches with TikZ**, 5.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2405.15306), [[Code]](https://github.com/potamides/DeTikZify).  

* **Mapping the Increasing Use of LLMs in Scientific Papers**, 4.2024, *CoLM 2024*, [[Paper]](https://arxiv.org/abs/2404.01268).  

* **We Are Who We Cite: Bridges of Influence Between Natural Language Processing and Other Academic Fields**, 12.2023, *EMNLP Main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.797/), [[Code]](https://github.com/jpwahle/emnlp23-citation-field-influence).  


### 2.4 Research Code

* **LEGOBench: Scientific Leaderboard Generation Benchmark**, 11.2024, *EMNLP Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.855), [[Code]](https://github.com/lingo-iitgn/LEGOBench).  

* **SUPER: Evaluating Agents on Setting Up and Executing Tasks from Research Repositories**, 11.2024, *EMNLP Main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.702/), [[Code]](https://github.com/allenai/super-benchmark).  

* **ActionIE: Action Extraction from Scientific Literature with Programming Languages**, 8.2024, *ACL Main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.683/).  

### 2.5 Peer-Review

* **What Can Natural Language Processing Do for Peer Review?**, 05.2024, arxiv, [[Paper]](https://arxiv.org/abs/2405.06563).

* **Automated Peer Reviewing in Paper SEA: Standardization, Evaluation, and Analysis**, 11.2024, *EMNLP Findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.595/), [[Code]](https://github.com/ecnu-sea/sea).  

* **LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing**, 11.2024, *EMNLP Findings 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.292), [[Code]](https://github.com/jiangshdd/ReviewCritique).  

* **AgentReview: Exploring Peer Review Dynamics with LLM Agents**, 11.2024, *EMNLP Main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.70), [[Code]](https://github.com/Ahren09/AgentReview).  

* **"Quis custodiet ipsos custodes?" Who Will Watch the Watchmen? On Detecting AI-Generated Peer Reviews**, 11.2024, *EMNLP Main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.1262/), [[Code]](https://github.com/sandeep82945/AI-Review-Detection).  

* **ARIES: A Corpus of Scientific Paper Edits Made in Response to Peer Reviews**, 8.2024, *ACL Main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.377), [[Code]](https://github.com/allenai/aries).  

* **GLIMPSE: Pragmatically Informative Multi-Document Summarization for Scholarly Reviews**, 8.2024, *ACL Main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.688/).  

* **A Sentiment Consolidation Framework for Meta-Review Generation**, 8.2024, *ACL Main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.547), [[Code]](https://github.com/oaimli/MetaReviewingLogic).  

* **Is LLM a Reliable Reviewer? A Comprehensive Evaluation of LLM on Automatic Paper Reviewing Tasks**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.816), [[Code]](https://huggingface.co/datasets/zhouruiyang/RR-MCQ).

* **Automatic Analysis of Substantiation in Scientific Peer Reviews**, 12.2023, *EMNLP Findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-emnlp.684), [[Code]](https://github.com/YanzhuGuo/SubstanReview).  

* **When Reviewers Lock Horns: Finding Disagreements in Scientific Peer Reviews**, 12.2023, *EMNLP Main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.1038), [[Code]](https://github.com/sandeep82945/Contradiction-in-Peer-Review).  

* **Exploring Jiu-Jitsu Argumentation for Writing Peer Review Rebuttals**, 12.2023, *EMNLP Main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.894), [[Code]](https://github.com/UKPLab/EMNLP2023_jiu_jitsu_argumentation_for_rebuttals).  

* **Causal Matching with Text Embeddings: A Case Study in Estimating the Causal Effects of Peer Review Policies**, 7.2023, *ACL Findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-acl.83/), [[Code]](https://github.com/raymondEDS/VRM-E/).  

* **NLPeer: A Unified Resource for the Computational Study of Peer Review**, 7.2023, *ACL Main 2023*, [[Paper]](https://aclanthology.org/2023.acl-long.277), [[Code]](https://github.com/UKPLab/nlpeer).  

### 2.6 Literature Review and Summarization

* **“Rows, Columns and Values, Oh My!” Synthesizing Scientific Literature into Tables using Language Models**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.538/), [[Code]](https://github.com/bnewm0609/arxivDIGESTables).

* **SumSurvey: An Abstractive Dataset of Scientific Survey Papers for Long Document Summarization**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.574/), [[Code]](https://github.com/Oswald1997/SumSurvey).

* **CHIME: LLM-Assisted Hierarchical Organization of Scientific Studies for Literature Review Support**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.8), [[Code]](https://github.com/allenai/chime).

* **Understanding Fine-grained Distortions in Reports of Scientific Findings**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.369), [[Code]](https://www.uni-bamberg.de/en/nlproc/resources/sciencecommdistortion/).

* **What Are You Token About? Differentiable Perturbed Top-$k$ Token Selection for Scientific Document Summarization**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.561/), [[Code]](https://github.com/disi-unibo-nlp/sci-lay).

* **Large Language Models for Automated Open-domain Scientific Hypotheses Discovery**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.804), [[Code]](https://github.com/SenticNet/MOOSE).

* **Hierarchical Attention Graph for Scientific Document Summarization in Global and Local Level**, 6.2024, *NAACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-naacl.45), [[Code]](https://github.com/MoLICHENXI/HAESum).

* **Few-TK: A Dataset for Few-shot Scientific Typed Keyphrase Recognition**, 6.2024, *NAACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-naacl.253/), [[Code]](https://github.com/AvishekLahiri/Few_TK).

* **ACLSum: A New Dataset for Aspect-based Summarization of Scientific Publications**, 6.2024, *NAACL main 2024*, [[Paper]](https://aclanthology.org/2024.naacl-long.371/), [[Code]](https://github.com/sobamchan/aclsum).

* **Knowledge Triplets Derivation from Scientific Publications via Dual-Graph Resonance**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.862/).

* **Enhancing Scientific Document Summarization with Research Community Perspective and Background Knowledge**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.536/).

* **DGoT: Dynamic Graph of Thoughts for Scientific Abstract Generation**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.433), [[Code]](https://github.com/JayceNing/DGoT).

* **Longform Multimodal Lay Summarization of Scientific Papers: Towards Automatically Generating Science Blogs from Research Articles**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.942).

* **Large Language Models for Scientific Information Extraction: An Empirical Study for Virology**, 3.2024, *EACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-eacl.26/), [[Code]](https://scinext-project.github.io/#/r0-estimates).

* **Citance-Contextualized Summarization of Scientific Papers**, 12.2023, *EMNLP findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-emnlp.573/), [[Code]](https://github.com/webis-de/emnlp23-contextualized-summarization-of-scientific-papers).

* **GreedyCAS: Unsupervised Scientific Abstract Segmentation with Normalized Mutual Information**, 12.2023, *EMNLP main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.372), [[Code]](https://github.com/CharizardAcademy/GreedyCAS).

* **Improving Biomedical Abstractive Summarisation with Knowledge Aggregation from Citation Papers**, 12.2023, *EMNLP main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.40), [[Code]](https://github.com/tangg555/biomed-sum).

* **SciReviewGen: A Large-scale Dataset for Automatic Literature Review Generation**, 7.2023, *ACL findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-acl.418/), [[Code]](https://github.com/tetsu9923/SciReviewGen).

* **What are the Desired Characteristics of Calibration Sets? Identifying Correlates on Long Form Scientific Summarization**, 7.2023, *ACL main 2023*, [[Paper]](https://aclanthology.org/2023.acl-long.587), [[Code]](https://github.com/griff4692/calibrating-summaries).

* **Cross-lingual Science Journalism: Select, Simplify and Rewrite Summaries for Non-expert Readers**, 7.2023, *ACL main 2023*, [[Paper]](https://aclanthology.org/2023.acl-long.103/).

* **DiSCoMaT: Distantly Supervised Composition Extraction from Tables in Materials Science Articles**, 7.2023, *ACL main 2023*, [[Paper]](https://aclanthology.org/2023.acl-long.753), [[Code]](https://github.com/M3RG-IITD/DiSCoMaT).

* **Cogito Ergo Summ: Abstractive Summarization of Biomedical Papers via Semantic Parsing Graphs and Consistency Rewards**, 6.2023, *AAAI 2023*, [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26503), [[Code]](https://github.com/disi-unibo-nlp/cogito-ergo-summ).

* **What’s New? Summarizing Contributions in Scientific Literature**, 5.2023, *EACL main 2023*, [[Paper]](https://aclanthology.org/2023.eacl-main.72/), [[Code]](https://github.com/salesforce/disentangled-sum).


### 2.7 Writing Assistance

* **Automated Focused Feedback Generation for Scientific Writing Assistance**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.580/), [[Code]](https://github.com/ericchamoun/FocusedFeedbackGeneration).

* **Towards Real-World Writing Assistance: A Chinese Character Checking Benchmark with Faked and Misspelled Characters**, 8.2024, *ACL main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.469/), [[Code]](https://github.com/THUKElab/Visual-C3).

* **Doolittle: Benchmarks and Corpora for Academic Writing Formalization**, 12.2023, *EMNLP main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.809/), [[Code]](https://github.com/shizhediao/Doolittle).

* **Smart Word Suggestions for Writing Assistance**, 7.2023, *ACL findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-acl.712/), [[Code]](https://github.com/microsoft/SmartWordSuggestions).


### 2.8 Idea and Novelty Generation

* **SciMON: Scientific Inspiration Machines Optimized for Novelty**, 8.2024, *ACL main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.18/), [[Code]](https://github.com/EagleW/Scientific-Inspiration-Machines-Optimized-for-Novelty).

* **Exploring and Verbalizing Academic Ideas by Concept Co-occurrence**, 7.2023, *ACL main 2023*, [[Paper]](https://aclanthology.org/2023.acl-long.727), [[Code]](https://github.com/xyjigsaw/Kiscovery).

### 2.9 Representation Learning

* **Co-training for Low Resource Scientific Natural Language Inference**, 8.2024, *ACL main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.139).

* **HDT: Hierarchical Document Transformer**, 7.2024, *CoLM 2024*, [[Paper]](https://arxiv.org/abs/2407.08330), [[Code]](https://github.com/autonomousvision/hdt).

* **Pre-training Multi-task Contrastive Learning Models for Scientific Literature Understanding**, 12.2023, *EMNLP findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-emnlp.820), [[Code]](https://github.com/yuzhimanhua/SciMult).

* **SciRepEval: A Multi-Format Benchmark for Scientific Document Representations**, 12.2023, *EMNLP main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.338/), [[Code]](https://github.com/allenai/scirepeval).

* **Content- and Topology-Aware Representation Learning for Scientific Multi-Literature**, 12.2023, *EMNLP main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.465/), [[Code]](https://github.com/MatthewKKai/SMRC2).

* **Are Layout-Infused Language Models Robust to Layout Distribution Shifts? A Case Study with Scientific Documents**, 7.2023, *ACL findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-acl.844), [[Code]](https://github.com/cchen23/layout_distribution_shift).

* **MIReAD: Simple Method for Learning High-quality Representations from Scientific Documents**, 7.2023, *ACL main 2023*, [[Paper]](https://aclanthology.org/2023.acl-short.46), [[Code]](https://github.com/arazd/miread).

<div align="right">
    <b><a href="#contents">👉 back to top</a></b>
</div>

## 3. Techniques

### 3.1 Prompt Engineering

* **SciPrompt: Knowledge-augmented Prompting for Fine-grained Categorization of Scientific Topics**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.350), [[Code]](https://github.com/zhiwenyou103/SciPrompt).

* **Chain-of-Thought Improves Text Generation with Citations in Large Language Models**, 3.2024, *AAAI 2024*, [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29794).

### 3.2 Few-Shot Learning

* **Impact of Sample Selection on In-Context Learning for Entity Extraction from Scientific Writing**, 12.2023, *EMNLP findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-emnlp.338), [[Code]](https://github.com/adalin16/ICL_EE).

### 3.3 Single Agent

* **Efficient Performance Tracking: Leveraging Large Language Models for Automated Construction of Scientific Leaderboards**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.453), [[Code]](https://github.com/UKPLab/emnlp2024-leaderboard-generation).

### 3.4 RAG

* **Knowledge Navigator: Hierarchical Subtopic Organization for Exploratory Search in Scientific Literature**, 11.2024, *EMNLP findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.516), [[Code]](https://github.com/katzurik/Knowledge_Navigator).

* **MixGR: Enhancing Retriever Generalization for Scientific Domain through Complementary Granularity**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.579/), [[Code]](https://github.com/TRUMANCFY/MixGR).

* **Taxonomy-guided Semantic Indexing for Academic Paper Search**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.407).


<div align="right">
    <b><a href="#contents">👉 back to top</a></b>
</div>

## 4. Dataset

* **The Multimodal Universe: Enabling Large-Scale Machine Learning with 100TBs of Astronomical Scientific Data**, 12.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2412.02527), [[Code]](https://github.com/MultimodalUniverse/MultimodalUniverse).

* **Are Large Language Models Good Classifiers? A Study on Edit Intent Classification in Scientific Document Revisions**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.839/), [[Code]](https://github.com/UKPLab/emnlp2024-llm-classifier).

* **LitSearch: A Retrieval Benchmark for Scientific Literature Search**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.840/), [[Code]](https://github.com/princeton-nlp/LitSearch).

* **SciDQA: A Deep Reading Comprehension Dataset over Scientific Papers**, 11.2024, *EMNLP main 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-main.1163/), [[Code]](https://github.com/yale-nlp/SciDQA).

* **SciER: An Entity and Relation Extraction Dataset for Datasets, Methods, and Tasks in Scientific Documents**, 10.2024, *EMNLP main 2024*, [[Paper]](https://arxiv.org/abs/2410.21155), [[Code]](https://github.com/edzq/SciER).

* **SciMMIR: Benchmarking Scientific Multi-modal Information Retrieval**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.746), [[Code]](https://github.com/Wusiwei0410/SciMMIR).

* **Multimodal ArXiv: A Dataset for Improving Scientific Comprehension of Large Vision-Language Models**, 8.2024, *ACL main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.775/), [[Code]](https://mm-arxiv.github.io/).

* **M3AV: A Multimodal, Multigenre, and Multipurpose Audio-Visual Academic Lecture Dataset**, 8.2024, *ACL main 2024*, [[Paper]](https://aclanthology.org/2024.acl-long.489/), [[Code]](https://github.com/Jack-ZC8/M3AV-dataset).

* **MSciNLI: A Diverse Benchmark for Scientific Natural Language Inference**, 6.2024, *NAACL main 2024*, [[Paper]](https://aclanthology.org/2024.naacl-long.90/), [[Code]](https://github.com/msadat3/MSciNLI).

* **POLYIE: A Dataset of Information Extraction from Polymer Material Scientific Literature**, 6.2024, *NAACL main 2024*, [[Paper]](https://aclanthology.org/2024.naacl-long.131), [[Code]](https://github.com/jerry3027/PolyIE).

* **SciNews: From Scholarly Complexities to Public Narratives -- A Dataset for Scientific News Report Generation**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.1258/).

* **SciDMT: A Large-Scale Corpus for Detecting Scientific Mentions**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.1256).

* **OpenMSD: Towards Multilingual Scientific Documents Similarity Measurement**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.1092), [[Code]](https://github.com/google-research/google-research/tree/master/OpenMSD).

* **CASIMIR: A Corpus of Scientific Articles Enhanced with Multiple Author-Integrated Revisions**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.257).

* **SciMRC: Multi-perspective Scientific Machine Reading Comprehension**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.1257/).

* **PEaCE: A Chemistry-Oriented Dataset for Optical Character Recognition on Scientific Documents**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.1110/), [[Code]](https://github.com/ZN1010/PEaCE).

* **Recommending Missed Citations Identified by Reviewers: A New Task, Dataset and Baselines**, 5.2024, *Coling 2024*, [[Paper]](https://aclanthology.org/2024.lrec-main.1196), [[Code]](https://github.com/ChainsawM/RMC).

* **SciInstruct: A Self-Reflective Instruction Annotated Dataset for Training Scientific Language Models**, 1.2024, *NeurIPS 2024*, [[Paper]](https://arxiv.org/abs/2401.07950), [[Code]](https://github.com/THUDM/SciGLM).

* **GSAP-NER: A Novel Task, Corpus, and Baseline for Scholarly Entity Extraction Focused on Machine Learning Models and Datasets**, 12.2023, *EMNLP findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-emnlp.548), [[Code]](https://github.com/ottowg/gsap-ner).

* **CiteBench: A Benchmark for Scientific Citation Text Generation**, 12.2023, *EMNLP main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.455), [[Code]](https://github.com/UKPLab/citebench).

* **SCITAB: A Challenging Benchmark for Compositional Reasoning and Claim Verification on Scientific Tables**, 12.2023, *EMNLP main 2023*, [[Paper]](https://aclanthology.org/2023.emnlp-main.483), [[Code]](https://github.com/XinyuanLu00/SciTab).

* **Scientific Document Retrieval using Multi-level Aspect-based Queries**, 10.2023, *NeurIPS 2023*, [[Paper]](https://arxiv.org/abs/2310.04678), [[Code]](https://github.com/kwang927/Doris-Mae-Dataset).

* **A Dataset of Argumentative Dialogues on Scientific Papers**, 7.2023, *ACL main 2023*, [[Paper]](https://aclanthology.org/2023.acl-long.425/), [[Code]](https://github.com/UKPLab/acl2023-argscichat).

<div align="right">
    <b><a href="#contents">👉 back to top</a></b>
</div>

## 5. Evaluation

* **On the Rigour of Scientific Writing: Criteria, Analysis, and Insights**, 11.2024, *EMNLP findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-emnlp.380).

* **Toward Reliable Ad-hoc Scientific Information Extraction: A Case Study on Two Materials Dataset**, 8.2024, *ACL findings 2024*, [[Paper]](https://aclanthology.org/2024.findings-acl.897/), [[Code]](https://github.com/SatanuG/ad_hoc_information_extraction).

* **Evaluating Unsupervised Argument Aligners via Generation of Conclusions of Structured Scientific Abstracts**, 3.2024, *EACL main 2024*, [[Paper]](https://aclanthology.org/2024.eacl-short.14).

* **GPT-4 as an Effective Zero-Shot Evaluator for Scientific Figure Captions**, 12.2023, *EMNLP findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-emnlp.363).

* **SciEval: A Multi-Level Large Language Model Evaluation Benchmark for Scientific Research**, 8.2023, *AAAI 2024*, [[Paper]](https://arxiv.org/abs/2308.13149), [[Code]](https://github.com/OpenDFM/SciEval).

* **Words as Gatekeepers: Measuring Discipline-specific Terms and Meanings in Scholarly Publications**, 7.2023, *ACL findings 2023*, [[Paper]](https://aclanthology.org/2023.findings-acl.433), [[Code]](https://github.com/lucy3/words_as_gatekeepers).

* **MatSci-NLP: Evaluating Scientific Language Models on Materials Science Language Tasks Using Text-to-Schema Modeling**, 7.2023, *ACL main 2023*, [[Paper]](https://aclanthology.org/2023.acl-long.201), [[Code]](https://github.com/BangLab-UdeM-Mila/NLP4MatSci-ACL23).

* **Task-Oriented**: Evaluate models on specific research tasks (e.g., summarization, QA).
* **General Metrics**: Assess LLMs using metrics like BLEU, ROUGE, and F1-score.

<div align="right">
    <b><a href="#contents">👉 back to top</a></b>
</div>

## 6. Platforms

* **NLP-KG: A System for Exploratory Search of Scientific Literature in Natural Language Processing**, 8.2024, *ACL demo 2024*, [[Paper]](https://aclanthology.org/2024.acl-demos.13), [[Code]](https://github.com/NLP-Knowledge-Graph/NLP-KG-WebApp).

* **GenGO: ACL Paper Explorer with Semantic Features**, 8.2024, *ACL demo 2024*, [[Paper]](https://aclanthology.org/2024.acl-demos.12/), [[Code]](https://gengo.sotaro.io/).

* **OpenResearcher: Unleashing AI for Accelerated Scientific Research**, 3.2024, *EMNLP demo 2024*, [[Paper]](https://aclanthology.org/2024.emnlp-demo.22), [[Code]](https://github.com/GAIR-NLP/OpenResearcher).

* [Galactica](https://galactica.org/explore/): A platform for scientific discovery.
* [FutureHouse: Automating scientific discovery](https://www.futurehouse.org/): For Paper QA, topic search, and more.

### 6.1 Personalized Recommendation


### 6.2 PaperChat


### 6.3 Writing Assistant


### 6.4 Search Engine


### 6.4 Integrated


<div align="right">
    <b><a href="#contents">👉 back to top</a></b>
</div>

## 7. Workshops and Tutorials

* Scholarly Document Processing


* SDU@AAAI


* Foundation Models for Science: Progress, Opportunities, and Challenges @ NeurIPS 2024


<div align="right">
    <b><a href="#contents">👉 back to top</a></b>
</div>

---

## Contributions

We welcome contributions from the community! If you know of any useful tools, techniques, or resources related to LLMs as research assistants, feel free to submit a pull request, open an issue, or email (yongcao2018@gmail.com) to add links.

---