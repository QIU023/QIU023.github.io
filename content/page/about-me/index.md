---
title: "About Me"
description: "Curriculum Vitae"
date: "2022-12-11"
slug: "about-me"
menu:
  main:
    weight: -90
    params:
      icon: user
---

# Education

- Master of Science in Computer Science and Engineering, University of California, San Diego, September 2022-Dec 2023
- Bachelor of Engineering in Computer Science and Technology, Sun-Yat sen University, September 2018-June 2022

# Work Experience

- **Video Algorithms Engineer Intern**, ByteDance, _November 2021-April 2022_

  - Built and Optimization of the architecture of DNNs for real-time Video Super-Resolution(SR) and Facial Landmark Detection. Got 43% improvement of the PSNR gain for SR and 67% decreasing for NME loss for Landmark in offline and online testing (SR:2M images, Landmark:100k images).
  - C++ Development of Multi-Frame path in SR node and Landmark Detection node in ByteDance RTC video engine, including using multi-threads concurrency and sharing memory buffers for communication, accelerated Multi-Frame SR processing by 2.3 times faster than trivial ”for-loop”. Together with previous trained DNN models being used in live streaming in Douyin, Tiktok and Lark.
  - Using Android Studio and CMake to compile and run Unit-Tests APP for RTC engine on Android devices.
  - Surveyed and reproduced four baselines for Image Matting.

- **Computer Vision Research Intern**, DMAI, _July 2021-October 2021_
  - Optimized lite models for Detection & Classification, and OpenSet Recognition applied, optimize test mAP to 99.5% for cards detection, and solve 95% bad cases, achieved 99% test precision for cards classification.
  - Development of a PyTorch based Distributed Generalized Training pipeline(pip install dldtrainer), widely used in DMAI research center to simplify the procedure of developing new DNN models.

# Publications

- **SATS: Self-Attention Transfer for Continual Semantic Segmentation**
  - Published in Journal: Pattern Recognition, as the 1st author, available at [arXiv](https://arxiv.org/abs/2203.07667). 
  <!-- - Explore self-attention mechanism application on Continual Semantic Segmentation, to keep learning new classes and remember old classes, got SOTA result.   -->
  
- **TDAN: Topic Driven Adaptive Network for Cross-Domain Sentiment Classification**
  - Published in Journal: Information Processing and Management as the 2nd author, available at [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0306457322003314?via%3Dihub). 
  <!-- - Reproduce code of four baselines for cross-domain text sentiment classification on Reviews Dataset. -->

# Research Experience

- **Continual Semantic Segmentation**, SYSU (Advised by Ruixuan Wang), _September 2020-May 2022_
  -  Explore self-attention mechanism application on Continual Semantic Segmentation, to keep learning new classes and remember old classes, got SOTA result. Paper published in Journal: Pattern Recognition, SATS: Self-Attention Transfer for Continual Semantic Segmentation.
  -  Extension of SATS to Classification, Object Detection and Instance Segmentation.
  -  Explore how to use continual learning strategy on Segmentation Model to learn the segment of different scenes, in which one class objects belongs to only one scene. Construct related experiments on Medical Decathlon dataset and COCO dataset.

- **Cross Domain Text Sentiment Classification**, SYSU (Advised by Yanghui Rao), _September 2019-August 2020_
  - Reimplementation results of baselines on Amazon Reviews Dataset.
  - Join the discussion of key innovation of some new method to improve the performance.
  - Paper published in Journal: Information Processing and Management, TDAN: Topic Driven Adaptive Network for Cross-Domain Sentiment Classification.

- **Transductive Ensemble Learning Semantic Segmentation**, SYSU (Advised by Ruixuan Wang), _September 2019-August 2020_
  - Using the ensemble pseudo label of testing set from the previous model to help the semantic segmentation of medical images  
  - Explore how the high confidence part of testing set’s pseudo label affects the training of segmentation model

# Projects

## Distributed File System

Python, Redis, gRPC, sqlite3, [Github](https://github.com/QIU023/Distributed_File_System)
- Implemented PAXOS distributed system consistency algorithm: sending proposals and file contents and checking timestamps and status of all responses among multiple servers to synchronize files through the gRPC framework.
- Build client local file cache system using Redis and Two-Queue (FIFO and LRU queue). 
- Implemented the Load Balancing/Traffic Management algorithm with the information of the 'ping' time delay, the number of hoops from the client to all file servers, and access frequency of each server to confirm the optimal server for each client access.
- Implemented parallel Read/Write access control for the same file through locks on sqlite database.

## Instant 

Go, Redis, MongoDB, [Github](https://github.com/QIU023/instant-go)
- Developing Back-End of the system, including low-level API to execute MongoDB queries/written and high-level API that executes the input command and sends the retrieved data to the front-end using web socket.
- Implemented a "Fan Out on Write" inbox using Go, MongoDB to retrieve userfeed, decreasing time to fetch data compared to "Fan Out on Read"(FOR) by over 3 times. Built hierarchy web session cache system with Redis and MongoDB, decreasing time to fetch data comparing to ”FOR” by over 10 times

## Operating System

C, C++, x86 assembly, shell, makefile
- Developing a simple Operating System that can run on a bare virtual machine, including a command shell, boot-sector module, a basic core module, a process scheduling module, and a FAT12 file system.

# Awards

  - Third Prize of Sun Yat-sen University Scholarship (2019, 2020, 2021)
  - Third Prize of Chaoshan Galaxy Award (2018), full marks(150/150) of math in college entrance examination(only two in Guangdong province)
  - First prize of Guangdong Province in the Chinese College Student Mathematics Competition (2019, 2020)
  - Sun Yat-sen University ACM Competition (second prize in 2019, third prize in 2020)

# Standard Test Scores

- **TOEFL: 106** (Listening: 27, Reading: 29, Writing: 27, Speaking: 23)
- **GRE: 318** (Verbal Reasoning: 151, Quantitative Reasoning: 167, Analytical Writing: 3.5)

# Skills

- **Programing:** (C/C++, Python, Java, Go, CUDA, shell, SQL, x86 assembly)
- **Libraries:** (Pytorch, Tensorflow, Matplotlib, Numpy, Redis, MongoDB, MySQL)
- **Tools:** (git, docker, Linux System)
- **Computer Vision:** (Semantic Segmentation, Incremental Learning, Super-Resolution, Facial Landmark Detection, Object Detection, Image Classification, Lite Network Optimization)
- **Natural Language Processing:** (Sentiment Classification, Cross Domain Transfer Learning, Topic Model, word2vec)
- **Machine Learning and Artificial Intelligence:** (Bayesian Learning, Searching, SVM, Logistic Regression, Decision Tree, Gaussian Mixture Model)
- **Reinforcement Learning:** (Monto-Carlo Tree Searching, Policy Gradient, Value/Policy Iteration, DQN, Meta-Gradient for hyper-params)
- **Recommender System:** (Collabtive Filtering, Latent Factor Modeling SVD, Sentiment Analysis based regression)

