# parkinsonDiseaseDetection
This project focuses on building a machine learning pipeline to detect Parkinson’s Disease using biomedical voice measurements. Parkinson’s Disease affects motor function, and subtle changes in voice can serve as early indicators. The goal is to classify whether a patient has Parkinson’s based on a set of vocal biomarker features.

### 🔍 Features:

* Based on the **UCI Parkinson’s Dataset**, containing 22 voice features like jitter, shimmer, and fundamental frequency.
* Preprocessing includes **scaling**, **correlation analysis**, and handling outliers.
* Applied and compared multiple classification models:

  * **Support Vector Machine (SVM)**
  * **Random Forest**
  * **Logistic Regression**

### 🛠️ Techniques Used:

* **Data Preprocessing** with `pandas` and `scikit-learn`
* **Feature Scaling** using `StandardScaler`
* **Model Tuning** via **GridSearchCV** and cross-validation
* **Model Evaluation** with:

  * **Confusion Matrix**
  * **Classification Report**
  * **ROC Curve and AUC Score**

### ✅ Results:

The best-performing model achieved high accuracy, precision, and recall, making it suitable for supporting early-stage medical diagnosis.

### 📁 Technologies:

* Python
* Scikit-learn
* Matplotlib & Seaborn (for visualization)
* Jupyter Notebook

---

### 📌 How to Run:

1. Clone the repository
2. Install required libraries (`pip install -r requirements.txt`)
3. Run the notebook: `Parkinson's Disease.ipynb`

---

This project demonstrates how machine learning can be used for early diagnosis of neurological disorders and can be further extended to include real-time voice input and deployment in medical tools.

---


