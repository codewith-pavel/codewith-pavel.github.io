---
title: "ACP-KD: Adaptive Clinical Prototype Knowledge Distillation with Dynamic Feature Fusion and Confidence-Aware Multi-Objective Learning for Lightweight Skin Lesion Classification"
collection: publications
category: under-review
status: under-review
authors: "Anonymous Authors"
role: "First Author"
venue: "Winter Conference on Applications of Computer Vision (WACV)"
journal: "WACV"
quartile: "Pending"
year: 2026
thumbnail: "/images/acp-kd.png"
keywords: ["Skin lesion classification", "Knowledge distillation", "Medical image analysis", "Dynamic feature fusion", "Prototype learning", "Confidence calibration", "HAM10000"]
permalink: /publication/acp-kd-adaptive-clinical-prototype-knowledge-distillation
excerpt: "This study introduces ACP-KD, a multi-objective knowledge distillation framework that combines dynamic feature fusion, prototype learning, and confidence-aware calibration for lightweight and reliable skin lesion classification."
date: 2026-08-30
citation: "Anonymous Authors (under review). ACP-KD: Adaptive Clinical Prototype Knowledge Distillation with Dynamic Feature Fusion and Confidence-Aware Multi-Objective Learning for Lightweight Skin Lesion Classification."
---

## Abstract

Automated skin lesion classification has achieved substantial progress through deep learning; however, the computational complexity of high-capacity models remains a major barrier to deployment in resource-constrained clinical environments. Knowledge distillation offers an effective approach for transferring diagnostic knowledge from powerful teacher networks to lightweight student models, yet conventional methods largely depend on output-level supervision and may fail to capture the heterogeneous, sample-dependent, and reliability-sensitive nature of medical image representations. To address these limitations, this study proposes **Adaptive Clinical Prototype Knowledge Distillation (ACP-KD)**, a multi-objective framework designed to improve the efficiency, robustness, and calibration of lightweight skin lesion classifiers. ACP-KD employs a high-capacity hybrid teacher and a lightweight student architecture with dynamic feature fusion, enabling the transfer of complementary diagnostic knowledge through multiple distillation objectives, including logit, attention, feature, prototype, concept, and confidence distillation. A difficulty-aware adaptive weighting mechanism dynamically adjusts the contribution of these knowledge sources according to individual sample characteristics and predictive reliability. Furthermore, prototype-guided representation learning promotes discriminative class-aware feature spaces, while counterfactual regularization enhances the robustness of learned representations. Confidence-aware supervision is incorporated to improve predictive calibration and reliability. Comprehensive experiments on the **HAM10000** dataset, including ablation, calibration, computational efficiency, and cross-dataset evaluations, demonstrate the effectiveness of the proposed framework. ACP-KD achieves **95.27\% accuracy, 95.10\% macro-F1, and 0.992 AUC**, while substantially reducing computational requirements compared with the high-capacity teacher model. The framework also achieves an **Expected Calibration Error (ECE) of 0.014**, indicating improved predictive reliability and calibration. Extensive ablation studies further confirm the complementary contributions of the individual knowledge sources and adaptive mechanisms. Overall, the findings demonstrate that ACP-KD provides an effective pathway for transferring diverse high-capacity diagnostic knowledge into efficient, robust, and better-calibrated lightweight models, supporting their potential deployment in resource-constrained medical imaging applications.

**Keywords:** Skin lesion classification; Knowledge distillation; Medical image analysis; Dynamic feature fusion; Prototype learning; Confidence calibration; Model efficiency; HAM10000; Explainable and reliable AI. 