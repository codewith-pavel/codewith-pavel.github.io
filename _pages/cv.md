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
    padding: 0 0 2rem;
  }

  .cv-page .cv-download-links {
    margin: 0 0 1.5rem;
    padding: 1rem 1.15rem;
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

  .cv-page .cv-profile,
  .cv-page .cv-card {
    margin: 0 0 1rem;
    padding: 1.1rem 1.25rem;
    border: 1px solid var(--global-border-color);
    border-left: 4px solid var(--cv-accent);
    border-radius: 6px;
    background: color-mix(in srgb, var(--global-bg-color) 97%, var(--cv-accent) 3%);
    box-shadow: 0 4px 14px rgba(17, 24, 39, 0.05);
  }

  .cv-page .cv-profile {
    margin-bottom: 1.75rem;
    padding: 1.5rem;
    border-left-width: 6px;
  }

  .cv-page .cv-profile h1 {
    margin: 0 0 0.25rem;
    padding: 0;
    border: 0;
    font-size: clamp(1.7rem, 3vw, 2rem);
    line-height: 1.2;
  }

  .cv-page .cv-card-title {
    display: flex;
    flex-wrap: wrap;
    align-items: baseline;
    justify-content: space-between;
    gap: 0.35rem 1rem;
    margin: 0 0 0.65rem;
  }

  .cv-page .cv-card-title .cv-card-date {
    color: var(--cv-accent);
    font-size: 0.9rem;
    font-weight: 700;
  }

  .cv-page .cv-card-location {
    margin: -0.4rem 0 0.65rem;
    font-size: 0.92rem;
    opacity: 0.75;
  }

  .cv-page .cv-card ul {
    margin: 0;
  }

  .cv-page .cv-card li:last-child {
    margin-bottom: 0;
  }

  .cv-page .cv-ielts {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem 1.25rem;
    align-items: center;
  }

  .cv-page .cv-ielts strong {
    color: var(--cv-accent);
  }

  .cv-page h1 {
    margin: 1.8rem 0 0.75rem;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid color-mix(in srgb, var(--cv-accent) 55%, transparent);
    color: var(--global-text-color);
    font-size: 1.35rem;
    letter-spacing: 0.01em;
  }

  .cv-page h3 {
    margin: 1.4rem 0 0.55rem;
    font-size: 1.05rem;
    line-height: 1.4;
  }

  .cv-page strong {
    color: var(--global-text-color);
  }

  .cv-page h1:first-of-type {
    margin-top: 0;
  }

  .cv-page .cv-role {
    margin: 0.35rem 0 0.5rem;
    color: var(--cv-accent);
    font-size: 1.05rem;
    font-weight: 700;
    line-height: 1.45;
  }

  .cv-page .cv-contact {
    margin: 0.25rem 0 0.5rem;
  }

  .cv-page .cv-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.35rem 0;
    margin: 0 0 1.25rem;
  }

  .cv-page .cv-links a + a::before {
    display: inline-block;
    margin: 0 0.65rem 0 0;
    color: var(--global-text-color);
    content: "·";
    opacity: 0.7;
  }

  .cv-page ul {
    margin: 0.4rem 0 1rem;
    padding-left: 1.35rem;
  }

  .cv-page > ul,
  .cv-page > p + ul {
    margin-bottom: 1.25rem;
    padding: 0.85rem 1rem 0.85rem 1.8rem;
    border-left: 3px solid color-mix(in srgb, var(--cv-accent) 60%, var(--global-border-color));
    border-radius: 0 5px 5px 0;
    background: color-mix(in srgb, var(--global-bg-color) 96%, var(--cv-accent) 4%);
  }

  .cv-page li {
    margin-bottom: 0.4rem;
    line-height: 1.6;
  }

  .cv-page li::marker {
    color: var(--cv-highlight);
  }

  .cv-page li:last-child {
    margin-bottom: 0;
  }

  .cv-page li > ul {
    margin-top: 0.3rem;
    padding-bottom: 0;
  }

  .cv-page li > ul li {
    margin-bottom: 0.25rem;
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
    color: var(--global-text-color);
    text-decoration-thickness: 2px;
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
    color: var(--global-text-color);
    font-size: 0.92rem;
    font-weight: 700;
  }

  @media (max-width: 600px) {
    .cv-page {
      padding-bottom: 1.5rem;
    }

    .cv-page .cv-download-links {
      padding: 0.85rem;
    }

    .cv-page .cv-profile,
    .cv-page .cv-card {
      padding: 0.9rem 1rem;
    }

    .cv-page .cv-profile {
      padding: 1.1rem;
    }

    .cv-page .cv-card-title {
      display: block;
    }

    .cv-page .cv-card-title .cv-card-date {
      display: block;
      margin-top: 0.15rem;
    }

    .cv-page > ul,
    .cv-page > p + ul {
      padding: 0.75rem 0.75rem 0.75rem 1.5rem;
    }

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
  <a href="{{ base_path }}/files/CV MAHIR AFSER PAVEL.pdf" target="_blank" rel="noopener noreferrer">Download Academic CV (PDF)</a>
</div>

<div class="cv-profile" markdown="1">

Mahir Afser Pavel
======

<p class="cv-role">AI Researcher · Medical AI · Multimodal Learning · Efficient and Reliable Deep Learning</p>

<p class="cv-contact">Dhaka, Bangladesh · +8801873742510 · <a href="mailto:mahir.pavel@gmail.com">mahir.pavel@gmail.com</a></p>

<p class="cv-links"><a href="https://scholar.google.com/citations?hl=en&amp;user=172rqgEAAAAJ&amp;view_op=list_works&amp;sortby=pubdate">Google Scholar</a><a href="https://orcid.org/0009-0005-3395-9159">ORCID</a><a href="https://www.researchgate.net/profile/Mahir-Afser-Pavel?ev=hdr_xprf">ResearchGate</a><a href="https://github.com/codewith-pavel">GitHub</a><a href="https://www.linkedin.com/in/mahirafserpavel/">LinkedIn</a><a href="https://codewith-pavel.github.io/">Portfolio</a></p>

</div>

Profile Summary
======

* AI researcher specializing in medical image analysis, with an emphasis on developing computationally efficient, reliable, and interpretable AI methods. Research spans knowledge distillation, explainable AI, vision-language models, quantization, federated learning, and visual question answering. First author of articles in Scientific Reports and PLOS One; co-first author of an article in the International Journal of Dentistry; second author of articles in Drones and Vehicles; and third author of an article in IEEE Access. Google Scholar profile: 100+ citations, h-index: 3, and i10-index: 2.

Research Interests
======

* Medical Image Analysis and Clinical AI: Medical image classification and segmentation, disease detection, and AI-assisted clinical triage.
* Multimodal Learning and Foundation Models: Vision-language models (VLMs), medical image-text alignment, and visual question answering (VQA).
* Efficient and Explainable AI: Knowledge distillation, model compression and quantization, explainable AI (XAI), and computationally efficient deep learning.
* Clinical Natural Language Processing and Privacy-Preserving AI: Federated learning, generative augmentation, clinical text analysis, robustness, and interpretable AI.

Education
======

<div class="cv-card cv-education" markdown="1">

<p class="cv-card-title"><strong>North South University</strong><span>Dhaka, Bangladesh</span></p>

<p class="cv-card-title"><strong>Bachelor of Science in Computer Science and Engineering</strong><span class="cv-card-date">2019–2023</span></p>

* CGPA: 3.71/4.00 ([Grading Policy](https://www.northsouth.edu/academic/grading-policy.html))
* CSE-specific GPA: 3.91/4.00 (Capstone Design, Core, and Elective Courses)
* Class Rank: 38th out of 595 students
* **B.Sc. Thesis:** “Non-small cell lung cancer detection through knowledge distillation approach with teaching assistant”
* **Summary:** Implemented a three-stage knowledge distillation architecture for lung cancer classification on the NSCLC-Radiomics dataset, achieving 94.53% accuracy, and later deployed it in a user-friendly web application.
* **Supervisor:** [Dr. Riasat Khan](https://ece.northsouth.edu/people/riasat-khan/), Associate Professor, Department of ECE

</div>

Scholarly Publications
======

### Peer-Reviewed Journal Publications

* **Multi-stage knowledge distillation with layer fusion-based deep learning approach for skin cancer classification**
  * Authors: Mahir Afser Pavel, Ramisa Asad, Goh Kah Ong Michael, Md Ikramuzzaman, Murad Mustakim, and Riasat Khan.
  * [Scientific Reports](https://www.nature.com/srep/) (Nature Portfolio), 2025. DOI: [10.1038/s41598-025-23403-2](https://doi.org/10.1038/s41598-025-23403-2). [Code](https://github.com/codewith-pavel/Optimizations)
* **Non-small cell lung cancer detection through knowledge distillation approach with teaching assistant**
  * Authors: Mahir Afser Pavel, Rafiul Islam, Shoyeb Bin Babor, Riaz Mehadi, and Riasat Khan.
  * [PLOS One](https://journals.plos.org/plosone/) (PLOS), 2024. DOI: [10.1371/journal.pone.0306441](https://doi.org/10.1371/journal.pone.0306441). [Code](https://github.com/codewith-pavel/KnowledgeDistillation)
* **Error-Tolerant Multimodal Vision-Language Models for Endodontic Triaging: A Cross-Sectional Study**
  * Authors: Mahir Afser Pavel (Co-First Author), Md Fahim Shahoriar Titu (Co-First Author), Afifa Zain Apurba, Saif Ahmed, Shafin Rahman, James Dudley, and Taseef Hasan Farook.
  * [International Journal of Dentistry](https://onlinelibrary.wiley.com/journal/6164) (Wiley), 2026. DOI: [10.1155/ijod/4148741](https://doi.org/10.1155/ijod/4148741). [Code](https://github.com/codewith-pavel/Endodontic-using-VLM)
* **Fusion of Image Filtering and Knowledge-Distilled YOLO Models for Root Canal Failure Diagnosis**
  * Authors: Afifa Zain Apurba, Md Fahim Shahoriar Titu, Mahir Afser Pavel, Intisar Tahmid Naheen, and Riasat Khan.
  * [IEEE Access](https://ieeeaccess.ieee.org/) (IEEE), 2025. DOI: [10.1109/ACCESS.2025.3560998](https://doi.org/10.1109/ACCESS.2025.3560998). [Code](https://github.com/codewith-pavel/Dental-Detection-ImageFiltering-Distillation)
* **Real-time fire detection: Integrating lightweight deep learning models on drones with edge computing**
  * Authors: Md Fahim Shahoriar Titu, Mahir Afser Pavel, Goh Kah Ong Michael, Hisham Babar, Umama Aman, and Riasat Khan.
  * [Drones](https://www.mdpi.com/journal/drones) (MDPI), 2024. DOI: [10.3390/drones8090483](https://doi.org/10.3390/drones8090483). [Code](https://github.com/codewith-pavel/Object_detection_with_Autodistill)
* **Hybrid ViT-RetinaNet with Explainable Ensemble Learning for Fine-Grained Vehicle Damage Classification**
  * Authors: Ananya Saha, Mahir Afser Pavel, Md Fahim Shahoriar Titu, Afifa Zain Apurba, and Riasat Khan.
  * [Vehicles](https://www.mdpi.com/journal/vehicles) (MDPI), 2025. DOI: [10.3390/vehicles7030089](https://doi.org/10.3390/vehicles7030089). [Code](https://github.com/codewith-pavel/finegrained-damage-classify-xai)

### Manuscripts Under Review

* Federated Multi-Component Framework for Brain Tumor Diagnosis with Generative Augmentation and Explainable AI
* CLKD-MED: A novel cross-lingual knowledge distillation framework for multilingual clinical outcome prediction
* SLGRA-Net: Structure-Aware Latent Graph Reasoning for 3D Brain Tumor Segmentation

### Research in Progress

* Trustworthy Clinical AI for Diabetic Retinopathy Grading via Hybrid Foundation Models, Calibration-Aware Uncertainty Learning, and Multi-Criteria Clinical Referral
* S³-Net: Self-Stabilizing, Self-Regulating, and Self-Optimizing Neural Networks via Universal Stability Learning
* FULCRUM: Option-Contrastive Frame Selection for Long-Video Understanding
* ACP-KD: Adaptive Clinical Prototype Knowledge Distillation with Dynamic Feature Fusion and Confidence-Aware Multi-Objective Learning for Lightweight Skin Lesion Classification

Professional Experience
======

<div class="cv-card cv-experience" markdown="1">

<p class="cv-card-title"><strong>Research Assistant · ELITE Research Lab LLC</strong><span class="cv-card-date">Aug 2025–Present</span></p>

<p class="cv-card-location">Dhaka, Bangladesh</p>

* **Federated Brain Tumor Classification:** Developed Fed-GAN-DE-CL, a federated multi-component framework that integrates generative adversarial networks and dual-encoder contrastive learning for decentralized brain tumor classification without centralizing patient data.
* **3D Brain Tumor Segmentation:** Proposed SLGRA-Net, incorporating structure-aware latent graph reasoning to model spatial relationships and address ambiguous tumor boundaries in 3D MRI segmentation.
* **Ongoing Research:** Contributing to research on trustworthy clinical AI, self-optimizing neural networks, and adaptive knowledge distillation, focusing on uncertainty calibration, neural network stability, and lightweight skin lesion classification.

</div>

<div class="cv-card cv-experience" markdown="1">

<p class="cv-card-title"><strong>Research Assistant · United International University</strong><span class="cv-card-date">May 2025–Jun 2025</span></p>

<p class="cv-card-location">Dhaka, Bangladesh</p>

* Optimized transformer architectures and developed multilingual benchmarks for low-resource languages using Hugging Face Transformers and PyTorch Lightning, leveraging TensorBoard and Weights & Biases (W&B) for experiment tracking, visualization, and hyperparameter tuning. Designed data preprocessing, feature engineering, and model-training pipelines; conducted literature reviews on multi-agent systems; and contributed to research proposal development.

</div>

<div class="cv-card cv-experience" markdown="1">

<p class="cv-card-title"><strong>Research Assistant · North South University</strong><span class="cv-card-date">May 2024–Jul 2024</span></p>

<p class="cv-card-location">Dhaka, Bangladesh</p>

* Co-developed a drone-based fire-detection pipeline using knowledge distillation to deploy lightweight YOLOv8n models on Raspberry Pi 5 devices for edge inference.

</div>

<div class="cv-card cv-experience" markdown="1">

<p class="cv-card-title"><strong>Research Trainee · Mahdy Research Academy</strong><span class="cv-card-date">Jan 2024–Mar 2025</span></p>

<p class="cv-card-location">Remote / Online</p>

* Introduced CLKD-MED, a knowledge-distillation framework for multilingual clinical outcome prediction using 92,293 clinical notes from the MIMIC-III dataset, transferring clinical representations across English and lower-resource languages to predict length of stay and mortality.

</div>

Skills
======

* **Programming Languages:** Python (Advanced), C++, Java, Bash.
* **AI/ML Frameworks:** PyTorch, TensorFlow, Keras, Scikit-learn, OpenCV.
* **Generative AI & VLMs:** LangChain, LLaMA, RAG, LoRA, QAT, BLIP, CLIP, Florence-2, PaliGemma.
* **Research & Development Tools:** Git, GitHub, LaTeX, Overleaf.
* **Databases & Analysis:** SQL, MySQL, NumPy, Pandas, Matplotlib, SPSS, Microsoft Excel.

Research Projects & Technical Contributions
======

* **Medical Image Analysis, Knowledge Distillation & Explainable AI:** Develops lightweight, layer-fusion, and knowledge-distillation methods for skin lesion classification, NSCLC detection from CT scans, dental radiograph analysis, and brain tumor diagnosis. Applies SHAP, LIME, and Score-CAM for model interpretability.
* **Medical Vision-Language Models & Efficient Clinical AI:** Evaluates BLIP, CLIP, Florence-2, and PaliGemma for dental triage, medical image understanding, and multimodal medical question answering. Explores quantization-aware training (QAT), model compression, LoRA, and efficient adaptation to reduce computational and memory requirements while preserving diagnostic performance.
* **Computer Vision, Object Detection & Edge Deployment:** Develops image processing, Grounded SAM-assisted annotation, YOLO-based detection, and teacher–student knowledge-distillation pipelines for root canal failure diagnosis. Also investigates drone-based fire detection on Raspberry Pi 5 and Hybrid ViT–RetinaNet with Weighted Box Fusion for vehicle damage classification.
* **Federated Learning, Generative Augmentation & 3D Biomedical AI:** Investigates federated learning, generative adversarial networks, and synthetic data augmentation for brain tumor diagnosis across decentralized, non-IID data distributions. Explores structure-aware latent graph reasoning and 3D volumetric segmentation to model spatial relationships and ambiguous tumor boundaries, improve robustness to data heterogeneity, and support explainable, reliability-aware evaluation.
* **Clinical NLP, Reliable AI & Generalizable Learning:** Develops cross-lingual knowledge distillation for clinical outcome prediction in low-resource languages and explores medical language models, retrieval-augmented generation (RAG), clinical reasoning, and healthcare decision support. Investigates calibration-aware uncertainty estimation, confidence-aware learning, and multi-criteria clinical referral for diabetic retinopathy grading, alongside adaptive clinical prototype distillation, dynamic feature fusion, confidence-aware multi-objective optimization for lightweight skin lesion classification, stability-oriented neural networks, and efficient video understanding.

Academic Service, Leadership & Mentoring
======

* **Research Leadership and Team Coordination:** Led research initiatives in deep learning, computer vision, and clinical NLP at ELITE Research Lab LLC and Mahdy Research Academy. Coordinated research assistants and senior design projects at North South University, mentoring junior students and supporting data-pipeline development and manuscript preparation across projects associated with five peer-reviewed journal articles.
* **Academic Manuscript Peer Reviewer:** Reviewed research manuscripts for IEEE and Elsevier journals, evaluating methodological rigor, technical validity, originality, and clarity.
* **Teaching and Student Mentoring (2022–2023):** Co-led academic sessions and supported laboratory instruction in Digital Electronics, Analog Electronics, and Senior Design at North South University under faculty supervision. Mentored students in circuit mapping, hardware–software co-design, laboratory troubleshooting, and scientific writing.

Standardized Test Scores
======

<div class="cv-card cv-ielts">
  <strong>IELTS Academic · 2026</strong>
  <span>Overall: 6.5</span>
  <span>Listening: 7.0</span>
  <span>Reading: 7.0</span>
  <span>Writing: 6.5</span>
  <span>Speaking: 6.0</span>
</div>

Honors & Awards
======

* **Magna Cum Laude (December 2024):** Awarded by North South University for academic excellence in the B.Sc. in Computer Science and Engineering program; ranked within the top 7% of the cohort.
* **Academic Merit Scholarships:** Received multiple tuition waivers of 10%–20% from North South University based on semester academic performance, with semester GPAs reaching 4.00.
* **Peer Reviewer Recognition (2026):** Recognized for peer-review contributions to IEEE Access, Heliyon, and Frontiers in Computer Science.

References
======

* **Dr. Riasat Khan** — Associate Professor, Department of Electrical and Computer Engineering, North South University. [riasat.khan@northsouth.edu](mailto:riasat.khan@northsouth.edu)
* **Dr. Shafin Rahman** — Associate Professor, Department of Electrical and Computer Engineering, North South University. [shafin.rahman@northsouth.edu](mailto:shafin.rahman@northsouth.edu)
* **Md. Kishor Morol** — Research Scientist and Founder, ELITE Research Lab LLC. [kishor@aiub.edu](mailto:kishor@aiub.edu)

</div>
