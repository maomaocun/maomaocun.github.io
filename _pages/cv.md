---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

<div class="cv-print-header">
  <h1>Yicun Yang</h1>
  <p>Ph.D. Student in Artificial Intelligence · HKUST(GZ)</p>
  <p>yangyicun187@gmail.com · maomaocun.github.io</p>
</div>

<p class="cv-download"><a class="btn home-button home-button--primary" href="/files/Yicun_Yang_CV.pdf" download>Download CV (PDF)</a></p>

<p class="cv-links"><a href="mailto:yangyicun187@gmail.com">Email</a> · <a href="https://scholar.google.com.hk/citations?user=zKnktocAAAAJ&hl=zh-CN">Google Scholar</a> · <a href="https://github.com/maomaocun">GitHub</a></p>

## Education

- **Ph.D. in Artificial Intelligence**, The Hong Kong University of Science and Technology (Guangzhou), AI Thrust, 2026–present. Primarily supervised by Prof. Linfeng Zhang and co-supervised by Prof. Xuming Hu.
- **B.Eng. in Software Engineering**, Harbin Institute of Technology, 2022–2026.

## Research experience

- **Research Intern**, Efficient and Precision Intelligent Computing (EPIC) Lab, Shanghai Jiao Tong University, 2024–2026. Supervised by Prof. Linfeng Zhang.

## Research interests

Discrete diffusion language models · efficient LLM inference · adaptive caching · block-wise denoising · speculative decoding · efficient training and serving.

## Open source

- [dLLM-Cache](https://github.com/maomaocun/dLLM-cache) — adaptive caching for diffusion LLM inference.
- [dLLM-Var](https://github.com/maomaocun/dLLM-Var) — native variable-length generation for diffusion LLMs.
- [dLLM-Factory](https://github.com/maomaocun/dLLM-Factory) — tools for training diffusion language models.

## Publications

<ul class="cv-publications">{% assign papers = site.publications | sort: "date" | reverse %}{% for post in papers %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Links

[Google Scholar](https://scholar.google.com.hk/citations?user=zKnktocAAAAJ&hl=zh-CN) · [alphaXiv](https://www.alphaxiv.org/@yicun-yang) · [GitHub](https://github.com/maomaocun)
