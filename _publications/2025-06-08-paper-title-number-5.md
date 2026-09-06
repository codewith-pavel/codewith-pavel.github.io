---
title: "Non-small cell lung cancer detection through knowledge distillation approach with teaching assistant"
collection: publications
category: manuscripts
status: published
authors: "Mahir Afser Pavel, Rafiul Islam, Shoyeb Bin Babor, Riaz Mehadi, & Riasat Khan"
role: "First Author"
venue: "PLOS ONE (PLOS)"
journal: "PLOS ONE"
quartile: "Q1"
year: 2024
paperurl: "https://doi.org/10.1371/journal.pone.0306441"
bibtexurl: "https://scholar.googleusercontent.com/scholar.bib?q=info:8GLnN3dXAnQJ:scholar.google.com/&output=citation&scisdr=CoE6YM8KEIzjolO4CTA:AIVdB-wAAAAAap2-ETCTYg-eBa5RpEstMncH4X4&scisig=AIVdB-wAAAAAap2-EWe3nXPQnAqJp6ouIGfuYgc&scisf=4&ct=citation&cd=-1&hl=en"
keywords: ["Lung Cancer", "Knowledge Distillation", "Medical AI"]
thumbnail: "/images/journal.pone.0306441.g003.png"
permalink: /publication/lung-cancer-knowledge-distillation-teaching-assistant
excerpt: "This paper presents a three-stage teacher–teaching assistant–student framework for efficient NSCLC classification with explainable AI and reduced computational complexity."
date: 2024-11-06
citation: "Pavel, Mahir Afser, et al. \"Non-small cell lung cancer detection through knowledge distillation approach with teaching assistant.\" Plos one 19.11 (2024): e0306441."
---
## Abstract:
Non-small cell lung cancer (NSCLC) exhibits a comparatively slower rate of metastasis in contrast to small cell lung cancer, contributing to approximately 85% of the global patient population. In this work, leveraging CT scan images, we deploy a knowledge distillation technique within teaching assistant (TA) and student frameworks for NSCLC classification. We employed various deep learning models, CNN, VGG19, ResNet152v2, Swin, CCT, and ViT, and assigned roles as teacher, teaching assistant and student. Evaluation underscores exceptional model performance in performance metrics achieved via cost-sensitive learning and precise hyperparameter (alpha and temperature) fine-tuning, highlighting the model’s efficiency in lung cancer tumor prediction and classification. The applied TA (ResNet152) and student (CNN) models achieved 90.99% and 94.53% test accuracies, respectively, with optimal hyperparameters (alpha = 0.7 and temperature = 7). The implementation of the TA framework improves the overall performance of the student model. After obtaining Shapley values, explainable AI is applied with a partition explainer to check each class’s contribution, further enhancing the transparency of the implemented deep learning techniques. Finally, a web application designed to make it user-friendly and classify lung types in recently captured images. The execution of the three-stage knowledge distillation technique proved efficient with significantly reduced trainable parameters and training time applicable for memory-constrained edge devices.
