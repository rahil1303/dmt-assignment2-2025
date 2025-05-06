## 📚 Dataset Access Liaison

To ensure everyone in the team can access the dataset easily — whether working locally or in the cloud — we support **two setup options**:  
1. Google Colab (no install required)  
2. Kaggle CLI (local development)

---

### ⚡ Option 1: Google Colab [Recommended]

Use our pre-configured Colab notebook to download and load the dataset directly from a shared Google Drive link.

👉 [Open the Colab Notebook](https://colab.research.google.com/drive/12TO_sHN2aT437rNhY4WNu7FEnKr-Xzax?usp=sharing)

This notebook will:
- Download the `dmt-2025-2nd-assignment.zip` from Google Drive
- Extract it into a local `/data` folder
- Load `training_set_VU_DM.csv` and `test_set_VU_DM.csv` into Pandas

✅ No setup required — just open and run.

---

### 🛠️ Option 2: Kaggle CLI (Local)

If you prefer working locally or need full control, use the **Kaggle CLI** to download the dataset.

#### Steps:

1. Join the private competition using this invite link:  
   [https://www.kaggle.com/t/44c6cb033eac40e2aec9d5ce0af03cb4](https://www.kaggle.com/t/44c6cb033eac40e2aec9d5ce0af03cb4)

2. Install the Kaggle CLI:
   ```bash
   pip install kaggle

3. Download the dataset:
   kaggle competitions download -c dmt-2025-2nd-assignment -p data

4. Extract it:
   unzip data/dmt-2025-2nd-assignment.zip -d data/

