Efficient Cyber Threat Detection with XGBoost on Compact Network Traffic Datasets

📌 Abstract
The increasing number of Internet of Things (IoT) devices necessitates the use of lightweight intrusion detection systems (IDS) to defend against malware and Distributed Denial of Service (DDoS) attacks. This repository contains the implementation of an IDS using XGBoost on a compact 379.72 KB subset of the UNSW-NB15 dataset (2,000 records). The model achieves:

✅ 95.00% test accuracy

📊 91.80% validation accuracy

🔍 High precision and recall

🚀 Deployment-ready for IoT devices

By excluding the attack_cat column to avoid data leakage and using feature importance analysis, the study identifies sttl, proto_tcp, and service_dns as key features. The model is ideal for deployment in low-resource environments such as edge and IoT devices.

🧠 Key Contributions
Lightweight IDS Design: Efficient XGBoost model using only 379.72 KB data.

Data Integrity: Methodological rigor by excluding leakage-prone features.

Interpretability: Actionable insights via feature importance.


📈 Results Summary
Metric	Test Set (400)	Validation Set (1,000)
Accuracy	95.00%	91.80%
Precision	94.15%	90.35%
Recall	96.02%	93.60%
F1-Score	95.07%	91.94%

🔬 Visualizations
Confusion Matrices: confusion_matrix.png, validation_confusion_matrix.png

ROC Curve (AUC ≈ 0.92): roc_curve.png

Feature Importance Plot: feature_importance.png

🧪 Future Work
Evaluate on imbalanced datasets

Use quantization & compression for faster edge inference

Expand hyperparameter tuning

Apply on modern datasets like CICIDS2017


File Description
Cybersecurity_XGBoost_UNSW.ipynb: Main Jupyter Notebook containing code, visualizations, and results.

confusion_matrix.png, validation_confusion_matrix.png, roc_curve.png, feature_importance.png: Visualization files.

Datasets Link: https://unsw-my.sharepoint.com/personal/z5025758_ad_unsw_edu_au/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fz5025758%5Fad%5Funsw%5Fedu%5Fau%2FDocuments%2FUNSW%2DNB15%20dataset%2FCSV%20Files%2FTraining%20and%20Testing%20Sets&ga=1

🚀 How to Run This Project (Simple Steps)
You can run this notebook in two ways:

✅ Option 1: Open Directly in Google Colab (No Installation Needed)
Go to the GitHub repo.

Click on the notebook file Cybersecurity_XGBoost_UNSW.ipynb.

Click the button "Open in Colab" (if available) or replace github.com with colab.research.google.com/github/ in the URL.

👉 Example:

bash
https://colab.research.google.com/github/YOUR-USERNAME/YOUR-REPO/blob/main/Cybersecurity_XGBoost_UNSW.ipynb
Once open in Colab, click Runtime > Run All or press Ctrl+F9.

✅ Option 2: Run Locally on Your Computer
Requirements
Python 3.7+

Jupyter Notebook or Jupyter Lab

Required libraries:

nginx
pandas
numpy
xgboost
matplotlib
seaborn
scikit-learn
Steps
Clone this repository:

bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
Install required packages:

pip install -r requirements.txt
Or manually:

bash
pip install pandas numpy xgboost matplotlib seaborn scikit-learn
Launch Jupyter Notebook:

bash
jupyter notebook
Open Cybersecurity_XGBoost_UNSW.ipynb and run the cells one by one.

📌 Index Terms
XGBoost, Intrusion Detection System (IDS), Internet of Things (IoT), UNSW-NB15 Dataset, Network Security, Compact Dataset



👨‍🏫 Author
Agha Wafa Abbas
Lecturer, School of Computing, Arden University, UK
Lecturer, IVY College of Management Sciences, Pakistan
📧 awabbas@arden.ac.uk | wafa.abbas.lhr@rootsivy.edu.pk
