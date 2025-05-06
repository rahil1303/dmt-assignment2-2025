# 📓 DMT Assignment 2 – Notebook Workspace

This folder contains all exploratory and development notebooks related to **Assignment 2** of the Data Mining Techniques course (VU Amsterdam, 2025).

Assignment 2 focuses on building a hotel recommender system using Expedia data. The tasks below reflect the official CRISP-DM workflow specified in the assignment document.

---

## ✅ Task Breakdown (Notebook Work)

### 1. 📊 Business Understanding
- Understand the goal of ranking hotel listings by booking likelihood
- Study the structure of the Expedia search session
- Write a short *Related Work* section (e.g., prior approaches from Kaggle forums)

### 2. 🧠 Data Understanding
- Load and inspect training/test data
- Investigate key features like `prop_location_score1`, `price_usd`, and booking/click labels
- Summarize missing values and distributions
- Analyze groupings by `srch_id` and `prop_id`

### 3. 🧹 Data Preparation
- Handle missing values
- Create new features (e.g., price differences, normalized scores)
- Rank hotels per search
- Optionally: sample from the dataset for prototyping
- Prepare hold-out validation sets for training

### 4. 🤖 Modeling & Evaluation
- Try at least two models:
  - A baseline ranker (e.g. sort by location score)
  - A learning-to-rank model (e.g. LightGBM, XGBoost)
- Tune model parameters
- Use **NDCG@5** as the evaluation metric
- Evaluate ranking performance using grouped validation

### 5. 🏁 Deployment & Ethics
- Discuss how Expedia could deploy the model in a scalable way
- Detect possible biases (e.g., against low-star hotels or price tiers)
- Apply an ethical AI technique (e.g., reweighting, group fairness metrics)
- Evaluate post-mitigation performance

---

## ⚠️ Notes
- Keep notebooks modular (one per task)
- Avoid hardcoding paths; use `../data/` or relative links
- Make heavy notebooks Colab-compatible

---

## 📦 Output from These Tasks
- Model training logs and validation metrics
- Preprocessed training and test data
- Kaggle-compatible submission file
- Visualizations and tables for use in the scientific report


