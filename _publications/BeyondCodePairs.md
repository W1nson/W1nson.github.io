---
title: "Beyond Code Pairs: Dialogue-Based Data Generation for LLM Code Translation"
collection: publications
category: conferences
permalink: /publication/BeyondCodePairs
excerpt: ''
date: 2025-11-29
venue: 'ACL 2026'
paperurl: 'https://arxiv.org/abs/2512.03086'
citation: 'L. Chen, N. Xu, W. Chen, B. Lei, P.-H. Lin, D. Zhou, R. Thakur, C. Ding, A. Jannesari, and C. Liao. 2026. Beyond Code Pairs: Dialogue-Based Data Generation for LLM Code Translation. In Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (ACL).'
---


Abstract:

Large language models (LLMs) have shown remarkable capabilities in code translation, yet their performance deteriorates in low-resource programming domains such as Fortran and emerging frameworks like CUDA, where high-quality parallel data are scarce. We present an automated dataset generation pipeline featuring a dual-LLM Questioner-Solver design that incorporates external knowledge from compilers and runtime feedback. Beyond traditional source-target code pair datasets, our approach additionally generates (1) verified translations with unit tests for assessing functional consistency and (2) multi-turn dialogues that capture the reasoning process behind translation refinement. Applied to Fortran-to-C++ and C++-to-CUDA, the pipeline yields 3.64k and 3.93k dialogues, respectively. Fine-tuning on this data yields dramatic improvements in functional correctness, boosting unit test success rates by over 56% on the challenging C++-to-CUDA task. We show that the generated data enables a 7B open-weight model to significantly outperform larger proprietary systems on key metrics like compilation success.
