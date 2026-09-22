---
permalink: /
title: false
excerpt: "Yicun Yang is a Ph.D. student in Artificial Intelligence at HKUST(GZ), working on discrete diffusion language models and efficient AI systems."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home-hero">
  <p class="home-hero__eyebrow">Ph.D. Student in Artificial Intelligence · HKUST(GZ)</p>
  <h1>Yicun Yang</h1>
  <p class="home-hero__lead">I build efficient language-model systems that make diffusion-based generation faster, more flexible, and easier to deploy.</p>
  <div class="home-hero__actions">
    <a class="btn home-button home-button--primary" href="#research">Explore my research</a>
    <a class="btn home-button" href="/publications/">View publications</a>
  </div>
  <div class="home-tags" aria-label="Research areas">
    <span>Discrete diffusion LLMs</span>
    <span>Efficient inference</span>
    <span>Efficient training</span>
  </div>
</div>

<section id="about" class="home-section">
  <div class="section-kicker">About</div>
  <h2>Researching efficient and practical AI</h2>
  <p>I am a first-year Ph.D. student in the AI Thrust at <a href="https://www.hkust-gz.edu.cn/">The Hong Kong University of Science and Technology (Guangzhou)</a>, advised by Prof. <a href="https://zhanglinfeng.tech/">Linfeng Zhang</a> and Prof. <a href="https://xuminghu.github.io/">Xuming Hu</a>. I am a member of the <a href="https://zhanglinfeng.tech/">Efficient and Precision Intelligent Computing (EPIC) Lab</a>.</p>
  <p>Previously, I studied Software Engineering at Harbin Institute of Technology and conducted research at Shanghai Jiao Tong University. My work sits at the intersection of large language models, diffusion modeling, and systems efficiency.</p>
</section>

<section id="research" class="home-section">
  <div class="section-kicker">Research</div>
  <h2>What I work on</h2>
  <div class="research-grid">
    <article class="research-card">
      <div class="research-card__number">01</div>
      <h3>Efficient diffusion LLMs</h3>
      <p>New inference paradigms for discrete diffusion language models, including variable-length generation and block-wise denoising.</p>
    </article>
    <article class="research-card">
      <div class="research-card__number">02</div>
      <h3>Fast and memory-aware inference</h3>
      <p>Adaptive caching, cache eviction, and speculative techniques that reduce latency and memory use without sacrificing quality.</p>
    </article>
    <article class="research-card">
      <div class="research-card__number">03</div>
      <h3>Efficient AI systems</h3>
      <p>Training and serving methods that turn capable foundation models into practical systems for real-world workloads.</p>
    </article>
  </div>
</section>

<section id="selected-work" class="home-section home-section--soft">
  <div class="section-kicker">Selected work</div>
  <h2>Recent research</h2>
  <div class="work-list">
    <article class="work-card">
      <div>
        <p class="work-card__meta">ICML 2026 · Efficient inference</p>
        <h3><a href="https://arxiv.org/abs/2506.06295">dLLM-Cache: Accelerating Diffusion Large Language Models with Adaptive Caching</a></h3>
        <p>An adaptive cache for diffusion LLMs that reuses stable computation across denoising steps and brings latency closer to autoregressive models.</p>
      </div>
      <a class="work-card__code" href="https://github.com/maomaocun/dLLM-cache">Code ↗</a>
    </article>
    <article class="work-card">
      <div>
        <p class="work-card__meta">2025 · Diffusion language models</p>
        <h3><a href="https://arxiv.org/abs/2510.24605">Diffusion LLM with Native Variable Generation Lengths</a></h3>
        <p>A diffusion language model that predicts the end of generation natively, removing the need to fix the output length before decoding.</p>
      </div>
      <a class="work-card__code" href="https://github.com/maomaocun/dLLM-Var">Code ↗</a>
    </article>
    <article class="work-card">
      <div>
        <p class="work-card__meta">2025 · Data-efficient learning</p>
        <h3><a href="https://arxiv.org/abs/2502.20653">Dataset Distillation with Neural Characteristic Function</a></h3>
        <p>A distribution-matching method that uses a learned characteristic-function discrepancy to improve synthetic data quality and efficiency.</p>
      </div>
      <a class="work-card__code" href="https://github.com/gszfwsb/NCFM">Code ↗</a>
    </article>
  </div>
  <p class="section-more"><a href="/publications/">See all publications →</a></p>
</section>

<section id="news" class="home-section">
  <div class="section-kicker">Updates</div>
  <h2>News</h2>
  <ul class="news-list">
    <li><time>2026.09</time><span>Started my Ph.D. in Artificial Intelligence at HKUST(GZ).</span></li>
    <li><time>2026.05</time><span><a href="https://github.com/maomaocun/dLLM-cache">dLLM-Cache</a> was accepted to ICML 2026.</span></li>
    <li><time>2025.10</time><span>Released <a href="https://github.com/maomaocun/dLLM-Var">dLLM-Var</a>, with code and models available online.</span></li>
    <li><time>2025.05</time><span>Released the code for <a href="https://github.com/maomaocun/dLLM-cache">dLLM-Cache</a>.</span></li>
  </ul>
</section>

<section id="contact" class="home-section home-contact">
  <div class="section-kicker">Contact</div>
  <h2>Let's connect</h2>
  <p>I am happy to discuss efficient AI, diffusion language models, research collaboration, and open-source projects.</p>
  <p><a class="btn home-button home-button--primary" href="mailto:yangyicun187@gmail.com">Email me</a> <a class="btn home-button" href="https://scholar.google.com.hk/citations?user=zKnktocAAAAJ&hl=zh-CN">Google Scholar</a> <a class="btn home-button" href="https://www.alphaxiv.org/@yicun-yang">alphaXiv</a></p>
</section>
