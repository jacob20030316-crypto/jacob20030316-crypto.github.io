---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my full CV [here](/files/DehaoWu_Resume.pdf).

## Education

* **M.S. in Information Management**, University of Illinois Urbana-Champaign, 2025 – 2027
* **B.S. in Artificial Intelligence**, Southwest Petroleum University, 2021 – 2025
  * GPA: 90.1/100 (Ranked 1st/77)

## Work Experience

* **LLM Algorithm Intern** — IICT, Chinese Academy of Sciences (Apr 2025 – Jun 2025)
  * Enhanced GraphRAG for Chinese financial, legal, and research domains by integrating structured domain ontologies and fine-tuning Qwen3 for domain-specific NER, improving entity extraction by 8–10%.
  * Built production-ready vertical Q&A assistants that reduced hallucination by 25%+ and improved long-chain reasoning accuracy by 20%.
  * Contributed to a High-Tech Enterprise Qualification Predictor using semi-supervised learning and LLMs (92%–95%+ accuracy).

* **Data Analysis Intern** — JD Group Inc, Retail AIGC Product Development (Aug 2024 – Oct 2024)
  * Designed a RAG-based Q&A system using LangChain + ChatOpenAI, achieving +14% accuracy on multi-hop queries.
  * Built a data pipeline with 22% noise reduction and 18% deduplication; developed a Django dashboard for sentiment/topic visualization.

## Skills

* **Programming & Data Science**: Python, R, SQL, Matlab, C, Pandas, NumPy, Matplotlib
* **Machine Learning & Tools**: TensorFlow, PyTorch, Scikit-learn, RAG, Docker, Linux

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
