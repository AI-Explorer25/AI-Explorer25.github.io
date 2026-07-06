# Owen Ashworth | AI Engineer Portfolio

<p align="center">
  <a href="https://ai-explorer25.github.io" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Portfolio-ai--explorer25.github.io-0A66C2?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live Portfolio">
  </a>
  <a href="https://github.com/AI-Explorer25" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-AI--Explorer25-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile">
  </a>
</p>

## Overview

This repository contains my professional portfolio website, built to showcase my AI Engineer projects, technical skills, deployed applications, and Curriculum Vitae.

The site is based on the free **iPortfolio Bootstrap template** from BootstrapMade and has been customised into a clean, single-page AI Engineer portfolio.

## Live Website

**Portfolio:**  
https://ai-explorer25.github.io

## Featured Projects

### Medical Radiology Summarization

A medical NLP project that generates concise radiology **IMPRESSION** summaries from chest X-ray **FINDINGS** text.

**Highlights:**

- XML radiology report parsing
- data cleaning and train/test preparation
- baseline evaluation
- FLAN-T5-small fine-tuning
- ROUGE evaluation
- FastAPI backend
- HTML interface
- Docker and Hugging Face Spaces deployment

**Tech stack:** Python, PyTorch, Transformers, FLAN-T5, ROUGE, FastAPI, Docker, Hugging Face Spaces

**Repository:**  
https://github.com/AI-Explorer25/medical-radiology-summarization

**Live demo:**  
https://ai-explorer64-medical-radiology-summarization.hf.space

---

### Visual Product Recommendations

A computer vision recommendation system that uses CLIP image embeddings and cosine similarity to return visually similar fashion products from an uploaded clothing image.

**Highlights:**

- image validation and cleaning
- duplicate image detection
- CLIP image embedding generation
- cosine similarity search
- near-duplicate filtering
- diversity-aware recommendations
- Gradio web interface
- optional FastAPI endpoint
- Hugging Face Spaces deployment

**Tech stack:** Python, NumPy, Pandas, PyTorch, Transformers, CLIP, Gradio, FastAPI, Hugging Face Spaces

**Repository:**  
https://github.com/AI-Explorer25/visual-product-recommendations

**Live demo:**  
https://ai-explorer64-visual-product-recommendations.hf.space

## Portfolio Features

- Responsive single-page layout
- AI Engineer-focused hero, about, projects, technologies, CV, and contact sections
- Project screenshots and modal-based project details
- Responsive technology logo grid
- Downloadable PDF Curriculum Vitae
- Working contact form using Formspree
- External project and demo links opening in new tabs
- Mobile-friendly navigation and layout

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap
- Bootstrap Icons
- AOS animations
- Typed.js
- Formspree
- GitHub Pages

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

## Local Preview

Clone the repository:

```bash
git clone https://github.com/AI-Explorer25/AI-Explorer25.github.io.git
cd AI-Explorer25.github.io
```

Open `index.html` directly in a browser, or use a local development server such as the VS Code Live Server extension.

## Deployment

The site is deployed through **GitHub Pages** from the `main` branch.

A `.nojekyll` file is included so the repository is served as a normal static Bootstrap site rather than being processed as a Jekyll site.

## Notes

This portfolio was created as part of my AI Engineer traineeship showcase work. The aim is to present practical, employer-visible AI projects with clear descriptions, deployed demos, source code links, and a concise technical profile.