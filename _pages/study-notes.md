---
permalink: /study-notes/
title: "Study Notes"
author_profile: true
---

<style>
  .study-notes-page {
    --bg-dark: #0a0a0a;
    --panel: rgba(17, 17, 17, 0.8);
    --panel-border: rgba(255, 255, 255, 0.1);
    --text: #f5f5f5;
    --muted: rgba(255, 255, 255, 0.7);
    --accent: #ff416c;
    --accent-2: #ff4b2b;
    --button: rgba(255, 255, 255, 0.08);
    --button-hover: rgba(255, 255, 255, 0.18);
    --shadow: rgba(0, 0, 0, 0.25);
  }

  .study-notes-page {
    padding: 3rem 1.25rem 2rem;
    color: var(--text);
    background:
      radial-gradient(circle at top, rgba(255, 75, 43, 0.22), transparent 25%),
      linear-gradient(135deg, #050505, #111111 48%, #0d0d0d 100%);
    border-radius: 18px;
    box-shadow: 0 20px 40px var(--shadow);
  }

  .study-notes-page .page-header {
    text-align: center;
    margin-bottom: 2rem;
  }

  .study-notes-page .eyebrow {
    font-size: 0.78rem;
    letter-spacing: 0.18rem;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 0.75rem;
  }

  .study-notes-page h2 {
    font-size: clamp(2rem, 4vw, 3rem);
    line-height: 1.2;
    margin: 0 0 1rem;
    font-weight: 700;
    background: linear-gradient(135deg, var(--accent), var(--accent-2));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
  }

  .study-notes-page .subtitle {
    max-width: 820px;
    margin: 0 auto;
    font-size: 1.15rem;
    line-height: 1.7;
    color: var(--muted);
  }

  .study-notes-page .card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.25rem;
    margin-top: 2rem;
  }

  .study-notes-page .card {
    width: min(100%, 290px);
    background: var(--panel);
    border: 1px solid var(--panel-border);
    border-radius: 14px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.22);
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
    position: relative;
  }

  .study-notes-page .card:hover {
    transform: translateY(-6px) scale(1.01);
    box-shadow: 0 18px 35px rgba(0, 0, 0, 0.28);
    border-color: rgba(255, 255, 255, 0.18);
  }

  .study-notes-page .card .card-content {
    padding: 1.4rem 1.2rem 1.2rem;
  }

  .study-notes-page .card h3 {
    margin: 0 0 0.7rem;
    font-size: 1.35rem;
    font-weight: 700;
    color: #ffffff;
  }

  .study-notes-page .card p {
    margin: 0 0 1.1rem;
    font-size: 0.96rem;
    line-height: 1.6;
    color: var(--muted);
  }

  .study-notes-page .card a {
    display: inline-block;
    color: #ffffff;
    text-decoration: none;
    background: var(--button);
    border: 1px solid rgba(255, 255, 255, 0.12);
    padding: 0.7rem 1rem;
    border-radius: 8px;
    font-weight: 600;
    transition: background 0.25s ease, transform 0.2s ease;
  }

  .study-notes-page .card a:hover {
    background: var(--button-hover);
    transform: translateY(-1px);
    text-decoration: none;
  }

  .study-notes-page .tooltip {
    position: absolute;
    top: 10px;
    right: 10px;
    background: rgba(0, 0, 0, 0.84);
    color: #fff;
    border-radius: 999px;
    padding: 0.3rem 0.65rem;
    font-size: 0.7rem;
    letter-spacing: 0.04rem;
    opacity: 0;
    transform: translateY(-6px);
    transition: opacity 0.25s ease, transform 0.25s ease;
    pointer-events: none;
  }

  .study-notes-page .card:hover .tooltip {
    opacity: 1;
    transform: translateY(0);
  }

  @media (max-width: 768px) {
    .study-notes-page {
      padding: 2.5rem 0.9rem 1.5rem;
    }

    .study-notes-page .subtitle {
      font-size: 1rem;
    }

    .study-notes-page .card {
      width: 100%;
      max-width: 450px;
    }
  }
</style>

<div class="study-notes-page">
  <div class="page-header">
    <p class="eyebrow">Learning Resources</p>
    <h2>Study Notes & Materials</h2>
    <p class="subtitle">
      Explore a collection of valuable resources, notes, guides, and technical materials designed to support deep learning, NLP, computer vision, and research learning.
    </p>
  </div>

  <div class="card-container">
    <div class="card">
      <div class="card-content">
        <h3>DL (Part 1)</h3>
        <p>Explore the 1st part of Deep Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_1.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 1</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>DL (Part 2)</h3>
        <p>Explore the 2nd part of Deep Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_2.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 2</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>DL (Part 3)</h3>
        <p>Explore the 3rd part of Deep Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_3.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 3</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>DL (Part 4)</h3>
        <p>Explore the 4th part of Deep Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_4.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 4</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>DL (Part 5)</h3>
        <p>Explore the 5th part of Deep Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_5.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 5</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>DL (CV)</h3>
        <p>Explore the Computer Vision part of Deep Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_CV.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 6</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>DL (NLP)</h3>
        <p>Explore the Natural Language Processing part of Deep Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/NLP_DL.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 7</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>NLP with ML-1</h3>
        <p>Explore the Natural Language Processing 1st part of Machine Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/NLP_ML_1.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 8</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>NLP with ML-2</h3>
        <p>Explore the Natural Language Processing 2nd part of Machine Learning.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/NLP_ML_2.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 9</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>NLP Coding Basics</h3>
        <p>Explore the coding basics of Natural Language Processing.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/Hands-On-Natural-Language-Processing-with-Python-master.zip" target="_blank" rel="noopener noreferrer">Visit ZIP</a>
        <div class="tooltip">Material 10</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>Useful Projects</h3>
        <p>Explore GitHub project references and available learning materials.</p>
        <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/github_if_available.txt" target="_blank" rel="noopener noreferrer">Visit TXT</a>
        <div class="tooltip">Material 11</div>
      </div>
    </div>

    <div class="card">
      <div class="card-content">
        <h3>PDF Books</h3>
        <p>Explore AI and machine learning books in PDF format.</p>
        <a href="https://github.com/mahirafserpavel/PDF" target="_blank" rel="noopener noreferrer">Visit PDF</a>
        <div class="tooltip">Material 12</div>
      </div>
    </div>
  </div>
</div>
