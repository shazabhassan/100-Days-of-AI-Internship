# 12-Week AI-Internship Roadmap 📆

This document is the authoritative syllabus for the **AI-Internship-Portfolio** repository.
Scroll, skim, or search (`Ctrl/⌘ + F`) for any topic.

------------------------------------------------------------------------
Legend
------------------------------------------------------------------------
✅ = done 🔄 = in progress ⏳ = queued  
🛠  Deliverable 🎯 Key Concept 🎥 Resource

------------------------------------------------------------------------
WEEK-BY-WEEK PLAN
------------------------------------------------------------------------

## WEEK 0 · Setup Weekend
🛠  Install Anaconda / Miniconda, VS Code, Git, Docker  
🛠  Create GitHub repo & push initial commit  
🛠  `environment.yml` + `.gitignore` + MIT LICENSE  
🎯  Reproducible environment, version control basics  
🎥  Corey Schafer YouTube – Git/GitHub Crash-Course

---

## WEEK 1 · Supervised-Learning Foundations
1. Andrew Ng Coursera ML – Lectures 1-2  
2. Kaggle micro-course: Intro to ML  
3. Project 01 `projects/01_titanic_survival/`  
   • notebook: EDA → feature engineering → logistic regression  
   • unit test: accuracy > 0.75 on val set  
4. Write LinkedIn post: “Confusion Matrix explained in 60 s”.

🎯  train/val/test split • overfitting • accuracy vs ROC-AUC  
🎥  StatQuest – Confusion Matrix

---

## WEEK 2 · Regression & Feature Engineering
Tasks  
• Read Hands-On ML Ch. 1-3  
• Project 02 `house_prices` – baseline linear → ridge/Lasso → RandomForest → XGBoost  
• 5 LeetCode Easy + 2 Medium each day

🛠  Markdown report comparing RMSEs  
🎯  Regularisation, cross-validation, feature pipelines  
🎥  Kassir (YouTube) – XGBoost in 15 min

---

## WEEK 3 · Model Evaluation & Statistics
Tasks  
• Metrics deep dive: RMSE, MAE, F1, PR-AUC  
• Implement k-fold CV from scratch in `utils/cv.py`  
• Mini-project: Breast-cancer detection with class imbalance + SMOTE

🎯  Bias/variance trade-off, p-values, hypothesis testing  
🎥  3Blue1Brown – Confidence Intervals

---

## WEEK 4 · Unsupervised Learning
Tasks  
• Algorithms: k-means, DBSCAN, hierarchical, PCA, t-SNE  
• Project 03 `customer_segmentation`  
   – Visualise PCA 2-D plot  
   – Silhouette score > 0.45  

🎯  Dimensionality reduction, distance metrics  
🎥  StatQuest – PCA Clearly Explained

---

## WEEK 5 · Neural Networks w/ PyTorch
Tasks  
• Coursera DL Spec C1  
• Code perceptron & 2-layer MLP from scratch (`numpy_only_nn.py`)  
• Project 04 `mnist_classifier` – > 98 % accuracy

🎯  Activation functions, forward/back-prop, gradients  
🎥  Andrej Karpathy – Neural Nets: A 4-hour Playlist

---

## WEEK 6 · CNNs & Transfer Learning
Tasks  
• fast.ai Part 1 – Lessons 1-2  
• Project 05 `dogs_vs_cats`  
   – Transfer-learn ResNet34, fine-tune last blocks  
   – Document LR finder plot  

🎯  Filters/kernels, parameter freezing, LR scheduling  
🎥  fast.ai Lesson 2 video

---

## WEEK 7 · NLP: Classical → Transformers
Tasks  
• Read “Illustrated BERT” (jalammar)  
• Project 06 `twitter_sentiment`  
   – TF-IDF + LogReg baseline  
   – DistilBERT fine-tune (<2 h on Colab)  
   – Streamlit demo `/capstone/app.py`  

🎯  Tokenisation, attention, padding/masking  
🎥  Jay Alammar – Visualizing BERT

---

## WEEK 8 · Model Serving & Basic MLOps
Tasks  
• Learn FastAPI + Docker basics  
• Wrap Sentiment model as REST API  
• Set up GitHub Actions: lint + pytest + docker build  
• Record 5-min screen-cast, post on YouTube

🎯  Containers, REST, CI/CD  
🎥  Sebastián Ramírez – FastAPI in 20 min

---

## WEEK 9 · Recommendation Systems
Tasks  
• Stanford CS246 Lectures 1-3  
• Project 07 `movielens_recsys`  
   – Matrix Factorisation (surprise) vs Neural CF (PyTorch)  
   – Metric: HR@10 > 0.62  

🎯  Implicit vs explicit feedback, cold-start, ranking metrics  
🎥  Google IO 2020 – Building Large-Scale Recommenders

---

## WEEK 10 · Scalable Data & System Design
Tasks  
• Read Google “Rules of ML”  
• PySpark mini-job in Colab: join & aggregate 10 M fake rows  
• System-design doc: “Image search service for 10 M queries/day” → `docs/system_design/image_search.md`

🎯  Feature stores, offline vs online pipelines, sharding  
🎥  Chip Huyen – ML System Design Crash-Course

---

## WEEK 11 · Capstone Planning
Tasks  
• Choose domain problem (medical, finance, climate, etc.)  
• Open GitHub Project board with user stories & tasks  
• Dataset acquisition + exploratory notebook

🎯  Scoping, MVP definition, dataset licensing  
🎥  Lewis Catarino – How to scope an ML project

---

## WEEK 12 · Capstone Build & Showcase
Tasks  
• Train, evaluate, deploy (Render/HF Spaces/AWS Free Tier)  
• Write 800-word Medium article & cross-post on LinkedIn  
• Pin capstone + 2 best mini-projects on GitHub profile  
• Reach out to 5 alumni for referral chats

🎯  End-to-end pipeline, storytelling, networking  
🎥  Josh Starmer – Presenting ML Results to an Audience

------------------------------------------------------------------------
CONTINUOUS TRACKS (parallel)
------------------------------------------------------------------------
1. DS-Algo Prep  
   • Mon/Wed/Fri: Arrays/Strings  
   • Tue: Trees/Graphs  
   • Thu: DP  
2. Communication  
   • Sunday: 15-min self-recorded weekly recap, critique filler words  
3. Networking  
   • 2 LinkedIn coffee-chat requests per week  
4. Open-Source  
   • 2 doc PRs to libraries you use (e.g., scikit-learn, HuggingFace)

------------------------------------------------------------------------
RESOURCES AT A GLANCE
------------------------------------------------------------------------
Courses   Andrew Ng ML + DL Spec • fast.ai • Kaggle Micro-Courses  
Books     Hands-On ML (Geron) • Machine Learning Engineering (Burkov)  
Videos    StatQuest • 3Blue1Brown • Chip Huyen • Lilian Weng  
Tools     Colab • scikit-learn • PyTorch • FastAPI • Docker • GitHub Actions

---

*Last updated: 2025-06-29 – © SHAZAB HASSAN*