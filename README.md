# Task 1: Data Cleaning & Preprocessing - Titanic Dataset

## Objectives:
- Load and explore the dataset
- Handle missing values
- Encode categorical features
- Normalize numerical features
- Visualize data using boxplots

## Tools Used:
- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Google Colab

## Dataset:
- [Titanic Dataset from Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)


# Task 2 - EDA on Titanic Dataset

## Objective
Perform EDA to understand the data, its distribution, relationships, and missing values.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Key Insights
- Females had higher survival rates.
- 3rd class passengers had lower chances of survival.
- Missing data in "Cabin" and "Age" columns.

  # 🏡 Linear Regression on Housing Prices

This project is part of my AI & ML internship, focusing on predicting housing prices using **Linear Regression**. It aims to understand how property features such as area, number of bedrooms, and bathrooms influence the price.

---

## 📌 Task Objective
To implement a linear regression model that predicts house prices based on given features using the **Housing Price Dataset**.

---

## 📁 Dataset
**Dataset used:** Housing.csv  
It includes attributes like:
- Area (sq ft)
- Number of Bedrooms
- Number of Bathrooms
- Price (target variable)

---

## 🛠️ Tools & Libraries Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧪 Steps Performed

1. **Imported Required Libraries**
2. **Loaded Dataset** using Pandas
3. **Exploratory Data Analysis (EDA)**  
   - Checked for nulls  
   - Visualized relationships using scatter plots
4. **Preprocessing**  
   - Encoded categorical data  
   - Handled missing values
5. **Feature Selection**  
   - Selected relevant features like `area`, `bedrooms`, and `bathrooms`
6. **Train-Test Split**
7. **Model Building** using `LinearRegression()`
8. **Model Evaluation**  
   - MAE, MSE, R² score
9. **Visualization**  
   - Plotted regression line for better understanding

---

## 📊 Sample Output

- **Mean Absolute Error:** _e.g._ 50,000  
- **R² Score:** _e.g._ 0.85  
- Visualizations included in the notebook

---

## 📎 How to Run

1. Open the notebook using [Google Colab](https://colab.research.google.com/)
2. Upload the `Housing.csv` dataset
3. Run the cells sequentially

---

## ✅ Conclusion

This project helped in understanding the basics of regression modeling and how to interpret housing data for price prediction. The trained model performs reasonably well and gives an idea of the impact of various features on the housing price.

---

## 🔗 Submission

This project was completed as part of **Task 3** of the AI/ML Internship and submitted via GitHub.


# 🧠 Breast Cancer Prediction using Logistic Regression

This project is a beginner-level Machine Learning task aimed at building a binary classifier using the Logistic Regression algorithm. The goal is to predict whether a breast tumor is **malignant** or **benign** based on various features of cell nuclei derived from digitized images.

---

## 📌 Objective

- Build a binary classification model using logistic regression.
- Apply preprocessing techniques including feature scaling.
- Evaluate the model using classification metrics and visual tools.

---

## 🗂 Dataset

- **Name:** Breast Cancer Wisconsin Diagnostic Dataset
- **Source:** [Kaggle UCI ML Repo](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Attributes:** 32 columns including ID, diagnosis (M = malignant, B = benign), and 30 real-valued input features.

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📊 Features

- **Data Cleaning:** Removed null values and unnecessary ID columns.
- **Label Encoding:** Converted diagnosis labels to binary format (M=1, B=0).
- **Train-Test Split:** Divided dataset into training and test sets (80/20).
- **Feature Scaling:** Applied StandardScaler to normalize feature values.
- **Model Building:** Used Logistic Regression for binary classification.
- **Evaluation Metrics:**
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)
  - ROC-AUC Score
  - ROC Curve Plot

---

## 📈 Model Performance

Example output (may vary depending on split):

- **Accuracy:** 97.3%
- **Precision:** 96%
- **Recall:** 98%
- **AUC Score:** 0.99

---

## 🧠 Key Learnings

- How Logistic Regression works for binary classification.
- Importance of data preprocessing and feature scaling.
- Use of ROC curves and AUC for evaluating classifier performance.
- Practical understanding of confusion matrix, precision, recall, and F1-score.

---

## 🚀 Future Enhancements

- Hyperparameter tuning using GridSearchCV.
- Add support for multiclass classification.
- Integrate interactive visualizations (e.g., Plotly).
- Save the model using `joblib` or `pickle` for deployment.

---

## ✅ How to Run the Code

1. Download the dataset from Kaggle and place `data.csv` in the project directory.
2. Install required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
