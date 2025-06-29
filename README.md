#  AI-Internship-Portfolio  

> A 12-week, 8-project sprint to build an ML/DL portfolio, sharpen DS-Algo
> skills, and land a summer internship.  
> **Status:** Day 1 / 84 | Last updated: ⟨2025-06-29⟩

[![CI](https://github.com/shazabhassan/100-Days-of-AI-Internship/actions/workflows/ci.yml/badge.svg)](link)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📑 Table of Contents
1. Why this repo?
2. Roadmap & progress
3. Quick start
4. Project directory
5. Contributing & contact

---

### 1 · Why this repo?
I am spending 12 weeks building real, end-to-end
AI projects. Keeping everything public forces good software practices and
creates a single link I can send to recruiters or mentors.

### 2 · Roadmap & Progress
| Week | Theme | Folder | Status | Main Metric |
|------|-------|--------|--------|-------------|
| 1    | Supervised Learning | `01_titanic_survival` | ✅ complete | ROC-AUC 0.81 |
| 2    | Regression / FE     | `02_house_prices`     | 🔄 active   | RMSE 0.117   |

Full syllabus: [`docs/roadmap.md`](docs/roadmap.md)

### 3 · Quick Start
```bash
git clone https://github.com/⟨GH_USERNAME⟩/ai-internship-portfolio.git
cd ai-internship-portfolio

conda env create -f environment.yml      # or: pip install -r requirements.txt
conda activate ai-internship

make test        # run unit tests in every project
make lint        # flake8 + black
```

### 4 · Project Directory
```
projects/
├── 01_titanic_survival/  → classical ML starter  
├── 02_house_prices/      → regression & XGBoost  
├── 03_customer_segmentation/ → PCA + clustering  
└── …  
```
Each folder contains its own README, notebooks, `src/`, tests, and small sample
data. Heavy artefacts are stored in Kaggle, Google Drive, or HuggingFace Hub.

### 5 · Contributing & Contact
Open an issue or find me on [LinkedIn](⟨www.linkedin.com/in/shazab-hassan-2aa8a3281⟩).  
PRs for typo fixes, new visualisations, or alternative model notebooks are
welcome!

---

© ⟨2025⟩ ⟨SHAZAB HASSAN⟩ — MIT License
