---
layout: default
title: Algorithmic Recourse using Causal Inference
---

# Algorithmic Recourse: Towards Actionable and Assistive Machine Learning

Machine learning has made remarkable strides, automating high-stakes decisions in domains such as loan approvals, granting bails, medical diagnostics, autonomous navigation, and agricultural monitoring. These systems operate on complex, high-dimensional inputs and deliver automated predictions that often influence real-world decisions. However, when outcomes are unfavorable or incorrect, the root cause is not always a flaw in the model itself. Sometimes, the outcome can be influenced also by the manner in which the input data is captured and presented to the model during inference. Users, especially non-experts, are rarely given clear guidance on how to adjust their inputs for better results.

Consider an automated pesticide recommendation system that relies on smartphone-based image diagnostics. In such systems, choosing the appropriate camera zoom level is critical: zooming out might fail to capture small pests, while zooming in too closely can obscure the broader context needed to assess crop damage. Identifying this optimal zoom level — one that matches the model’s preferred input conditions for accurate predictions — is often not straightforward for end-users like farmers. While it is widely acknowledged that machine learning models perform optimally when test-time inputs align with their training distribution, users are often unaware of these training conditions. This gap underscores the need for ML systems that do more than just provide passive predictions; they should actively assist users in generating appropriate inputs. Recourse models fulfill this need by guiding users toward feasible, minimally disruptive modifications to their inputs, thereby increasing the likelihood of success.


Some motivating examples of recourse include:

- **Image Recognition**: If an image is poorly lit, a recourse model could suggest improving the lighting to enhance classification accuracy.
- **Loan Approval**: For denied applications, the model might recommend actionable steps, such as clearing specific debts, to increase the likelihood of loan approval.
- **Medical Diagnosis**: In diabetes management, the model could suggest adjustments to insulin dosage to maintain blood glucose within a safe range, helping prevent adverse health conditions.

In this project, our team explores how to build such recourse models, **analyze** their feasibility under realistic assumptions, and design efficient training **algorithms**. We show **applications** of recourse models in many areas, such as diagnosing root causes of anomalies, planning personalized interventions to achieve desired outcomes, etc.


# Publications
* Robust Root Cause Diagnosis using In-Distribution Interventions \
  In *ICLR 2025*, with Lokesh N, Ashutosh Srivastava, Sunita Sarawagi, Amit Sharma\

* From Search to Sampling: Generative Models for Robust Algorithmic Recourse \
  In *ICLR 2025*, with Prateek Garg, Lokesh N, Sunita Sarawagi\

* Leveraging a Simulator for Learning Causal Representations from Post-Treatment Covariates for CATE \
  In *TMLR 2025*, with Lokesh N, Pranava Singhal, Avishek Ghosh, Sunita Sarawagi\

* PairNet: Training with Observed Pairs to Estimate Individual Treatment Effect \
  In *ICML 2024*, with Lokesh N, Pranava Singhal, Avishek Ghosh, Sunita Sarawagi\

* Continuous Treatment Effect Estimation Using Gradient Interpolation and Kernel Smoothing \
  In *AAAI 2024*, with Lokesh N, Akshay Iyer, Abir De, Sunita Sarawagi\

* Learning Recourse on Instance Environment to Enhance Prediction Accuracy \
  In *NeurIPS 2022*, with Lokesh N, Guntakanti Sai Koushik, Abir De, Sunita Sarawagi\

 

# Collaborators
* [Lokesh N](https://nlokesh.netlify.app/)
* [Prateek Garg](https://prateekgargx.github.io/)
* [Akshay Iyer](https://www.linkedin.com/in/akshay-iyer2211/)
* [Pranava Singhal](https://scholar.google.com/citations?user=7smSwUsAAAAJ&hl=en)
* [Amit Sharma](http://amitsharma.in/)
* [Abir De](https://abir-de.github.io/)
* [Avishek Ghosh](https://sites.google.com/view/avishekghosh/home)
* [Sunita Sarawagi](https://www.cse.iitb.ac.in/~sunita/)