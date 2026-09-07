---
title: "Trustworthy Clinical AI for Diabetic Retinopathy Grading via Hybrid Foundation Models, Calibration-Aware Uncertainty Learning, and Multi-Criteria Clinical Referral"
collection: publications
category: under-review
status: under-review
authors: "Anonymous Authors"
role: "First Author"
venue: "Winter Conference on Applications of Computer Vision (WACV)"
journal: "WACV"
quartile: "Pending"
year: 2026
thumbnail: "/images/trust_dr.png"
keywords: ["Diabetic retinopathy", "Trustworthy AI", "Medical image analysis", "Hybrid foundation models", "Calibration-aware learning", "Uncertainty estimation", "Clinical referral", "APTOS 2019"]
permalink: /publication/trust-dr-trustworthy-clinical-ai-diabetic-retinopathy
excerpt: "This paper introduces TRUST-DR, a trustworthy clinical AI framework for diabetic retinopathy grading that combines hybrid foundation-model features, calibration-aware uncertainty learning, and a multi-criteria clinical referral strategy."
date: 2026-08-30
citation: "Anonymous Authors (under review). Trustworthy Clinical AI for Diabetic Retinopathy Grading via Hybrid Foundation Models, Calibration-Aware Uncertainty Learning, and Multi-Criteria Clinical Referral."
---
## Abstract

Diabetic retinopathy (DR) is a leading cause of preventable blindness worldwide, making trustworthy automated screening essential for early diagnosis and clinical intervention. Although recent deep learning approaches have achieved promising classification performance, their clinical adoption remains constrained by poor confidence calibration, unreliable uncertainty estimation, limited interpretability, and simplistic referral strategies. This study proposes **TRUST-DR**, a trustworthy clinical artificial intelligence framework for automated DR grading that integrates hybrid CNN–foundation model feature learning, calibration-aware uncertainty estimation, quantitative explainability, clinical trust estimation, and a learnable multi-criteria referral mechanism within a unified end-to-end architecture. A hybrid **ResNet50–DINOv2** backbone captures complementary local lesion-level and global retinal representations, while predictive uncertainty, confidence calibration, image quality, and Grad-CAM-derived explainability are jointly incorporated to estimate a continuous **Clinical Trust Score** and guide intelligent referral decisions for clinically ambiguous cases. Experiments on the **APTOS 2019** dataset demonstrate that TRUST-DR achieves an accuracy of **95.27%**, a **Quadratic Weighted Kappa (QWK) of 0.9824**, an **Expected Calibration Error (ECE) of 0.014**, and a **Brier Score of 0.059**. These results demonstrate the potential of TRUST-DR to provide an accurate, well-calibrated, transparent, and clinically trustworthy decision-support framework for automated diabetic retinopathy screening.

**Keywords:** Diabetic retinopathy; Trustworthy AI; Medical image analysis; Hybrid foundation models; Calibration-aware learning; Uncertainty estimation; Clinical referral; APTOS 2019; Retinal image grading.
