# FETAL-GAUGE
### A Benchmark for Assessing Vision-Language Models in Fetal Ultrasound

[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2512.22278)

---

## Overview

Fetal ultrasound is a cornerstone of prenatal care, yet its interpretation is highly operator-dependent and clinically challenging. Although Vision-Language Models (VLMs) have shown impressive results in natural images and other medical imaging domains, their ability to understand fetal ultrasound remains largely unexplored.

**FETAL-GAUGE** introduces the first large-scale benchmark designed to systematically evaluate vision-language models on clinically relevant fetal ultrasound tasks.

---
## Key Features

- First benchmark for evaluating VLMs on fetal ultrasound
- Over **42,000** fetal ultrasound images
- Over **93,000** question–answer pairs
- Covers a wide range of clinically meaningful tasks
- Enables standardized and reproducible evaluation
- Highlights critical performance gaps in current VLMs

---


## Benchmark Tasks

FETAL-GAUGE formulates all tasks as visual question-answering (VQA) problems to enable unified evaluation across models.

| Task Category | Description |
|--------------|-------------|
| Plane Identification | Identification of standard anatomical planes |
| Anatomical Recognition | Recognition of fetal organs and structures |
| Visual Grounding | Localization of anatomical structures |
| Orientation Understanding | Inference of fetal orientation and position |
| View Conformity | Assessment of clinical acquisition standards |

---

## Benchmark Findings

We evaluate a diverse set of general-purpose and medical vision-language models using FETAL-GAUGE.

Key findings include:

- State-of-the-art VLMs struggle with fetal ultrasound understanding
- Best-performing models achieve only ~55% accuracy
- Significant weaknesses in:
  - Fine-grained anatomical reasoning
  - Visual grounding in ultrasound

These results highlight the need for domain-specific multimodal modeling.

---

Data will be published soon!


## ✒️ Citation
If you find our work useful, please consider giving our repo a star and citing our paper as follows:
```bibtex
@article{alasmawi2025fetal,
  title={FETAL-GAUGE: A Benchmark for Assessing Vision-Language Models in Fetal Ultrasound},
  author={Alasmawi, Hussain and Saeed, Numan and Yaqub, Mohammad},
  journal={arXiv preprint arXiv:2512.22278},
  year={2025}
}

