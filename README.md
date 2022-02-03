# Awesome Software Engineering Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of software engineering research, data sets and tools. Inspired by [awesome-msr](https://github.com/dspinellis/awesome-msr) project.

## Contents
- [PapersWithCode](#paperswithcode)
  - [Stack Overflow](#stack-overflow)
  - [API Recommendation](#api-recommendation)
  - [Method Name Generation](#method-name-generation)
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


### Query Refinement/Expansion
  - [Chatbot4QR](https://osf.io/npwg4/?view_only=560f6453f31a439db469d7fe4c82dbec). Chatbot4QR: Interactive Query Refinement for Technical Question Retrieval. [paper](https://ieeexplore.ieee.org/document/9165927). 


## Data Sets
Collecting a list of data sets, benchmarks for different tasks.
### Microservice System
 - [Train Ticket：A Benchmark Microservice System](https://github.com/FudanSELab/train-ticket). The project is a train ticket booking system based on microservice architecture which contains 41 microservices. This project is maintained by the CodeWidom team of Fudan University.

### Code-Related Task Benchmark
  - [CodeXGLUE](https://github.com/microsoft/CodeXGLUE) - A benchmark dataset and open challenge for code intelligence. It includes 14 datasets for 10 diversified code intelligence tasks covering the following scenarios: 1) code-code (clone detection, defect detection, cloze test, code completion, code repair, and code-to-code translation); 2) text-code (natural language code search, text-to-code generation); 3) code-text (code summarization); 4) text-text (documentation translation). 
  - [Project CodeNet](https://github.com/IBM/Project_CodeNet), The goal of Project CodeNet is to provide the AI-for-Code research community with a large scale, diverse, and high quality curated dataset to drive innovation in AI techniques. Project CodeNet is a large scale dataset with approximately 14 million code samples, each of which is an intended solution to one of 4000 coding problems. Project CodeNet aims to do for AI for Code what ImageNet did for computer vision.
  - 
### Bug Localization
  - [EMSE Bug Location Data Set](https://seers.utdallas.edu/projects/emse-query-reformulation/#), from paper "Using Bug Descriptions to Reformulate Queries during Text-Retrieval-based Bug Localization" by Oscar Chaparro, Juan Manuel Florez, Andrian Marcus.
  - [DeepLocalize](https://github.com/Wardat-ISU/DeepLocalize), DeepLocalize: Fault Localization for Deep Neural Networks. This repo includes a bechmark.

### API Misuse
   - [MUBench](https://github.com/stg-tud/MUBench), MUBench (pronounced "Moo Bench") is an automated benchmark for API-misuse detectors, based on the MUBench benchmarking dataset. If you encounter any problems using MUBench, please report them to us. If you have any questions, please contact Sven Amann.
   - [CryptoAPI-Bench](https://github.com/CryptoGuardOSS/cryptoapi-bench): A Comprehensive Benchmark on Java Cryptographic API Misuses

### API Recommendation
  - [BIKER](https://github.com/tkdsheep/BIKER-ASE2018), The dataset and source code for paper "API Method Recommendation without Worrying About the Task-API Knowledge Gap", ASE, [Paper](https://dl.acm.org/doi/10.1145/3238147.3238191), including about 400 API retrieval tasks from Stack Overflow.
  
### Feature Location
  - [Deny Benchmark on Feature Location](http://www.cs.wm.edu/semeru/data/benchmarks/), from JSEP 2013 "Feature Location in Source Code-A Taxonomy and Survey". It provides ArgoUML，Eclipse，JabRef ，jEdit ，muCommander feaure location data sets.

### API Review Classification
  - https://github.com/soarsmu/PTM4SE

###  Annotation Recommendation 
  - [Java-Annotation-Study](https://github.com/zhongxingyu/Java-Annotation-Study), This repository contains our code for studying Java annotation and its evolution, the collected large scale data about evolution of annotations in three years for each project, and our manual analysis of the characteristics of annotation evolution.

### Others
  - [Stack Exchange](https://archive.org/details/stackexchange) - Anonymized dump of all user-contributed content on the Stack Exchange network.
  - [AwesomeList](https://github.com/lockys/Awesome.json), awesome lists data in json format.

## Tools
  Tools that could be used in SE research
  
- [PyDriller](https://github.com/ishepard/pydriller) - Python Framework to analyse Git repositories.
- [GrimoireLab](https://github.com/chaoss/grimoirelab) - Toolset for software development analytics. By far the best set of tools to mine software repositories.

## Tutorials
- [msrWS](https://github.com/dmgerman/msrWS) - Tutorials about how to mine github repository, including some pdfs.

## Other Resource Lists
- [awesome-machine-learning-on-source-code](https://github.com/src-d/awesome-machine-learning-on-source-code), Cool links & research papers related to Machine Learning applied to source code (MLonCode)

## Contributing
- This list requires your input for its continuous improvement.
  Read the [contribution guide](contributing.md) for instructions on how
  you can contribute.
  Alternatively, you can send me an [email](lmwtclmwtc@outlook.com)
  if you find the process too cumbersome or confusing.
- For more awesome lists, see [awesome](https://github.com/sindresorhus/awesome).

