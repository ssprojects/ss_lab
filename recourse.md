---
layout: default
title: Algorithmic Recourse using Causal Inference
---

# Algorithmic Recourse using Causal Inference
Our goal is to offer recourse solutions for instances impacted by machine learning predictions. Suppose the data generating process, denoted as $\mathcal{G}: Z\times \Beta \mapsto \mathcal{X}$, creates instances $\mathbb{x} \in \mathcal{X}$ based on inherent features $z \in Z$ and environmental features $\beta \in \Beta$. In image classification tasks, $Z$ encompasses content attributes such as class label and object shape, while $\Beta$ represents style attributes like brightness and rotation. In loan approval models, $Z$ corresponds to user attributes like age and gender, with $\Beta$ encompassing mutable attributes like an individual's bank balance. We aim to shift the model's decision to a favorable outcome as the user implements the recommended recourse actions. The key to solving this problem lies in treatment effect estimation, where we model the difference in predicted outcomes as the environment changes from $\beta$ to $\beta'$. The inherent complexity arises from confounding/treatment selection bias in training datasets, and we propose robust models for predicting actionable recourse actions.

# Publications
 * Learning Recourse on Instance Environment to Enhance Prediction Accuracy \
   In NeurIPS 2022, with Lokesh Nagalapatti, Guntakanti Sai Koushik, Abir De, Sunita Sarawagi\
   \[[Paper](https://openreview.net/forum?id=nrOLtfeiIdh)\]
 

# Collaborators
* [N Lokesh](https://nlokesh.netlify.app/)
* [Prateek Garg](https://prateekgargx.github.io/)
* [Pranava Singhal](https://scholar.google.com/citations?user=7smSwUsAAAAJ&hl=en)
* [Abir De](https://abir-de.github.io/)
* [Avishek Ghosh](https://sites.google.com/view/avishekghosh/home)
* [Sunita Sarawagi](https://www.cse.iitb.ac.in/~sunita/)