<h1 align="center">Owen Ashworth | AI Engineer Portfolio</h1>

<p align="center">
  A responsive single-page portfolio showcasing practical AI Engineer projects, deployed applications, technical skills, and a downloadable Curriculum Vitae.
</p>

<p align="center">
  <a href="https://ai-explorer25.github.io" target="_blank"><strong>Live Portfolio</strong></a>
  &nbsp;|&nbsp;
  <a href="https://github.com/AI-Explorer25" target="_blank"><strong>GitHub Profile</strong></a>
</p>

---

## Overview

This repository contains my professional portfolio website. It was created to present my AI Engineer project work in a clean, employer-ready format.

The website is based on the free **iPortfolio Bootstrap template** from BootstrapMade and has been customised into a focused single-page AI Engineer portfolio.

The site includes:

- a professional hero and about section
- a responsive technology logo grid
- featured AI project cards
- modal-based project details
- a downloadable PDF Curriculum Vitae
- a working Formspree contact form
- mobile-friendly navigation and layout

---

## Live Website

**Portfolio:**  
https://ai-explorer25.github.io

---

## Featured Projects

### Medical Radiology Summarization

A medical NLP project that generates concise radiology **IMPRESSION** summaries from chest X-ray **FINDINGS** text.

**Key work completed:**

- parsed raw XML radiology reports
- cleaned and prepared the dataset
- created train/test splits
- built and evaluated a baseline
- fine-tuned FLAN-T5-small
- evaluated model output using ROUGE
- built a FastAPI backend
- created an HTML interface
- deployed publicly on Hugging Face Spaces using Docker

**Tech stack:**  
Python, PyTorch, Transformers, FLAN-T5, ROUGE, FastAPI, Docker, Hugging Face Spaces

**Links:**

- Repository: https://github.com/AI-Explorer25/medical-radiology-summarization
- Live demo: https://ai-explorer64-medical-radiology-summarization.hf.space

---

### Visual Product Recommendations

A computer vision recommendation system that uses CLIP image embeddings and cosine similarity to return visually similar fashion products from an uploaded clothing image.

**Key work completed:**

- indexed and validated fashion product images
- removed unusable and duplicate images
- generated CLIP image embeddings
- implemented cosine similarity search
- added near-duplicate and diversity-aware filtering
- created final recommendation outputs
- built a Gradio web interface
- added an optional FastAPI endpoint
- deployed publicly on Hugging Face Spaces

**Tech stack:**  
Python, NumPy, Pandas, PyTorch, Transformers, CLIP, Gradio, FastAPI, Hugging Face Spaces

**Links:**

- Repository: https://github.com/AI-Explorer25/visual-product-recommendations
- Live demo: https://ai-explorer64-visual-product-recommendations.hf.space

---

## Portfolio Features

| Feature | Implementation |
|---|---|
| Single-page layout | Bootstrap-based SPA-style portfolio |
| Project details | Bootstrap modals instead of separate pages |
| Technology display | Responsive grid of technology logos |
| CV access | Downloadable `Owen_Ashworth_CV.pdf` |
| Contact form | Formspree-powered contact form |
| Deployment | GitHub Pages |
| Mobile support | Responsive layout and mobile navigation |

---

## Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap
- Bootstrap Icons

### Template and UI Libraries

- iPortfolio by BootstrapMade
- AOS animations
- Typed.js

### Deployment and Forms

- GitHub Pages
- Formspree

---

## Repository Structure

```text
AI-Explorer25.github.io/
│
├── index.html
├── README.md
├── .nojekyll
│
├── cv/
│   └── Owen_Ashworth_CV.pdf
│
└── assets/
    ├── css/
    ├── js/
    ├── vendor/
    └── img/
        ├── backgrounds/
        ├── profile/
        ├── projects/
        ├── favicon.png
        ├── apple-touch-icon.png
        └── logo.png
```

---

## Local Preview

Clone the repository:

```bash
git clone https://github.com/AI-Explorer25/AI-Explorer25.github.io.git
cd AI-Explorer25.github.io
```

Open `index.html` directly in a browser, or use a local development server such as the VS Code Live Server extension.

---

## Deployment Notes

The website is deployed through **GitHub Pages** from the `main` branch.

A `.nojekyll` file is included so GitHub Pages serves the project as a normal static Bootstrap site rather than processing it as a Jekyll site.

---

## Purpose

This portfolio was created as part of my AI Engineer traineeship showcase work. The aim is to present practical, employer-visible AI projects with clear explanations, deployed demos, source code links, and a concise technical profile.