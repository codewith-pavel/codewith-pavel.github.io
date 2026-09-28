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
    --cv-accent: #237a70;
    --cv-highlight: #a95f1c;
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
    border-bottom: 2px solid color-mix(in srgb, var(--cv-accent) 55%, transparent);
    color: var(--cv-accent);
    font-size: 1.45rem;
    letter-spacing: 0.01em;
  }

  .cv-page strong {
    color: var(--cv-accent);
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
    border-left: 3px solid color-mix(in srgb, var(--cv-accent) 60%, var(--global-border-color));
    background: color-mix(in srgb, var(--global-bg-color) 96%, var(--cv-accent) 4%);
  }

  .cv-page li {
    margin-bottom: 0.55rem;
    line-height: 1.65;
  }

  .cv-page li::marker {
    color: var(--cv-highlight);
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

  .cv-page .cv-publications {
    display: grid;
    gap: 1rem;
    margin: 1.25rem 0 0;
    padding: 0;
    list-style: none;
  }

  .cv-page .cv-publication {
    display: grid;
    grid-template-columns: 5.25rem minmax(0, 1fr);
    gap: 1rem;
    margin: 0;
    padding: 1.2rem 1.25rem;
    border: 1px solid var(--global-border-color);
    border-left: 4px solid var(--cv-accent);
    background: color-mix(in srgb, var(--global-bg-color) 96%, var(--cv-accent) 4%);
  }

  .cv-page .cv-publication__meta {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 0.4rem;
    padding-top: 0.15rem;
  }

  .cv-page .cv-publication__year {
    color: var(--global-text-color);
    font-size: 1.05rem;
    font-weight: 800;
  }

  .cv-page .cv-publication__status {
    padding: 0.2rem 0.45rem;
    border-radius: 3px;
    background: color-mix(in srgb, var(--global-bg-color) 84%, var(--cv-highlight) 16%);
    color: var(--global-text-color);
    font-size: 0.68rem;
    font-weight: 700;
    line-height: 1.3;
    text-transform: uppercase;
  }

  .cv-page .cv-publication__title {
    margin: 0 0 0.45rem;
    font-size: 1.05rem;
    line-height: 1.45;
  }

  .cv-page .cv-publication__title a {
    color: var(--global-text-color);
    text-decoration-color: var(--cv-accent);
    text-decoration-thickness: 1px;
    text-underline-offset: 3px;
  }

  .cv-page .cv-publication__title a:hover {
    color: var(--cv-accent);
  }

  .cv-page .cv-publication__authors,
  .cv-page .cv-publication__venue,
  .cv-page .cv-publication__citation,
  .cv-page .cv-publication__excerpt {
    margin: 0.35rem 0 0;
    line-height: 1.55;
  }

  .cv-page .cv-publication__authors {
    font-weight: 600;
  }

  .cv-page .cv-publication__authors span,
  .cv-page .cv-publication__citation,
  .cv-page .cv-publication__excerpt {
    color: var(--global-text-color);
    opacity: 0.78;
  }

  .cv-page .cv-publication__venue {
    color: var(--cv-accent);
    font-size: 0.92rem;
    font-weight: 700;
  }

  @media (max-width: 600px) {
    .cv-page .cv-publication {
      grid-template-columns: minmax(0, 1fr);
      gap: 0.55rem;
      padding: 1rem;
    }

    .cv-page .cv-publication__meta {
      flex-direction: row;
      align-items: center;
      flex-wrap: wrap;
    }
  }
</style>

<div class="cv-page" markdown="1">

<div class="cv-download-links">
  <a href="{{ base_path }}/files/Mahir_Afser_Pavel_Academic_CV.pdf" target="_blank" rel="noopener noreferrer">Download Academic CV (PDF)</a>
</div>

Profile Summary
======

* **AI researcher** with a strong research interest in **medical image analysis** and **90+ citations (Google Scholar, September 2026)** in **5 Q1** and solo Q2 journal publications, **4** of which are **SCIE** and **2 ESCI**, holding an **h-index** of **3** and **i10-index** of **2**.

Research Interests
======

* **Vision-Language Models (VLMs)** and **Large Language Models (LLMs)**
* **Deep Learning**, **Explainable Artificial Intelligence (XAI)**, and **Edge AI**
* **Medical Image Analysis** and **Computational Clinical Triaging**

Education
======

* **B.Sc. in Computer Science and Engineering**, **North South University**, 2019–2024
  * **CGPA: 3.71/4.00**
  * **Magna Cum Laude**
  * **B.Sc. Thesis:** "Non-small cell lung cancer detection through knowledge distillation approach with teaching assistant"
  * **Summary:** Implemented a three-stage **knowledge distillation** architecture for **lung cancer classification** on the **NSCLC-Radiomics** dataset, achieving **94.53% accuracy** and later deploying it in a web application.
  * Supervisor: Dr. Riasat Khan, Associate Professor, Department of ECE

Work experience
======

* **Aug 2025 – Present: Research Assistant**
  * **ELITE Research Lab LLC**, Dhaka, Bangladesh
  * Responsibilities include: **federated medical architectures**, **3D brain tumor segmentation** with **structure-aware latent graph reasoning**, and **uncertainty-aware explainable deep learning** frameworks for medical diagnosis.
  * Supervisor: Md. Kishor Morol, Research Scientist & Founder

* **Jan 2024 – Mar 2025: Research Intern**
  * **Mahdy Research Academy**, Remote
  * Responsibilities included: developing **CLKD-MED**, a **cross-lingual knowledge distillation** framework for **multilingual clinical outcome prediction** from electronic health records.
  * Supervisor: M. R. C. Mahdy

* **May 2024 – Jul 2024: Research Assistant**
  * **North South University**, Dhaka, Bangladesh
  * Responsibilities included: developing **lightweight deep learning** and **knowledge-distillation** approaches for **real-time drone-based fire detection** and deploying **YOLOv8n** on **Raspberry Pi 5** edge devices.
  * Supervisor: Faculty research team

Skills
======

* **Programming & Data Science**
  * **Python**
  * **SQL**
  * **C++**
  * **Java**
  * **Bash Scripting**
  * **NumPy, Pandas, Matplotlib, SPSS, Microsoft Excel**

* **Artificial Intelligence & Machine Learning**
  * **Deep Learning**
  * **Computer Vision**
  * **Medical Image Analysis**
  * **Explainable AI (XAI)**
  * **Knowledge Distillation**
  * **Federated Learning**
  * **PyTorch, TensorFlow, Keras, Scikit-learn**

* **Generative AI & Vision-Language Models**
  * **Vision-Language Models (VLMs)**
  * **Large Language Models (LLMs)**
  * **BLIP, CLIP, Florence-2, PaliGemma**
  * **LLaMA**
  * **Retrieval-Augmented Generation (RAG)**
  * **Low-Rank Adaptation (LoRA)**
  * **Quantization-Aware Training (QAT)**

* **Edge AI & Research Tools**
  * **YOLOv5, YOLOv8**
  * **Raspberry Pi 5**
  * **OpenCV, Detectron2**
  * **Git, GitHub**
  * **LaTeX, Overleaf**

Honors & Awards
======

* **Magna Cum Laude** (December 2024): North South University
* **Academic Merit Scholarship:** multiple tuition waivers (10%–20%) based on strong semester GPA
* **Peer Reviewer Recognition** (March 2026): recognition for scientific reviews in **IEEE Access**, **Heliyon** and **Frontiers in Computer Science**

Publications
======
  <ul class="cv-publications">{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

</div>
