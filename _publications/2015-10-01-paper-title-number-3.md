---
title: "Hybrid ViT-RetinaNet with Explainable Ensemble Learning for Fine-Grained Vehicle Damage Classification"
collection: publications
category: manuscripts
status: published
authors: "Ananya Saha, Mahir Afser Pavel, Md Fahim Shahoriar Titu, Afifa Zain Apurba, & Riasat Khan"
role: "Co-author"
venue: "Vehicles (MDPI)"
journal: "Vehicles"
quartile: "Q2"
year: 2025
paperurl: "https://www.mdpi.com/2624-8921/7/3/89"
bibtexurl: "https://scholar.googleusercontent.com/scholar.bib?q=info:wLU3kLSDFR0J:scholar.google.com/&output=citation&scisdr=CoE6YM8LEIzjolOJ-es:AIVdB-wAAAAAap2P4evTIgttsTZwYrpDXBugjJU&scisig=AIVdB-wAAAAAap2P4Y700Q2GtF7mmkMP1nQShb4&scisf=4&ct=citation&cd=-1&hl=en"
keywords: ["Vision Transformers", "Vehicle Damage", "Explainable AI"]
permalink: /publication/hybrid-vit-retinanet-vehicle-damage
excerpt: "This paper proposes a robust and interpretable ViT–RetinaNet framework with weighted ensemble learning for accurate and real-time vehicle damage detection."
date: 2025-08-25
citation: "Saha, Ananya, et al. \"Hybrid ViT-RetinaNet with Explainable Ensemble Learning for Fine-Grained Vehicle Damage Classification.\" Vehicles 7.3 (2025): 89."
---
## Abstract
Efficient and explainable vehicle damage inspection is essential due to the increasing complexity and volume of vehicular incidents. Traditional manual inspection approaches are not time-effective, prone to human error, and lead to inefficiencies in insurance claims and repair workflows. Existing deep learning methods, such as CNNs, often struggle with generalization, require large annotated datasets, and lack interpretability. This study presents a robust and interpretable deep learning framework for vehicle damage classification, integrating Vision Transformers (ViTs) and ensemble detection strategies. The proposed architecture employs a RetinaNet backbone with a ViT-enhanced detection head, implemented in PyTorch using the Detectron2 object detection technique. It is pretrained on COCO weights and fine-tuned through focal loss and aggressive augmentation techniques to improve generalization under real-world damage variability. The proposed system applies the Weighted Box Fusion (WBF) ensemble strategy to refine detection outputs from multiple models, offering improved spatial precision. To ensure interpretability and transparency, we adopt numerous explainability techniques—Grad-CAM, Grad-CAM++, and SHAP—offering semantic and visual insights into model decisions. A custom vehicle damage dataset with 4500 images has been built, consisting of approximately 60% curated images collected through targeted web scraping and crawling covering various damage types (such as bumper dents, panel scratches, and frontal impacts), along with 40% COCO dataset images to support model generalization. Comparative evaluations show that Hybrid ViT-RetinaNet achieves superior performance with an F1-score of 84.6%, mAP of 87.2%, and 22 FPS inference speed. In an ablation analysis, WBF, augmentation, transfer learning, and focal loss significantly improve performance, with focal loss increasing F1 by 6.3% for underrepresented classes and COCO pretraining boosting mAP by 8.7%. Additional architectural comparisons demonstrate that our full hybrid configuration not only maintains competitive accuracy but also achieves up to 150 FPS, making it well suited for real-time use cases. Robustness tests under challenging conditions, including real-world visual disturbances (smoke, fire, motion blur, varying lighting, and occlusions) and artificial noise (Gaussian; salt-and-pepper), confirm the model’s generalization ability. This work contributes a scalable, explainable, and high-performance solution for real-world vehicle damage diagnostics.
