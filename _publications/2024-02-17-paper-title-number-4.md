---
title: "Fusion of Image Filtering and Knowledge-Distilled YOLO Models for Root Canal Failure Diagnosis"
collection: publications
category: manuscripts
status: published
authors: "Afifa Zain Apurba, Md Fahim Shahoriar Titu, Mahir Afser Pavel, Intisar Tahmid Naheen, & Riasat Khan"
role: "Co-author"
venue: "IEEE Access (IEEE)"
journal: "IEEE Access"
quartile: "Q1"
year: 2025
paperurl: "https://doi.org/10.1109/ACCESS.2025.3560998"
bibtexurl: "https://scholar.googleusercontent.com/scholar.bib?q=info:r9tv7vMGvDYJ:scholar.google.com/&output=citation&scisdr=CoE6YM8OEKiYrlO8pwk:AIVdB-wAAAAAap26vwnJmKnXNjDY5OP97PZ8MBM&scisig=AIVdB-wAAAAAap26v83rgWt9gn8-M4hKM-3f0BA&scisf=4&ct=citation&cd=-1&hl=en"
keywords: ["Root Canal Diagnosis", "YOLO", "Knowledge Distillation"]
thumbnail: "/images/khan5-3560998-large.gif"
permalink: /publication/fusion-image-filtering-knowledge-distilled-yolo-root-canal
excerpt: "This paper combines image filtering and knowledge-distilled YOLO models for root canal failure diagnosis."
date: 2025-04-15
citation: "Apurba, Afifa Zain, et al. \"Fusion of Image Filtering and Knowledge-Distilled YOLO Models for Root Canal Failure Diagnosis.\" IEEE Access 13 (2025): 66557-66573."
---
## Abstract:
Root canal treatment involves the removal of inflamed pulp from infected teeth and sealing them to prevent re-entry of bacteria and infection. Early and accurate identification of root canal issues is crucial for improving treatment outcomes and minimizing complications. This study proposes a novel method for efficiently detecting failures in root canal treatments by incorporating image filtering techniques into deep learning models. A custom dataset has been collected from Square Hospital Ltd of Dhaka, Bangladesh, comprising 1,600 annotated, filtered radiographs. These images are processed using denoising algorithms (mean, median, Gaussian, contourlet transform, or Bayesian wavelet), non-local means, and BM3D. The YOLO models used for detection included YOLOv5, YOLOv7, and YOLOv8, with YOLOv5 achieving the highest accuracy of 90.6% on the filtered datasets. This work integrates an autodistillation technique with Grounded SAM as the base model for bounding box generation, YOLOv8 as an intermediate model to bridge architectural differences, and YOLOv5 as the target model due to its lightweight design, fewer parameters, and superior performance on the filtered dataset. Knowledge distillation was employed to optimize performance on lightweight models, resulting in precision and recall values of 99.16% and 97.29%, respectively, for YOLOv5. The filtered datasets outperformed raw images, with the Bayesian wavelet and contourlet transform yielding the best results on YOLOv5. This pipeline demonstrates the potential to develop one of the most accurate and clinically applicable diagnostic tools for root canal failure detection by combining deep learning and knowledge distillation techniques with image filtering. This study demonstrates how combining deep learning with advanced image enhancement techniques can provide a highly accurate, clinically relevant tool for the early detection of root canal treatment failures, potentially aiding dentists in making faster and more consistent diagnoses.
