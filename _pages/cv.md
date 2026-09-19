---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-page {
    max-width: 920px;
    margin: 0 auto;
  }

  .cv-page .cv-download-links {
    margin: 0 0 2rem;
    padding: 1.25rem 1.35rem;
    border: 1px solid var(--global-border-color);
    border-left: 5px solid var(--global-text-color);
    background: var(--global-bg-color);
    box-shadow: 0 8px 22px rgba(17, 24, 39, 0.08);
  }

  .cv-page .cv-download-links a {
    display: inline-flex;
    align-items: center;
    min-height: 42px;
    padding: 0.65rem 1rem;
    border: 1px solid var(--global-text-color);
    border-radius: 6px;
    background: var(--global-text-color);
    color: var(--global-bg-color);
    text-decoration: none;
    font-weight: 700;
  }

  .cv-page .cv-download-links a:hover {
    opacity: 0.78;
  }

  .cv-page h1 {
    margin: 2.25rem 0 1rem;
    padding-bottom: 0.65rem;
    border-bottom: 2px solid var(--global-text-color);
    color: var(--global-text-color);
    font-size: 1.45rem;
    letter-spacing: 0.01em;
  }

  .cv-page h1:first-of-type {
    margin-top: 0;
  }

  .cv-page ul {
    margin-top: 0.5rem;
    padding-left: 1.35rem;
  }

  .cv-page > ul,
  .cv-page > p + ul {
    padding: 1rem 1.25rem 1rem 2rem;
    border-left: 3px solid var(--global-border-color);
    background: color-mix(in srgb, var(--global-bg-color) 94%, var(--global-text-color) 6%);
  }

  .cv-page li {
    margin-bottom: 0.55rem;
    line-height: 1.65;
  }

  .cv-page li:last-child {
    margin-bottom: 0;
  }

  .cv-page li > ul {
    margin-top: 0.45rem;
    padding-bottom: 0;
  }

  .cv-page li > ul li {
    margin-bottom: 0.3rem;
  }
</style>

<div class="cv-page" markdown="1">

<div class="cv-download-links">
  <a href="{{ base_path }}/files/Mahir_Afser_Pavel_Academic_CV.pdf" target="_blank" rel="noopener noreferrer">Download Academic CV (PDF)</a>
</div>

Profile Summary
======

* AI researcher with a strong research interest in **medical image analysis** and **90+ citations (Google Scholar, September 2026)** in **5 Q1** and solo Q2 journal publications, **4** of which are **SCIE** and **2 ESCI**, holding an **h-index** of **3** and **i10-index** of **2**.

Research Interests
======

* Vision-Language Models (VLMs) and Large Language Models (LLMs)
* Deep Learning, Explainable Artificial Intelligence (XAI), and Edge AI
* Medical Image Analysis and Computational Clinical Triaging

Education
======

* B.Sc. in Computer Science and Engineering, North South University, 2019–2024
  * CGPA: 3.71/4.00
  * Magna Cum Laude
  * B.Sc. Thesis: "Non-small cell lung cancer detection through knowledge distillation approach with teaching assistant"
  * Summary: Implemented a three-stage knowledge distillation architecture for lung cancer classification on the NSCLC-Radiomics dataset, achieving 94.53% accuracy and later deploying it in a web application.
  * Supervisor: Dr. Riasat Khan, Associate Professor, Department of ECE

Work experience
======

* Aug 2025 – Present: Research Assistant
  * ELITE Research Lab LLC, Dhaka, Bangladesh
  * Responsibilities include: federated medical architectures, 3D brain tumor segmentation with structure-aware latent graph reasoning, and uncertainty-aware explainable deep learning frameworks for medical diagnosis.
  * Supervisor: Md. Kishor Morol, Research Scientist & Founder

* Jan 2024 – Mar 2025: Research Intern
  * Mahdy Research Academy, Remote
  * Responsibilities included: developing CLKD-MED, a cross-lingual knowledge distillation framework for multilingual clinical outcome prediction from electronic health records.
  * Supervisor: M. R. C. Mahdy

* May 2024 – Jul 2024: Research Assistant
  * North South University, Dhaka, Bangladesh
  * Responsibilities included: developing lightweight deep learning and knowledge-distillation approaches for real-time drone-based fire detection and deploying YOLOv8n on Raspberry Pi 5 edge devices.
  * Supervisor: Faculty research team

Skills
======

* Programming & Data Science
  * Python
  * SQL
  * C++
  * Java
  * Bash Scripting
  * NumPy, Pandas, Matplotlib, SPSS, Microsoft Excel

* Artificial Intelligence & Machine Learning
  * Deep Learning
  * Computer Vision
  * Medical Image Analysis
  * Explainable AI (XAI)
  * Knowledge Distillation
  * Federated Learning
  * PyTorch, TensorFlow, Keras, Scikit-learn

* Generative AI & Vision-Language Models
  * Vision-Language Models (VLMs)
  * Large Language Models (LLMs)
  * BLIP, CLIP, Florence-2, PaliGemma
  * LLaMA
  * Retrieval-Augmented Generation (RAG)
  * Low-Rank Adaptation (LoRA)
  * Quantization-Aware Training (QAT)

* Edge AI & Research Tools
  * YOLOv5, YOLOv8
  * Raspberry Pi 5
  * OpenCV, Detectron2
  * Git, GitHub
  * LaTeX, Overleaf

Honors & Awards
======

* Magna Cum Laude (December 2024): North South University
* Academic Merit Scholarship: multiple tuition waivers (10%–20%) based on strong semester GPA
* Peer Reviewer Recognition (March 2026): recognition for scientific reviews in IEEE Access and Frontiers in Computer Science

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

</div>
