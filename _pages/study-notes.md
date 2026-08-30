---
permalink: /study-notes/
title: "Study Notes"
author_profile: true
---

<style>
  .study-notes-page {
    --bg: #ffffff;
    --panel: #ffffff;
    --panel-alt: #f7f9fc;
    --panel-soft: #f3f6fb;
    --border: rgba(15, 23, 42, 0.08);
    --text: #111827;
    --muted: #4b5563;
    --heading: #0f172a;
    --accent: #2563eb;
    --accent-2: #0ea5e9;
    --accent-soft: rgba(37, 99, 235, 0.08);
    --shadow: rgba(15, 23, 42, 0.08);
  }

  .study-notes-page {
    width: 100%;
    min-height: 100vh;
    padding: 0;
    background: linear-gradient(180deg, #ffffff 0%, #f8fbff 100%);
    color: var(--text);
    box-sizing: border-box;
  }

  .study-notes-page .page-shell {
    width: 100%;
    min-height: 100vh;
    margin: 0;
    background: rgba(255, 255, 255, 0.82);
    border: none;
    border-radius: 0;
    box-shadow: none;
    overflow: hidden;
  }

  .study-notes-page .hero {
    position: relative;
    padding: 5rem 2rem 3rem;
    min-height: 36vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background:
      radial-gradient(circle at top left, rgba(37, 99, 235, 0.12), transparent 24%),
      radial-gradient(circle at bottom right, rgba(14, 165, 233, 0.12), transparent 28%),
      linear-gradient(180deg, #ffffff 0%, #f9fbff 100%);
    border-bottom: 1px solid var(--border);
    text-align: center;
  }

  .study-notes-page .eyebrow {
    display: inline-block;
    padding: 0.5rem 0.9rem;
    border-radius: 999px;
    background: var(--accent-soft);
    color: var(--accent);
    letter-spacing: 0.14rem;
    text-transform: uppercase;
    font-size: 0.72rem;
    font-weight: 700;
    margin-bottom: 1rem;
  }

  .study-notes-page h2 {
    margin: 0;
    color: var(--heading);
    font-size: clamp(2.2rem, 4vw, 4rem);
    line-height: 1.08;
    letter-spacing: -0.04em;
    font-weight: 800;
  }

  .study-notes-page .subtitle {
    max-width: 960px;
    margin: 1.2rem auto 0;
    font-size: 1.12rem;
    line-height: 1.8;
    color: var(--muted);
  }

  .study-notes-page .note-intro {
    max-width: 1120px;
    margin: 0 auto 1.5rem;
    padding: 1.2rem 1.5rem;
    border: 1px solid var(--border);
    border-radius: 16px;
    background: linear-gradient(180deg, #ffffff 0%, #f5f9ff 100%);
    box-shadow: 0 10px 24px rgba(15, 23, 42, 0.04);
    text-align: center;
  }

  .study-notes-page .note-intro p {
    margin: 0;
    font-size: 1.08rem;
    line-height: 1.8;
    color: var(--heading);
    font-weight: 600;
  }

  .study-notes-page .content-wrap {
    padding: 2.2rem 2rem 2.5rem;
    max-width: 1440px;
    margin: 0 auto;
  }

  .study-notes-page .card-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1.3rem;
  }

  .study-notes-page .card {
    position: relative;
    background: linear-gradient(180deg, var(--panel) 0%, var(--panel-soft) 100%);
    border: 1px solid var(--border);
    border-radius: 18px;
    overflow: hidden;
    transition: transform 0.26s ease, box-shadow 0.26s ease, border-color 0.26s ease;
    box-shadow: 0 14px 28px rgba(15, 23, 42, 0.04);
  }

  .study-notes-page .card:hover {
    transform: translateY(-6px);
    border-color: rgba(37, 99, 235, 0.18);
    box-shadow: 0 22px 38px rgba(15, 23, 42, 0.09);
  }

  .study-notes-page .card .card-top {
    height: 8px;
    background: linear-gradient(90deg, var(--accent), var(--accent-2));
  }

  .study-notes-page .card .card-content {
    padding: 1.4rem 1.25rem 1.3rem;
  }

  .study-notes-page .card h3 {
    margin: 0 0 0.65rem;
    font-size: 1.28rem;
    line-height: 1.3;
    color: var(--heading);
    font-weight: 700;
  }

  .study-notes-page .card p {
    margin: 0 0 1rem;
    color: var(--muted);
    font-size: 0.96rem;
    line-height: 1.7;
  }

  .study-notes-page .card a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.72rem 1rem;
    border-radius: 10px;
    background: #111827;
    color: #ffffff;
    text-decoration: none;
    font-weight: 700;
    letter-spacing: 0.01em;
    transition: background 0.25s ease, transform 0.25s ease;
  }

  .study-notes-page .card a:hover {
    background: var(--accent);
    transform: translateY(-1px);
    text-decoration: none;
  }

  .study-notes-page .tooltip {
    position: absolute;
    top: 14px;
    right: 14px;
    background: rgba(15, 23, 42, 0.92);
    color: #fff;
    border-radius: 999px;
    padding: 0.28rem 0.6rem;
    font-size: 0.68rem;
    letter-spacing: 0.06rem;
    text-transform: uppercase;
    opacity: 0;
    transform: translateY(-6px);
    transition: opacity 0.2s ease, transform 0.2s ease;
    pointer-events: none;
  }

  .study-notes-page .card:hover .tooltip {
    opacity: 1;
    transform: translateY(0);
  }

  @media (max-width: 768px) {
    .study-notes-page {
      padding: 1rem 0.75rem 2rem;
    }

    .study-notes-page .hero {
      padding: 3rem 1rem 1.75rem;
    }

    .study-notes-page .content-wrap {
      padding: 1.2rem 0.9rem 1.5rem;
    }

    .study-notes-page .subtitle {
      font-size: 1rem;
    }
  }
</style>

<div class="study-notes-page">
  <div class="page-shell">
    <div class="hero">
      <div class="eyebrow">Learning Resources</div>
      <h2>Study Notes & Materials</h2>
      <p class="subtitle">
        Check my all notes that I learned over AI theories and practical applications, including deep learning, NLP, computer vision, and modern research concepts.
      </p>
    </div>

    <div class="content-wrap">
      <div class="note-intro">
        <p>Check my all notes that I learned over AI theories, mathematics, model design, and research-driven problem solving — organized for quick review and deeper understanding.</p>
      </div>

      <div class="card-container">
        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>DL (Part 1)</h3>
            <p>Explore the 1st part of Deep Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_1.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 1</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>DL (Part 2)</h3>
            <p>Explore the 2nd part of Deep Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_2.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 2</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>DL (Part 3)</h3>
            <p>Explore the 3rd part of Deep Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_3.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 3</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>DL (Part 4)</h3>
            <p>Explore the 4th part of Deep Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_4.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 4</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>DL (Part 5)</h3>
            <p>Explore the 5th part of Deep Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_Advanced_5.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 5</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>DL (CV)</h3>
            <p>Explore the Computer Vision part of Deep Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/DL_CV.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 6</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>DL (NLP)</h3>
            <p>Explore the Natural Language Processing part of Deep Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/NLP_DL.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 7</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>NLP with ML-1</h3>
            <p>Explore the Natural Language Processing 1st part of Machine Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/NLP_ML_1.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 8</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>NLP with ML-2</h3>
            <p>Explore the Natural Language Processing 2nd part of Machine Learning.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/NLP_ML_2.pdf" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 9</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>NLP Coding Basics</h3>
            <p>Explore the coding basics of Natural Language Processing.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/Hands-On-Natural-Language-Processing-with-Python-master.zip" target="_blank" rel="noopener noreferrer">Visit ZIP</a>
            <div class="tooltip">Material 10</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>Useful Projects</h3>
            <p>Explore GitHub project references and available learning materials.</p>
            <a href="https://github.com/mahirafserpavel/DL_NLP/blob/main/github_if_available.txt" target="_blank" rel="noopener noreferrer">Visit TXT</a>
            <div class="tooltip">Material 11</div>
          </div>
        </div>

        <div class="card">
          <div class="card-top"></div>
          <div class="card-content">
            <h3>PDF Books</h3>
            <p>Explore AI and machine learning books in PDF format.</p>
            <a href="https://github.com/mahirafserpavel/PDF" target="_blank" rel="noopener noreferrer">Visit PDF</a>
            <div class="tooltip">Material 12</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

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
