---
title: "SLGRA-Net: Structure-Aware Latent Graph Reasoning for 3D Brain Tumor Segmentation"
collection: publications
category: under-review
status: under-review
authors: "Mahir Afser Pavel, Nafiz Fahad, Md Tanzib Hosain, Md. Kishor Morol, Tze Hui Liew"
role: "First Author"
venue: "Biomedical Signal Processing and Control (Elsevier)"
journal: "Biomedical Signal Processing and Control"
quartile: "Pending"
year: 2026
thumbnail: "/images/slgra.png"
keywords: ["Brain tumor segmentation", "3D MRI", "Latent graph reasoning", "Graph neural networks", "Medical image segmentation", "Uncertainty-aware learning"]
permalink: /publication/slgra-net-brain-tumor-segmentation
excerpt: "This paper introduces **SLGRA-Net, a structure-aware latent graph reasoning** framework that enables efficient global reasoning for 3D brain tumor segmentation with uncertainty-aware supervision."
date: 2026-07-18
citation: "Mahir Afser Pavel et al. (under review). SLGRA-Net: Structure-Aware Latent Graph Reasoning for 3D Brain Tumor Segmentation."
---
## Abstract

### Background

Segmentation of brain tumor subregions from multi-modal 3D MRI is essential for clinical diagnosis and treatment planning. However, it remains challenging due to severe class imbalance, ambiguous boundaries, and fragmented enhancing tumor (ET) regions. While convolutional and transformer-based models improve local and global feature representations, most approaches operate in dense voxel or token spaces, resulting in high computational costs and limited explicit structural representation.

### Methods

This paper proposes **SLGRA-Net**, a **Structure-aware Latent Graph Reasoning Network** that enables global structural reasoning within a compact latent graph space. The framework aggregates 3D feature patches into graph nodes, efficiently capturing long-range structural dependencies while preserving voxel-level precision. Graph-based message passing further refines node representations, which are adaptively integrated into the decoder through gated unpooling. To address severe class imbalance and label uncertainty, particularly in the clinically important ET region, an auxiliary node-level supervision mechanism with uncertainty-aware and class-balanced weighting is introduced.

### Findings

Extensive experiments on the **BraTS benchmarks** demonstrate that SLGRA-Net achieves strong segmentation performance, reaching a **Dice score of 0.89**, with particularly robust performance in the clinically critical ET region, while substantially reducing computational overhead compared with transformer-based methods. Comprehensive ablation studies validate the contribution of each architectural component, while external validation demonstrates the framework's robust and consistent performance across diverse datasets.

**Keywords:** 3D Brain Tumor Segmentation; Multi-Modal MRI; Latent Graph Reasoning; Structure-Aware Learning; Uncertainty-Aware Supervision; Class Imbalance; BraTS; Medical Image Segmentation.