# Assignment-4
#  Breast Cancer Classification using K-Nearest Neighbors (KNN)

A Machine Learning project developed as part of **AI-ML Assignment 4**. This project classifies breast tumors as **Malignant (M)** or **Benign (B)** using the **K-Nearest Neighbors (KNN)** algorithm.

---

#  Project Overview

Breast cancer classification is an important healthcare application of machine learning. This project develops a K-Nearest Neighbors (KNN) classifier to predict whether a breast tumor is malignant or benign based on diagnostic measurements.

---

#  Objective

- Load and understand the Breast Cancer dataset.
- Perform data preprocessing.
- Remove unnecessary columns.
- Encode the target variable.
- Standardize feature values.
- Train a KNN classifier (K = 5).
- Predict tumor classes.
- Evaluate model performance.

---

#  Dataset

**Dataset Name**

Breast Cancer Wisconsin Diagnostic Dataset

**Source**

Kaggle

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

---

#  Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn

---

#  Target Variable

**Diagnosis**

- M = Malignant
- B = Benign

---

#  Methodology

## Step 1 – Data Understanding

- Loaded dataset
- Displayed first five records
- Identified numerical features
- Displayed dataset information
- Displayed summary statistics

---

## Step 2 – Data Preprocessing

- Checked missing values
- Removed unnecessary columns
- Encoded target variable
- Standardized features
- Split dataset into training and testing sets

---

## Step 3 – Model Development

- Trained K-Nearest Neighbors classifier
- Used **K = 5**
- Predicted class labels

---

## Step 4 – Model Evaluation

Evaluation Metrics:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

#  Results

The KNN classifier successfully classified breast tumors into malignant and benign categories. The model achieved good classification performance after feature scaling.

---

# 🔍 Key Findings

- Feature scaling significantly improves KNN performance.
- KNN correctly classifies most tumor samples.
- The confusion matrix shows high prediction accuracy.

---

#  Conclusion

The K-Nearest Neighbors (KNN) algorithm was successfully implemented for breast cancer classification. The dataset was preprocessed by removing unnecessary columns, encoding the target variable, and standardizing the feature values before training the model with K = 5. The model performed well based on Accuracy, Precision, Recall, F1-Score, and the Confusion Matrix. Feature scaling is essential because KNN relies on distance calculations. One limitation of KNN is that prediction becomes slower for larger datasets since it computes distances to many training samples.

---

#  Repository Structure

```text
Assignment-4/
│
├── Assignment-4.ipynb
├── data.csv
└── README.md
```

---

#  How to Run

1. Clone the repository.

```
git clone https://github.com/your-username/Assignment-4.git
```

2. Install required libraries.

```
pip install pandas matplotlib scikit-learn
```

3. Open `Assignment-4.ipynb` in Google Colab or Jupyter Notebook.

4. Run all cells.

---

#  Libraries Used

- pandas
- matplotlib
- scikit-learn

---

#  Author

**Name:** Sougat Das

**Course:** B.Tech CSE (AI & ML)

**Assignment:** Assignment-4

**Topic:** Breast Cancer Classification using K-Nearest Neighbors (KNN)

---

#  Acknowledgement

This project was completed as part of the AI & ML course assignment using the Breast Cancer Wisconsin Diagnostic Dataset.
