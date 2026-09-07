---
title: "S³-Net: Self-Stabilizing, Self-Regulating, and Self-Optimizing Neural Networks via Universal Stability Learning"
collection: publications
category: under-review
status: under-review
authors: "Anonymous Authors"
role: "First Author"
venue: "Winter Conference on Applications of Computer Vision (WACV)"
journal: "WACV"
quartile: "A"
year: 2026
thumbnail: "/images/s3Net.png"
keywords: ["Deep neural networks", "Training stability", "Adaptive optimization", "Hyperparameter robustness", "Meta-optimization", "Feature dynamics", "Stability learning"]
permalink: /publication/s3-net-universal-stability-learning
excerpt: "This paper introduces S³-Net, a closed-loop stability-aware training framework that adaptively regulates optimization and improves robustness, calibration, and convergence across deep learning models."
date: 2026-08-30
citation: "Anonymous Authors (under review). S³-Net: Self-Stabilizing, Self-Regulating, and Self-Optimizing Neural Networks via Universal Stability Learning."
---
## Abstract

Deep neural networks have achieved remarkable performance across a wide range of computer vision tasks; however, their training processes remain largely passive, with optimization strategies, learning schedules, and regularization parameters typically predetermined rather than dynamically adapting to the evolving stability of the learning process. This limitation can increase sensitivity to initialization, hyperparameter configurations, and stochastic optimization dynamics, resulting in inconsistent convergence and reduced training reliability.

To address this challenge, this study presents **S$^3$-Net**, a unified framework for **Self-Stabilizing, Self-Regulating, and Self-Optimizing Neural Networks via Universal Stability Learning**, which reformulates neural network training as a closed-loop optimization process. S$^3$-Net integrates a stability-aware **FRFormer** backbone with a **Dynamic Stability Module (DSM)**, **Neural Stability Controller (NSC)**, **Meta Optimizer (MO)**, **Universal Stability Loss (USL)**, and **Stability Distillation (SD)**. The DSM continuously characterizes feature, activation, prediction, and gradient dynamics, while the NSC uses the resulting stability state to adapt the training process online. The Meta Optimizer learns transferable optimization configurations, whereas USL explicitly incorporates stability into the training objective and SD transfers stability-aware representations across different model capacities.

The framework is evaluated across **6 datasets and 8 representative architectures** under multiple random seeds, hyperparameter perturbations, and training budgets. Compared with corresponding baseline training strategies, S$^3$-Net improves average predictive performance by **3.27%** while reducing the aggregate instability measure by **41.36%**. Across independent training runs, the framework reduces performance variance by **46.82%** and sensitivity to hyperparameter perturbations by **42.57%**. The adaptive controller introduces an average computational overhead of only **8.73%**, while Stability Distillation reduces the teacher–student stability gap by **34.68%**. Comprehensive ablation studies demonstrate that stability monitoring, adaptive regulation, stability-aware optimization, and stability transfer provide complementary improvements, with the complete framework achieving the most consistent performance across the evaluated settings.

Overall, these findings support **autonomous stability learning** as a general approach for transforming conventional open-loop neural optimization into a more adaptive, self-regulating, and reliable learning process.

**Keywords:** Deep neural networks; Training stability; Adaptive optimization; Hyperparameter robustness; Meta-optimization; Feature dynamics; Stability learning; Universal stability loss; Closed-loop training.
