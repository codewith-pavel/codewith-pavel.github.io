---
title: "CLKD-MED: A cross-lingual knowledge distillation framework for bridging linguistic barriers in clinical AI"
collection: publications
category: under-review
status: under-review
authors: "Mahir Afser Pavel, Rafiul Islam, Mohammad Junayed Hasan, & M. R. C. Mahdy"
role: "First Author"
venue: "Information Processing & Management (Elsevier)"
journal: "Information Processing & Management"
quartile: "Q1"
year: 2026
keywords: ["Low-resource languages", "Healthcare informatics", "Multilingual clinical NLP"]
thumbnail: "/images/clkd.png"
permalink: /publication/clkd-med-cross-lingual-clinical-outcome
excerpt: "This paper introduces **CLKD-MED, a cross-lingual knowledge distillation** framework for multilingual clinical outcome prediction across low-resource languages, with interpretable and computationally efficient deployment."
date: 2026-08-17
citation: "Mahir Afser Pavel et al. (under review). CLKD-MED: A cross-lingual knowledge distillation framework for bridging linguistic barriers in clinical AI."
---
## Abstract

Clinical AI systems remain predominantly English-centric despite a substantial proportion of global healthcare operating in other languages. This disparity limits access to AI-driven clinical decision support for billions of individuals in linguistically diverse populations. This work introduces **CLKD-MED**, to the best of our knowledge, the first cross-lingual knowledge distillation framework that integrates multilingual clinical outcome prediction, cross-lingual distillation, and interpretability evaluation across multiple low-resource languages. The framework was validated on **92,293 clinical notes** from the **MIMIC-III** database using five translation strategies and five typologically diverse target languages: **Bengali** (Indo-Aryan), **Amharic** (Semitic), **Arabic** (Afroasiatic), **Swahili** (Bantu), and **Khmer** (Austroasiatic). Ensemble teacher models combining specialized clinical BERT variants achieved **ROC-AUC scores of 0.81 for length-of-stay prediction and 0.83 for mortality prediction** on English texts. Cross-lingual knowledge distillation consistently outperformed direct transfer learning across all languages, with statistically significant improvements (*p* < 0.05) and medium to large effect sizes, while achieving **2–3× computational efficiency gains** and **0.01–0.06 ROC-AUC improvements** for multilingual student models. SHAP-based interpretability analysis confirmed the preservation of clinical reasoning patterns across linguistic boundaries. CLKD-MED addresses a critical healthcare equity challenge by enabling robust clinical outcome prediction for underserved linguistic communities worldwide. Code is publicly available at the [Cross-Lingual Knowledge Distillation](https://github.com/codewith-pavel/Cross-Lingual-Knowledge-Distillation) repository.

**Keywords:** Cross-Lingual Knowledge Distillation; Multilingual Clinical NLP; Clinical Outcome Prediction; Low-Resource Languages; MIMIC-III; Explainable AI; Efficient Deep Learning.
