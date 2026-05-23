---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version is available [here](../assets/CV_ZhengyangHu.pdf).

Education
======
* **Ph.D., Electrical and Computer Engineering**, The University of Hong Kong, 2023.08 – present
  * Advisors: Dr. Yanchao Yang & Prof. Kaibin Huang
* **B.Sc., Mathematics and Applied Mathematics**, School of the Gifted Young, University of Science and Technology of China (USTC), 2019.09 – 2023.06
  * Major-course GPA: 3.87 / 4.3

Research interests
======
* Foundation models for statistical inference (mutual information, dependency measurement)
* Training dynamics and interpretability of Transformers / LLMs
* Information theory and representation learning

Experience
======
* **Visiting Researcher**, Huawei HPC Group (RAFT) — LLM Training Dynamics & Interpretability, 2024.09 – 2026.01
  * Designed real-time representation-monitoring metrics for LLM pre-training; validated across multi-scale Transformers for early warning of training anomalies.
* **Quantitative Research Intern**, Chengqi Asset Management, 2022.08 – 2022.12
  * Built, backtested, and shipped 5 alpha factors integrated into the firm's factor / strategy library.

Selected competitions
======
* **Lingjun Investment Quant Competition** — A-Share Market Microstructure Prediction (Kaggle), 2026.03 – 2026.04
  * Team ranked **Top 13–15**. Predicted intraday multi-horizon returns across 500 A-share stocks from Level-2 high-frequency features; benchmarked XGBoost / LightGBM / GRU / LSTM / Transformer with Optuna tuning. Single XGBoost reached test R² = 0.030 (matching the runner-up's best single model).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Skills
======
* **Languages**: Python, C/C++, MATLAB, SQL
* **ML / DL**: PyTorch, distributed multi-GPU training (DeepSpeed / Megatron-style), Transformers, HuggingFace
* **Data science**: NumPy / Pandas, XGBoost, LightGBM, Optuna
* **Tools**: Linux, Git, Slurm, Docker
* **Languages (Human)**: Mandarin (native), English (TOEFL iBT 105, GRE 322)
