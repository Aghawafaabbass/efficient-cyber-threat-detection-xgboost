
# 🚨 Efficient Cyber Threat Detection with XGBoost on Compact Network Traffic Datasets

[![DOI](https://zenodo.org/badge/1017939446.svg)](https://doi.org/10.5281/zenodo.18242426)

Citation & Publication
This project is part of a published research paper. You can read the full publication here:

🔗 Agha, W. A. (2025). Efficient Cyber Threat Detection with XGBoost on Compact Network Traffic Datasets. Zenodo: https://doi.org/10.5281/zenodo.15861018 . 

## 📌 Abstract

The exponential growth of Internet of Things (IoT) devices demands **lightweight Intrusion Detection Systems (IDS)** to protect against **malware** and **DDoS attacks**. This repository presents a highly efficient IDS built using **XGBoost** on a **compact 379.72 KB subset** (2,000 records) of the **UNSW-NB15 dataset**.

### 🔑 Key Results
- ✅ **95.00% Test Accuracy**
- 📊 **91.80% Validation Accuracy**
- 🔍 High **Precision** and **Recall**
- 🚀 **Deployment-ready for edge/IoT devices**

By excluding the `attack_cat` column to avoid data leakage and performing feature importance analysis, key features such as `sttl`, `proto_tcp`, and `service_dns` were identified.

---

## 🧠 Key Contributions

- **Lightweight IDS Design**: Efficient XGBoost implementation using only 379.72 KB of data.
- **Data Integrity**: Methodologically sound by excluding leakage-prone columns.
- **Interpretability**: Visual feature importance analysis provides actionable insights.

---

## 📈 Results Summary

| Metric     | Test Set (400 records) | Validation Set (1,000 records) |
|------------|------------------------|---------------------------------|
| Accuracy   | 95.00%                 | 91.80%                         |
| Precision  | 94.15%                 | 90.35%                         |
| Recall     | 96.02%                 | 93.60%                         |
| F1-Score   | 95.07%                 | 91.94%                         |

---

## 🔬 Visualizations

- 📉 **Confusion Matrices**:  
  - `confusion_matrix.png`  
  - `validation_confusion_matrix.png`

- 📊 **ROC Curve**:  
  - AUC ≈ **0.92** (`roc_curve.png`)

- 🌟 **Feature Importance**:  
  - `feature_importance.png`

---

## 🧪 Future Work

- Evaluate on **imbalanced datasets**
- Apply **quantization and compression** for real-time inference
- Expand **hyperparameter tuning**
- Test on modern datasets like **CICIDS2017**

---

## 📂 File Description

| File | Description |
|------|-------------|
| `Cybersecurity_XGBoost_UNSW.ipynb` | Main Jupyter Notebook with code, visuals, and results |
| `confusion_matrix.png` | Confusion Matrix (Test Data) |
| `validation_confusion_matrix.png` | Confusion Matrix (Validation Data) |
| `roc_curve.png` | Receiver Operating Characteristic Curve |
| `feature_importance.png` | Plot showing top contributing features |

---

## 📥 Dataset Access

Download the dataset subset used from this link:  
[UNSW-NB15 Dataset (SharePoint)](https://unsw-my.sharepoint.com/personal/z5025758_ad_unsw_edu_au/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fz5025758%5Fad%5Funsw%5Fedu%5Fau%2FDocuments%2FUNSW%2DNB15%20dataset%2FCSV%20Files%2FTraining%20and%20Testing%20Sets&ga=1)

---

## 🚀 How to Run This Project

### ✅ Option 1: Open in Google Colab (No Setup Needed)
1. Click on the notebook `Cybersecurity_XGBoost_UNSW.ipynb`
2. Replace `github.com` with `colab.research.google.com/github/` in the URL  
   👉 Example:  
```

[https://colab.research.google.com/github/YOUR-USERNAME/YOUR-REPO/blob/main/Cybersecurity\_XGBoost\_UNSW.ipynb](https://colab.research.google.com/github/YOUR-USERNAME/YOUR-REPO/blob/main/Cybersecurity_XGBoost_UNSW.ipynb)

````
3. Click `Runtime > Run All` or press `Ctrl+F9`

---

### ✅ Option 2: Run Locally

#### Requirements
- Python 3.7+
- Jupyter Notebook or Lab

#### Install Required Libraries
```bash
pip install pandas numpy xgboost matplotlib seaborn scikit-learn
````

#### Launch the Notebook

```bash
jupyter notebook
```

Then open `Cybersecurity_XGBoost_UNSW.ipynb` and run the cells.

---

## 📌 Index Terms

`XGBoost`, `Intrusion Detection System (IDS)`, `Internet of Things (IoT)`, `UNSW-NB15 Dataset`, `Network Security`, `Compact Dataset`

## 👨‍🏫 Author

**Agha Wafa Abbas**
Lecturer, School of Computing, Arden University, UK
Lecturer, IVY College of Management Sciences, Pakistan
📧 [awabbas@arden.ac.uk](mailto:awabbas@arden.ac.uk) | [wafa.abbas.lhr@rootsivy.edu.pk](mailto:wafa.abbas.lhr@rootsivy.edu.pk)

---

## 📜 License

* 📄 **Code**: Licensed under the [MIT License](LICENSE)


