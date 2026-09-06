---
title: "Multi-stage knowledge distillation with layer fusion-based deep learning approach for skin cancer classification"
collection: publications
category: manuscripts
status: published
authors: "Mahir Afser Pavel, Ramisa Asad, Goh Kah Ong Michael, Md Ikramuzzaman, Murad Mustakim & Riasat Khan"
role: "First Author"
venue: "Scientific Reports (nature)"
journal: "Scientific Reports"
quartile: "Q1"
year: 2025
paperurl: "https://www.nature.com/articles/s41598-025-23403-2"
bibtexurl: "https://scholar.googleusercontent.com/scholar.bib?q=info:UmLM9UdfxhgJ:scholar.google.com/&output=citation&scisdr=CoE6YM8IEIzjolOM6z8:AIVdB-wAAAAAap2K8z_QJk3GVB84aRIUL7qgS5E&scisig=AIVdB-wAAAAAap2K84v-ZZ6FzPYhz4ILqNyUikw&scisf=4&ct=citation&cd=-1&hl=en&scfhb=1"
keywords: ["Knowledge Distillation", "Skin Cancer", "Deep Learning"]
thumbnail: "/images/41598_2025_23403_Fig1_HTML.webp"
permalink: /publication/multi-stage-knowledge-distillation-skin-cancer
excerpt: "This paper presents a multi-stage knowledge distillation and layer fusion approach for accurate, efficient, and interpretable skin lesion classification."
date: 2025-11-13
citation: "M. A. Pavel et al. (2025). \"Multi-stage knowledge distillation with layer fusion-based deep learning approach for skin cancer classification.\" Scientific Reports 15.1 (2025): 39792."
---
## Abstract
Skin cancer is one of the most common types of cancer globally, caused by prolonged exposure to the sun’s UV rays. Despite recent developments in research, early diagnosis, prevention, and treatment, skin cancer remains a significant health concern. This study proposes a multi-stage knowledge distillation-based deep learning technique with a layer fusion strategy to classify different types of skin lesion cells using the HAM10000 dataset. Augmentation and basic preprocessing steps have been applied to the HAM10000 dataset to enhance robustness. The applied multi-stage knowledge distillation incorporates intermediate features by measuring several loss values and coefficients to balance the corresponding losses. The proposed ViT and ConvNeXT-integrated teacher model leverages hybrid architectures derived from baseline models, combining convolutional feature extraction with transformer-based attention mechanisms. The distilled model, built using CNN and EfficientNet, achieved significant performance improvements over the baseline. The optimized model achieved an accuracy of 95.88%, F1 and AUC scores of 95.91% and 99.02%, respectively. Multi-stage knowledge distillation with intermediate exits and layer fusion improved model accuracy and performance metrics with the lowest training and inference times of 61 and 15 ms/step, respectively. Post-training quantization was applied to reduce the parameters and size of the distilled model. Multiple XAI techniques—Grad-CAM, Score-CAM, and LIME—have been explored to enhance the interpretability of the applied multi-stage knowledge distillation model. The implementation codes with the quantized and distilled model are available in the following repository: https://github.com/codewith-pavel/Optimizations.
