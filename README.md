# A Paper Repository on DBMS Tuning 

General DBMS and LSM-Tree-based KV stores.

## Introduction

This repository provides a curated collection of research papers on two main topics: general DBMS tuning and tuning of LSM-tree-based key-value stores. The latter includes structural optimizations of LSM-trees as a core subtopic. 

## Table of Content

- [Introduction](#Introduction)
- [General DBMS Tuning Papers](#general-dbms-tuning-papers)
  - [Survey](#survey)
  - [Heuristic-based](#heuristic-based)
  - [Bayesian Optimization-based](#bayesian-optimization-based)
  - [Reinforcement Learning-based](#reinforcement-learning-based)
  - [Large Language Model Assisted](#large-language-model-assisted)
- [LSM-tree-based KV Store Tuning Papers](#lsm-tree-based-kv-store-tuning-papers)
  - [Structural Tuning of LSM-trees](#structural-tuning-of-lsm-trees)



## General DBMS Tuning Papers

### Survey

1. Automatic Database Knob Tuning: A Survey ([PDF](https://dl.acm.org/doi/10.1109/TKDE.2023.3266893)) [TKDE 2023]
2. 数据库参数配置智能调优研究综述 ([PDF](http://cjc.ict.ac.cn/online/onlinepaper/lyy-2024729180804.pdf)) [计算机学报 2024]
3. Facilitating database tuning with hyper-parameter optimization: a comprehensive experimental evaluation ([PDF](https://dl.acm.org/doi/10.14778/3538598.3538604)) [VLDB 2022]

### Heuristic-based

1. Automatic Configuration for IBM ® DB 2 Universal Database TM Compressing years of performance tuning experience into seconds of execution ([PDF](https://api.semanticscholar.org/CorpusID:15267980)) [02]
2. OpenTuner: An Extensible Framework for Program Autotuning ([PDF](https://doi.org/10.1145/2628071.2628092)) [PACT 14]
3. BestConfig: Tapping the Performance Potential of Systems via Automatic Configuration Tuning ([PDF](https://doi.org/10.1145/3127479.3128605)) [SoCC 17]

### Bayesian Optimization-based

1. Tuning Database Configuration Parameters with ITuned ([PDF](https://doi.org/10.14778/1687627.1687767)) [VLDB 09]
2. Automatic Database Management System Tuning Through Large-scale Machine Learning ([PDF](https://dl.acm.org/doi/10.1145/3035918.3064029)) [VLDB 17] [GitHub](https://github.com/cmu-db/ottertune)
3. Black or White? How to Develop an AutoTuner for Memory-Based Analytics ([PDF](https://doi.org/10.1145/3318464.3380591)) [SIGMOD 20]
4. CGPTuner: A Contextual Gaussian Process Bandit Approach for the Automatic Tuning of IT Configurations under Varying Workload Conditions ([PDF](https://doi.org/10.14778/3457390.3457404)) [VLDP 21]
5. ResTune: Resource Oriented Tuning Boosted by MetaLearning for Cloud Databases ([PDF](https://doi.org/10.1145/ 3448016.3457291)) [SIGMOD 21]
6. Towards Dynamic and Safe Configuration Tuning for Cloud Databases ([PDF](https://doi.org/10.1145/3514221.3526176)) [SIGMOD 22]
7. LlamaTune: sample-efficient DBMS configuration tuning ([PDF](https://doi.org/10.14778/3551793.3551844)) [VLDB 22]

### Reinforcement Learning-based

1. An End-to-End Automatic Cloud Database Tuning System Using Deep Reinforcement Learning ([PDF](https://doi.org/10.1145/3299869.3300085)) [SIGMOD 19]
2. QTune: A Query-Aware Database Tuning System with Deep Reinforcement Learning ([PDF](https://doi.org/10.14778/3352063.3352129)) [VLDB 19]
3. UDO: universal database optimization using reinforcement learning ([PDF](https://doi.org/10.14778/3484224.3484236)) [VLDB 21]
4. HUNTER: An Online Cloud Database Hybrid Tuning System for Personalized Requirements ([PDF](https://doi.org/10.1145/3514221.3517882)) [SIGMOD 22]

### Large Language Model Assisted

1. DB-BERT: A Database Tuning Tool that “Reads the Manual” ([PDF](https://doi.org/10.1145/3514221.3517843)) [SIGMOD 22] 
2. GPTuner: A Manual-Reading Database Tuning System via GPT-Guided Bayesian Optimization ([PDF](https://doi.org/10.14778/3659437.3659449)) [VLDB 24] 
3. E2ETune: End-to-End Knob Tuning via Fine-tuned Generative Language Model ([PDF](https://arxiv.org/abs/2404.11581)) [VLDB 25]
4.  $\lambda$ -Tune: Harnessing Large Language Models for Automated Database System Tuning ([PDF](https://doi.org/10.1145/3709652)) [SIGMOD 25]

## LSM-tree-based KV Store Tuning Papers

1. RocksDB: RocksDB Tuning Guide. [edited on 23] [Github](https://github.com/facebook/rocksdb/wiki/RocksDB-Tuning-Guide) 
2. Dremel: Adaptive Configuration Tuning of RocksDB KV-Store ([PDF](https://doi.org/10.1145/3489048.3530970)) [SIGMETRICS/PERFORMANCE 22]
3. Endure: A Robust Tuning Paradigm for LSM Trees Under Workload Uncertainty ([PDF](https://doi.org/10.14778/3529337.3529345)) [VLDB 22]
4. Can Modern LLMs Tune and Configure LSM-based Key-Value Stores? ([PDF](https://doi.org/10.1145/3655038.3665954)) [HOTSTORAGE 24]
5. RTune: A RocksDB Tuning System with Deep Genetic Algorithm ([PDF](https://doi.org/10.1145/3512290.3528726)) [GECCO 24]



### Structural Tuning of LSM-trees

Hybrid merging policies with more fine-grained tunings

Optimized memory allocation strategies

Variations of Bloom Filters

New compaction routines

Exploitation of data characteristics 