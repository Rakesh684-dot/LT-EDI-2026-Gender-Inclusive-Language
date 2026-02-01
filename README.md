# LT-EDI-2026-Gender-Inclusive-Language
LT-EDI@ACL 2026: Gender Inclusive Language Generation. Advancing research in bias-free text by transforming gendered input into inclusive alternatives across 5 languages (EN, DE, ES, TA, KN). Includes Subtask A (Inclusive Rewriting) and Subtask B (Counterfactuals) to mitigate LLM stereotypes while preserving meaning and fluency.
# 🌈 Gender Inclusive Language Generation (LT-EDI @ ACL 2026)

## 🏗️ Project Hierarchy

```text
├── data/                   # Multilingual datasets (EN, DE, ES, TA, KN)
│   ├── raw/                # Original competition data
│   └── processed/          # Cleaned data for model training
├── notebooks/              # Jupyter Notebooks for experimentation
│   ├── 01_data_cleaning.ipynb
│   ├── 02_model_training.ipynb
│   └── 03_evaluation.ipynb
├── src/                    # Core Python source code
│   ├── preprocessing.py    # Text normalization and bias detection
│   ├── transformer_model.py # mT5 / Flan-T5 implementation
│   └── utils.py            # Helper functions
├── models/                 # Saved model weights and configurations
└── results/                # Performance metrics and GIFI scores

<p align="center">
  <img src="https://img.shields.io/badge/Task-LT--EDI%20%40%20ACL%202026-blueviolet?style=for-the-badge&logo=acl" />
  <img src="https://img.shields.io/badge/Focus-AI%20Fairness%20%26%20Ethics-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Languages-EN%20%7C%20DE%20%7C%20ES%20%7C%20TA%20%7C%20KN-orange?style=for-the-badge" />
</p>

---

## 📌 Project Overview
This repository contains our team's research and implementation for the **Gender Inclusive Language Generation** shared task. We aim to advance bias-free text generation by transforming gendered input into inclusive, neutral alternatives while preserving meaning and fluency.

> [!IMPORTANT]
> This project addresses the tendency of LLMs to amplify gender stereotypes and misgendering patterns found in training data.

---

## 🛠️ Task Breakdown

### 🔹 Subtask A: Inclusive Rewriting
Transforming gender-biased or marked sentences into fully inclusive versions.
* **Example:** *"The fireman saved the little girl"* → *"The firefighter saved the child"*
* **Languages:** English, German, Spanish, Tamil, and Kannada.

### 🔹 Subtask B: Counterfactual Generation
Generating empathetic and persuasive counter-narratives to challenge gender-biased statements (English only).
* **Example:** *"Women are not good at math"* → *"People of all genders can be skilled in mathematics..."*

---

## 🚀 Technical Approach
We utilize a **Hybrid LLM-as-a-Judge** framework to evaluate our systems across two key metrics:
1. **GIFI (Gender Inclusive Fairness Index):** Effectiveness in removing bias.
2. **Semantic Similarity:** Ensuring no hallucinations while preserving intent.

### 💻 Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-Hugging%20Face-orange?style=for-the-badge)

---

## 🤝 Connect With Me
<p align="left">
<a href="https://www.linkedin.com/in/YOUR_USERNAME" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://twitter.com/YOUR_USERNAME" target="_blank"><img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
<a href="https://www.instagram.com/YOUR_USERNAME" target="_blank"><img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
</p>

---

<p align="center">
  <i>Developed for the LT-EDI@ACL 2026 Shared Task</i>
</p>
