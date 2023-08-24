---
title: "Early Experience with Transformer-Based Similarity Analysis for DataRaceBench"
collection: publications
permalink: /publication/EarlyDRB
excerpt: ''
date: 2023-01-31
venue: 'IEEE Correctness 22'
paperurl: 'https://ieeexplore.ieee.org/document/10027519'
citation: 'W. Chen, T. Vanderbruggen, P. -H. Lin, C. Liao and M. Emani, "Early Experience with Transformer-Based Similarity Analysis for DataRaceBench," 2022 IEEE/ACM Sixth International Workshop on Software Correctness for HPC Applications (Correctness), Dallas, TX, USA, 2022, pp. 45-53, doi: 10.1109/Correctness56720.2022.00011.'
---



[Early Experience with Transformer-Based Similarity Analysis for DataRaceBench](https://ieeexplore.ieee.org/document/10027519) (Chen et al., IEEE Correctness 2022)

Abstract:

DataRaceBench (DRB) is a dedicated benchmark suite to evaluate tools aimed to find data race bugs in OpenMP programs. Using microbenchmarks with or without data races, DRB is able to generate standard quality metrics and provide systematic and quantitative assessments of data race detection tools. However, as the number of microbenchmarks grows, it is challenging to manually identify similar code patterns for DRB, within the context of identifying duplicated kernels or guiding the additions of new kernels. In this paper, we experiment with a transformer-based, deep learning approach to similarity analysis. A state-of-the-art transformer model, CodeBERT, has been adapted to find similar OpenMP code regions. We explore the challenges and the solutions when applying transformer-based similarity analysis to new source codes which are unseen by pre-trained transformers. Using comparative experiments of different variants of similarity analysis, we comment on the strengths and limitations of the transformer-based approach and point out future research directions.