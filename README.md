# Customer Classification ML Project

## Overview

This project is a machine learning classification problem where we predict customer target behavior using multiple ML algorithms.

The project includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training & comparison
* Prediction system

---

##  Dataset Features

* Age
* Gender
* Annual Income
* Spending Score
* Region
* Marital Status
* Number of Children
* Employment Status
* Credit Score
* Online Shopping Frequency

 Target:

* `0` → No
* `1` → Yes

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Data Preprocessing

* Removed unnecessary column (`Customer_ID`)
* Handled missing values using median
* Converted float values to integer
* Encoded categorical variables using Label Encoding
* Applied feature scaling (StandardScaler)

---

##  Exploratory Data Analysis (EDA)

* Target distribution
* Feature relationships
* Correlation heatmap
* Categorical analysis

---

##  Machine Learning Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes
* Support Vector Machine (SVM)
* Random Forest

---

##  Handling Imbalanced Data

The dataset had class imbalance (~69% vs ~31%).

To solve this:

* Used `class_weight='balanced'`
* Applied SMOTE (Synthetic Minority Oversampling Technique)

---

##  Model Evaluation

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score

---

##  Best Model

Random Forest and SVM performed best after tuning and balancing the dataset.

---

## Prediction

The trained model can predict customer target behavior based on input features.

Example:

```python
prediction = model.predict(new_data)
```

---

## Key Learnings

* Importance of data preprocessing
* Handling imbalanced datasets
* Comparing multiple ML models
* Importance of evaluation metrics beyond accuracy

---

## How to Run

```bash
git clone https://github.com/your-username/customer-classification-ml.git
cd customer-classification-ml
pip install -r requirements.txt
python main.py
```

---

## Project Structure

```
├── data/
├── notebooks/
├── models/
├── main.py
├── README.md
```

---

## Author

shamil u

---
