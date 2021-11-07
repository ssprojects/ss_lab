---
layout: default
title: Machine Learning as a Service
---

With ever increasing size of State-of-the-art Machine Learning models, we see greater reliance on ML models hosted as a service through an API. 
Toward the objective of rendering service APIs that can cater to a wider population of clients, we conduct research on:   
(1) training algorithms that enable broader generalization--domain generalization\[[NeurIPS21a](#neurips21a), [ICML20](#icml20), [ICLR18](#iclr18)\].  
(2) evaluation data-structures that can allow the query of service's performance on the client data \[[NeurIPS21b](#neurips21b)\].   
(3) adaptation techniques that side-step the non-scalable parameter fine-tuning to potentially millions of clients \[[Interspeech20](#interspeech20), [EMNLP20](#emnlp20)\].  


<a name="neurips21a"></a>
* Training for the Future: A Simple Gradient Interpolation Loss to Generalize Along Time. \
  In *NeurIPS 2021*. A Nasery, S Thakur, V Piratla, A De, S Sarawagi \
  \[[Paper](https://arxiv.org/pdf/2108.06721.pdf)\]
  <a name="neurips21b"/>
* Active Assessment of Prediction Services as Accuracy Surface Over Attribute Combinations. \
  In *NeurIPS 2021*.\
  V Piratla, S Chakrabarty, S Sarawagi\
  \[[Paper](https://arxiv.org/pdf/2108.06514.pdf)\] \[[Code](https://github.com/vihari/AAA)\]
  <a name="interspeech20"/>
* Black-box Adaptation of ASR for Accented Speech. \
   In *Interspeech, 2020*. Kartik Khandelwal, Preethi Jyothi, Abhijeet Awasthi, Sunita Sarawagi\
   \[[Paper](https://arxiv.org/pdf/2006.13519)\] \[[Code](https://github.com/Kartik14/FineMerge)\]
  <a name="emnlp20"/>
* NLP Service APIs and Models for Efficient Registration of New Clients.\
   In *Findings in EMNLP 2020*. S Shah, V Piratla, S Chakrabarti, S Sarawagi\
   \[[Paper](https://arxiv.org/pdf/2010.01526.pdf)\] \[[Code](https://github.com/sahil00199/KYC)\]
  <a name="icml20"/>
* Efficient Domain Generalization via Common-Specific Low-Rank Decomposition. \
   In *ICML 2020*. V Piratla, P Netrapalli, S Sarawagi\
   \[[Paper](https://arxiv.org/pdf/2003.12815.pdf)\] \[[Code](https://github.com/vihari/CSD)\] \[[Talk 📢](https://icml.cc/virtual/2020/poster/6528)\]
   <a name="acl19"/>
  <a name="iclr18"/>
* Generalizing across domains via cross-gradient training. \
   In *ICLR 2018*.    S Shankar*, V Piratla*, S Chaudhuri, P Jyothi, S Chakrabarti, S Sarawagi \
   \[[Paper](https://arxiv.org/pdf/1804.10745.pdf)\] \[[Code](https://github.com/vihari/crossgrad)\]
   
# Collaborators
 * [Soumen Chakrabarti](https://www.cse.iitb.ac.in/~soumen/) 
 * [Siddhartha Chaudhuri](https://www.cse.iitb.ac.in/~sidch/)
 * [Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/)
