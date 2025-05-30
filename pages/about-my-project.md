---
layout: project
title: About My Project
permalink: /about-my-project.html

subtitle: Deep Learning & Healthcare
project_title: "EcgNet: A Hybrid Multimodal Deep Learning Approach for Cardiovascular Disease (CVD) Diagnosis"

problem: |
  Cardiovascular disease (CVD) remains a leading cause of morbidity and mortality worldwide. Accurate and early diagnosis is critical for effective intervention, but current automated ECG analysis systems often struggle with limited interpretability, algorithmic bias, and suboptimal performance across diverse patient populations. There is a need for robust, interpretable, and equitable AI models that can leverage the full spectrum of ECG signal information to improve diagnostic accuracy and fairness.

approach: |
  The project follows a four-phase pipeline:

  - <b>Signal Preprocessing:</b> Clean ECG signals using Butterworth bandpass filtering and wavelet denoising to enhance data quality.

  - <b>Hybrid Deep Learning Modeling:</b> Develop a multimodal model combining 1D-CNNs (time-domain), 2D-CNNs (time-frequency), and LSTMs (temporal dependencies).

  - <b>Interpretability and Fairness:</b> Use explainable AI tools (SHAP, LIME) and bias mitigation strategies to ensure model transparency and equity.

  - <b>Validation and Benchmarking:</b> Test and benchmark the system on public ECG datasets, comparing its performance to existing methods.

  We will primarily use PyTorch for this project.

outcome: |
  By the end of this project, we aim to have a working deep learning model that can accurately diagnose cardiovascular disease from ECG data. All code and documentation will be made open-source to support further research and reproducibility. We will also generate clear visualizations and explanations to show how the model makes its decisions and to ensure its fairness across different patient groups. Finally, our results and key insights will be shared in a poster presentation at the research symposium.

final_report_url: https://dl.icdst.org/pdfs/files/22e390b2eb0c8e951f3a742fda5b2d1d.pdf

grad_mentor:
  name: Sudip Sharma
  linkedin: https://www.linkedin.com/in/nxxis/

faculty_mentor:
  name: Dr. Timothy Oladunni
  linkedin: https://www.linkedin.com/in/timothyoladunni/
---