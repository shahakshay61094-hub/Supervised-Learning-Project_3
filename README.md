# Risk Alert Analysis Using Classification Models

## Project Overview

Is project me maine **Risk Alert Analysis** problem par kaam kiya hai. Project ka main objective Machine Learning Classification Algorithms ki help se risk alerts ko classify karna tha taaki high-risk aur low-risk cases ko accurately identify kiya ja sake.

Project ke dauran maine dataset ko explore kiya, data preprocessing perform ki, missing values handle ki, different classification models train kiye aur unki performance compare ki. Iske alawa imbalanced data ko balance karne ke liye different sampling techniques aur model performance improve karne ke liye Hyperparameter Tuning bhi implement ki gayi.

---

## Dataset Information

Project me Risk Alert dataset use kiya gaya hai.

Dataset me customers aur unke transactions se related alag-alag information available hai jinke basis par risk status predict kiya gaya hai.

**Target Variable**

* Risk Status

**Important Features**

* Customer ID
* Transaction Information
* Last Transaction Date
* Transaction Month
* Transaction Day
* Customer Related Attributes
* Financial Information
* Aur anya risk analysis se related features

---

## Project Workflow

### 1. Data Loading

Sabse pehle dataset ko Pandas DataFrame me load kiya gaya aur dataset ki initial records ko display karke uski structure ko samjha gaya.

### 2. Data Exploration

Dataset ko detail me analyze kiya gaya.

Is process me following steps perform kiye gaye:

* Dataset Information
* Data Types
* Missing Values
* First Five Records

### 3. Data Preprocessing

Machine Learning model ko train karne se pehle dataset ko prepare kiya gaya.

Is process me:

* Customer ID column remove kiya.
* Last Transaction Date ko DateTime format me convert kiya.
* Date se Transaction Month aur Transaction Day create kiye.
* Categorical columns ko Label Encoding ki help se numerical format me convert kiya.
* Features aur Target Variable ko alag kiya.
* Dataset ko Training aur Testing sets me divide kiya.
* Missing values ko Simple Imputer ki help se handle kiya.

---

## Machine Learning Models Used

### 1. Logistic Regression

Sabse pehle Logistic Regression model train kiya gaya aur uski prediction performance evaluate ki gayi.

Model ko evaluate karne ke liye:

* Confusion Matrix
* Accuracy Score
* Precision
* Recall
* F1 Score
* Type I Error
* Type II Error

calculate kiye gaye.

### 2. Decision Tree Classifier

Decision Tree Classifier implement kiya gaya aur uski prediction accuracy evaluate ki gayi.

### 3. Random Forest Classifier

Random Forest Classifier train kiya gaya aur uske results ko Decision Tree aur Logistic Regression ke saath compare kiya gaya.

---

## Handling Imbalanced Data

Dataset me class imbalance ko improve karne ke liye different sampling techniques apply ki gayi.

### Random Under Sampling

Majority class ke samples ko reduce karke balanced dataset create kiya gaya.

### Random Over Sampling

Minority class ke samples ko increase karke dataset balance kiya gaya.

### SMOTE

Synthetic Minority Oversampling Technique ka use karke naye synthetic samples generate kiye gaye.

### ADASYN

Adaptive Synthetic Sampling algorithm ki help se difficult minority class ke synthetic samples generate kiye gaye.

In sabhi techniques ki performance compare karke best approach analyze ki gayi.

---

## Hyperparameter Tuning

Model ki prediction accuracy improve karne ke liye Hyperparameter Tuning perform ki gayi.

### Randomized Search CV

Random combinations evaluate karke best parameters identify kiye gaye.

### Grid Search CV

Different parameter combinations ko systematically evaluate karke best-performing Random Forest model select kiya gaya.

---

## ROC Curve Analysis

Project me different classification models ki ROC Curves generate aur compare ki gayi.

Following models ki ROC performance evaluate ki gayi:

* Logistic Regression
* Decision Tree
* Random Forest
* Tuned Random Forest

Har model ke liye AUC Score calculate kiya gaya aur final comparison kiya gaya.

---

## Evaluation Metrics

Models ko evaluate karne ke liye following metrics use kiye gaye:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Type I Error
* Type II Error
* ROC Curve
* AUC Score

---

## Model Comparison

Sabhi classification models ki performance compare ki gayi.

Hyperparameter Tuning aur Imbalanced Data Handling ke baad models ki accuracy aur AUC Scores ka comparison kiya gaya aur best-performing model identify kiya gaya.

---

## Key Learnings

Is project ke through maine:

* Data Preprocessing
* Missing Value Handling
* Label Encoding
* Feature Engineering
* Train-Test Split
* Logistic Regression
* Decision Tree Classification
* Random Forest Classification
* Handling Imbalanced Data
* Random Under Sampling
* Random Over Sampling
* SMOTE
* ADASYN
* Hyperparameter Tuning
* Randomized Search CV
* Grid Search CV
* Confusion Matrix
* ROC Curve
* AUC Score
* Model Comparison

jaise important Machine Learning concepts ko practically implement kiya.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn
* Jupyter Notebook

---

## Conclusion

Is project me Risk Alert Analysis ke liye complete Machine Learning Classification pipeline implement ki gayi. Data preprocessing se lekar Logistic Regression, Decision Tree, Random Forest, Imbalanced Data Handling, Hyperparameter Tuning aur ROC Curve Analysis tak saare important steps perform kiye gaye. Different models ki performance compare karne ke baad evaluation metrics ke basis par best-performing classification model identify kiya gaya. Is project ne mujhe real-world risk prediction problems aur model evaluation techniques ko practical level par samajhne ka valuable experience diya.
