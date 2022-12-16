# Awesome Software Engineering Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of software engineering research, data sets and tools. Inspired by [awesome-msr](https://github.com/dspinellis/awesome-msr) project.

## Contents
- [PapersWithCode](#paperswithcode)
  - [Stack Overflow](#stack-overflow)
  - [API Recommendation](#api-recommendation)
  - [Method Name Generation](#method-name-generation)
  - [Documentation Bad Smell](#documentation-bad-smell)
  - [Query Refinement/Expansion](#query-refinement/expansion)
  
- [Data Sets](#data-sets)
  - [Code-Related Task Benchmark](#code-related-task-benchmark)
  - [Bug Localization](#bug-localization)
  - [API Misuse](#api-misuse)
  - [Feature Location](#feature-location)
  
- [Tools](#tools)
- [Tutorials](#tutorials)

## PapersWithCode
Collecting a list of papers with code implementations, which could be used as baselines.

### Stack Overflow
  - [AnswerBot](https://github.com/XBWer/AnswerBot.git), Replication package of the paper "AnswerBot: An Answer Summary Generation Tool Based on Stack Overflow", ESEC/FSE 2019, [Paper](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5491&context=sis_research)

### API Recommendation
  - [BIKER](https://github.com/tkdsheep/BIKER-ASE2018), The dataset and source code for paper "API Method Recommendation without Worrying About the Task-API Knowledge Gap", ASE, [Paper](https://dl.acm.org/doi/10.1145/3238147.3238191), including about 400 API retrieval tasks from Stack Overflow.


### Method Name Generation
  - [debug-method-name-2019-ICSE](https://github.com/SerVal-DTF/debug-method-name), A tool of spotting and refactoring inconsistent method names learned from real-world code bases. This work will be presented at ICSE 2019. This reincluding data with .
  - [DeepName-2021-ICSE](https://github.com/deepname2021icse/DeepName-2021-ICSE), This repository contains the code and dataset for A Context-based Automated Approach for Method Name Consistency Checking and Suggestion.

### Documentation Bad Smell
  - [DocSmell Benchmark](https://github.com/disa-lab/SANER2021-DocSmell)，benchmark dataset of 1000 documentations with these 5 types of smells.
  
### Query Refinement/Expansion
  - [Chatbot4QR](https://osf.io/npwg4/?view_only=560f6453f31a439db469d7fe4c82dbec). Chatbot4QR: Interactive Query Refinement for Technical Question Retrieval. [paper](https://ieeexplore.ieee.org/document/9165927). 


## Data Sets and Benchmarks
Collecting a list of data sets, benchmarks for different tasks.
### Code Language
  - [Code-LMs](https://github.com/VHellendoorn/Code-LMs), include a 249GB multi-lingual code corpus used to train language model and some pretrained language model for code, e.g., GPT-2, PolyCoder. [Paper](https://arxiv.org/pdf/2202.13169.pdf).

### Test Oracle Generation
  - [Toga](https://github.com/microsoft/toga). This repository contains the replication artifact for TOGA: A Neural Method for Test Oracle Generation to appear in ICSE 2022.

### Microservice System
 - [Train Ticket：A Benchmark Microservice System](https://github.com/FudanSELab/train-ticket). The project is a train ticket booking system based on microservice architecture which contains 41 microservices. This project is maintained by the CodeWidom team of Fudan University.

### NL-based Code Search
  - [facebook Neural-Code-Search-Evaluation-Dataset](https://github.com/facebookresearch/Neural-Code-Search-Evaluation-Dataset),Code Search Dataset from FaceBook: H. Li, S. Kim, and S. Chandra, “Neural code search evaluation dataset,” ArXiv, vol. abs/1908.09804, 2019
  - [codesearchnet](https://github.com/github/codesearchnet), Code Search Dataset from Github & Microsoft: H. Husain, H.-H. Wu, T. Gazit, M. Allamanis, and M. Brockschmidt, “Codesearchnet challenge: Evaluating the state of semantic code search,” ArXiv, vol. abs/1909.09436, 2019, github/codesearchnet.
  - [CosBench](https://github.com/BASE-LAB-SJTU/CosBench), 52 queries and corresponding answers from 4,199,769 java snippets.

### API Usage Pattern Recommendation
  - [FOCUS](https://github.com/crossminer/FOCUS/tree/ICSE19-artifact-evaluation), FOCUS is a context-aware collaborative-filtering system that exploits cross relationships among OSS projects to suggest the inclusion of additional API invocations and concrete API usage patterns. Paper: "FOCUS: A Recommender System for Mining API Function Calls and Usage Patterns".

Authors: Phuong T. Nguyen, Juri Di Rocco, Davide Di Ruscio, Lina Ochoa, Thomas Degueule, and Massimiliano Di Penta

### Code-Related Task Benchmark
  - [CodeXGLUE](https://github.com/microsoft/CodeXGLUE) - A benchmark dataset and open challenge for code intelligence. It includes 14 datasets for 10 diversified code intelligence tasks covering the following scenarios: 1) code-code (clone detection, defect detection, cloze test, code completion, code repair, and code-to-code translation); 2) text-code (natural language code search, text-to-code generation); 3) code-text (code summarization); 4) text-text (documentation translation). 
  - [Project CodeNet](https://github.com/IBM/Project_CodeNet), The goal of Project CodeNet is to provide the AI-for-Code research community with a large scale, diverse, and high quality curated dataset to drive innovation in AI techniques. Project CodeNet is a large scale dataset with approximately 14 million code samples, each of which is an intended solution to one of 4000 coding problems. Project CodeNet aims to do for AI for Code what ImageNet did for computer vision.
### Library-Oriented Code Generation
   - [PyCodeGPT](https://github.com/microsoft/PyCodeGPT), from paper [CERT: Continual Pre-Training on Sketches for Library-Oriented Code Generation
](https://arxiv.org/abs/2206.06888). Providing two benchmark: PandasEval and NumpyEval.

### Bug Localization
  - [EMSE Bug Location Data Set](https://seers.utdallas.edu/projects/emse-query-reformulation/#), from paper "Using Bug Descriptions to Reformulate Queries during Text-Retrieval-based Bug Localization" by Oscar Chaparro, Juan Manuel Florez, Andrian Marcus.
  - [DeepLocalize](https://github.com/Wardat-ISU/DeepLocalize), DeepLocalize: Fault Localization for Deep Neural Networks. This repo includes a bechmark.
  - [TSSB-3M](https://github.com/cedricrupb/TSSB3M), mining tool and large-scale datasets of single statement bug fixes in Python.
     - Paper:  TSSB-3M: Mining single statement bugs at massive scale
     - TSSB-3M: A dataset of over 3 million isolated single statement bug fixes. Each bug fix is related to a commit in a public Python that does not change more than a single statement.
     - SSB-9M: A dataset of over 9 million single statement bug fixes. Each fix modifies at least a single statement to fix a bug. However, the related code changes might incorporate changes to other files.
     - SSC-28M: A dataset of over 28 million general single statement changes. We are releasing this dataset with the intention to faciliate research in software evolution. Therefore, a code change might not necessarily relate to a bug fix.

### API Misuse
   - [MUBench](https://github.com/stg-tud/MUBench), MUBench (pronounced "Moo Bench") is an automated benchmark for API-misuse detectors, based on the MUBench benchmarking dataset. If you encounter any problems using MUBench, please report them to us. If you have any questions, please contact Sven Amann.
   - [CryptoAPI-Bench](https://github.com/CryptoGuardOSS/cryptoapi-bench): A Comprehensive Benchmark on Java Cryptographic API Misuses

### Variable Misuee
   - [great](https://github.com/google-research-datasets/great), [ICLR20-Great](https://github.com/VHellendoorn/ICLR20-Great),, the dataset for the variable-misuse task, described in the ICLR 2020 paper 'Global Relational Models of Source Code' [https://openreview.net/forum?id=B1lnbRNtwr]. This repository contains the data and code to replicate our ICLR 2020 paper on models of source code that combine global and structural information, including the Graph-Sandwich model family and the GREAT (Graph-Relational Embedding Attention Transformer) model.

### Programming-Language Understanding and Repair
   - [PLUR](https://github.com/google-research/plur), PLUR (Programming-Language Understanding and Repair) is a collection of source code datasets suitable for graph-based machine learning. We provide scripts for downloading, processing, and loading the datasets. This is done by offering a unified API and data structures for all datasets.
   - 
### API Recommendation
  - [BIKER](https://github.com/tkdsheep/BIKER-ASE2018), The dataset and source code for paper "API Method Recommendation without Worrying About the Task-API Knowledge Gap", ASE, [Paper](https://dl.acm.org/doi/10.1145/3238147.3238191), including about 400 API retrieval tasks from Stack Overflow.
  
### Feature Location
  - [Deny Benchmark on Feature Location](http://www.cs.wm.edu/semeru/data/benchmarks/), from JSEP 2013 "Feature Location in Source Code-A Taxonomy and Survey". It provides ArgoUML，Eclipse，JabRef ，jEdit ，muCommander feaure location data sets.

### API Review Classification
  - https://github.com/soarsmu/PTM4SE

###  Annotation Recommendation 
  - [Java-Annotation-Study](https://github.com/zhongxingyu/Java-Annotation-Study), This repository contains our code for studying Java annotation and its evolution, the collected large scale data about evolution of annotations in three years for each project, and our manual analysis of the characteristics of annotation evolution.

### Bug Fix
  - [TSSB3M](https://github.com/cedricrupb/TSSB3M), including three dataset for python code. 
    - TSSB-3M: A dataset of over 3 million isolated single statement bug fixes. Each bug fix is related to a commit in a public Python that does not change more than a single statement.
    - SSB-9M: A dataset of over 9 million single statement bug fixes. Each fix modifies at least a single statement to fix a bug. However, the related code changes might incorporate changes to other files.
    - SSC-28M: A dataset of over 28 million general single statement changes. We are releasing this dataset with the intention to faciliate research in software evoluation. Therefore, a code change might not necessarily relate to a bug fix.
    - [nbfbaselines](https://github.com/cedricrupb/nbfbaselines), Neural baselines for finding and fixing single token bugs in Python, [paper](https://arxiv.org/pdf/2207.00301.pdf), "Can we learn from developer mistakes? Learning to localize and repair real bugs from real bug fixes".




### Code Diff
  - [Code Diff Datasets](https://github.com/GumTreeDiff/datasets), A collection of diff datasets. It contains: Defects4J, BugsInPy, and unparsable.

### Others
  - [Stack Exchange](https://archive.org/details/stackexchange) - Anonymized dump of all user-contributed content on the Stack Exchange network.
  - [AwesomeList](https://github.com/lockys/Awesome.json), awesome lists data in json format.
  
## Tools
  Tools that could be used in SE research
  
- [PyDriller](https://github.com/ishepard/pydriller) - Python Framework to analyse Git repositories.
- [GrimoireLab](https://github.com/chaoss/grimoirelab) - Toolset for software development analytics. By far the best set of tools to mine software repositories.

### Code Analysis
 - [code_diff](https://github.com/cedricrupb/code_diff), Fast AST based code differencing in Python
 - [code_tokenize](https://github.com/cedricrupb/code_tokenize), Fast tokenization and structural analysis of any programming language

## Tutorials
- [msrWS](https://github.com/dmgerman/msrWS) - Tutorials about how to mine github repository, including some pdfs.

## Other Resource Lists
- [awesome-machine-learning-on-source-code](https://github.com/src-d/awesome-machine-learning-on-source-code), Cool links & research papers related to Machine Learning applied to source code (MLonCode)
- [CUHK-ARISE/ml4code-dataset](https://github.com/CUHK-ARISE/ml4code-dataset), a collection of datasets for machine learning for big code.
- SE4I
  - [SE4AI Course](https://github.com/ckaestne/seai)
  - [SE4AI Papers](https://github.com/ckaestne/seaibib)
  - [ML4Code](https://ml4code.github.io/papers.html)
  - [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets)
  - [awesome-machine-learning-on-source-code](https://github.com/src-d/awesome-machine-learning-on-source-code)
- [huggingface dataset](https://github.com/huggingface/datasets/tree/master/datasets)
- Papers using Stack Overflow data
  - [academic-papers-using-stack-exchange-data](https://meta.stackexchange.com/questions/134495/academic-papers-using-stack-exchange-data)
  - [Has-there-been-any-academic-research-using-Stack-Overflow-or-Stack-Exchange](https://www.quora.com/Has-there-been-any-academic-research-using-Stack-Overflow-or-Stack-Exchange)
- [Open Research Datasets in Software Engineering](http://www.cc.uah.es/drg/c/RHH_RAISE12_Repos.html)  

## Contributing
- This list requires your input for its continuous improvement.
  Read the [contribution guide](contributing.md) for instructions on how
  you can contribute.
  Alternatively, you can send me an [email](lmwtclmwtc@outlook.com)
  if you find the process too cumbersome or confusing.
- For more awesome lists, see [awesome](https://github.com/sindresorhus/awesome).

