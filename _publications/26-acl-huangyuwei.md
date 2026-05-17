---
title: "LSEG: A Fine-tuning Free Method for NL2FOL via Logic-Structure and Entropy Guided Inference Controlling"
collection: publications
permalink: /publication/26-acl-huangyuwei
excerpt: ''
date: 2026-04-06
venue: ' ACL (Findings)'
citation: 'Yuwei Huang, <b>Shi Wang</b>, Kangli Zi, Tianyu Luo, Jiang Zhixiao, Ruiheng Wang, Yufei Wang: LSEG: A Fine-tuning Free Method for NL2FOL via Logic-Structure and Entropy Guided Inference Controlling. ACL 2026 (Findings)'
---
Abstract
--
Large language models have shown strong generative and reasoning capabilities, yet they still struggle with natural language to first order logic (NL2FOL) translation due to logical hallucination. We propose LSEG (Logic Structure and Entropy Guided), a fine-tuning free framework designed to improve logical consistency during inference. The core idea of LSEG is to correct hidden state deviation by leveraging logical stability across logic preserving perturbations of the input. Such deviation is especially harmful in NL2FOL, as even small drifts can flip quantifier scope or logical operators, producing formulas that are syntactically valid yet logically incorrect. First, LSEG constructs perturbation-averaged direction vectors that approximate a stable logical center. Second, it derives layer-wise correction directions by contrasting original and perturbed representations. Lastly, LSEG uses an entropy-guided adaptive mechanism to inject these directions only when the model exhibits unstable or over-confident reasoning states, thereby preserving fluency while correcting logical drift. Experiments on the FOLIO and MALLS benchmarks show that LSEG consistently improves logical equivalence scores over strong baselines, despite requiring no training or parameter updates. Further evaluation on LogicLLaMA demonstrates LSEG’s architecture-agnostic effectiveness.

[Download](https://2026.aclweb.org/program/findings/)
