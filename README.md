# Credit-Risk-Prediction
# Credit Risk Prediction Project

## 📌 Project Overview

This project focuses on predicting credit risk using machine learning techniques. The objective is to classify whether a loan applicant is likely to default or not based on financial and demographic data.

---

## 📊 Data Preprocessing

### 1. Handling Missing Data

* Identified missing values in the dataset.
* Treated missing values using:

  * Mean/Median for numerical features
  * Mode for categorical features
* Ensured a clean and consistent dataset for modeling.

---

### 2. Labeling (Target Variable)

* Converted categorical target values (e.g., *Good/Bad Loan*) into numerical format.
* Applied labeling techniques such as:

  * Label Encoding for binary classification
* This step enabled the dataset to be used in machine learning models.

---

### 3. Sampling Technique (Handling Imbalanced Data)

* Observed class imbalance in the dataset.
* Applied sampling techniques to balance the data:

   **Undersampling** (reducing majority class samples)
* This helped improve model performance and reduce bias toward the majority class.

---

## 📈 Data Visualization

To understand patterns and relationships in the dataset:

* **Loan Amount** (Histogram)
* **Applicant Income Distribution** (Histogram)
* **Education** (Count Plot)
* **Income vs Loan Amount** (Scatter Plot)

Libraries used:

* `matplotlib`
* `seaborn`

---

## 🤖 Model Building

Two classification models were implemented:

### 1. Logistic Regression

* Used for binary classification
* Provides probability-based predictions


## 🧪 Model Evaluation

Model performance was evaluated using:

### ✔ Accuracy Score

* Measures overall correctness

### ✔ Confusion Matrix

* Provides insights into:

  * True Positives
  * True Negatives
  * False Positives
  * False Negatives

This ensures a better understanding of prediction quality.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 📌 Conclusion

This project demonstrates an end-to-end machine learning workflow:

* Data cleaning and preprocessing
* Label encoding and sampling for imbalanced data
* Visualization and analysis
* Model training and evaluation

It highlights the importance of proper data preparation for improving model performance in credit risk prediction.

---

## 📬 Future Improvements

* Apply advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Cross-validation
* Deploy using Flask or Streamlit

---

## 👨‍💻 Author

Haseeb Ahmed

