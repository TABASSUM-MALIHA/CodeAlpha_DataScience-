# Iris Flower Species Classification Using Machine Learning

## 📌 Project Overview

This project is developed as part of the **CodeAlpha Data Science Internship**.

The objective of this project is to build a machine learning classification model that predicts the species of an Iris flower based on its sepal and petal measurements.

The three Iris species included in the dataset are:

* Setosa
* Versicolor
* Virginica

## 🎯 Objectives

* Understand and explore the Iris dataset.
* Perform exploratory data analysis (EDA).
* Check the dataset for missing values and basic data quality issues.
* Visualize relationships between the flower measurements.
* Prepare the data for machine learning.
* Train a classification model using Logistic Regression.
* Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.

## 📊 Dataset

The project uses the **Iris dataset** available through Scikit-learn.

The dataset contains **150 samples** and four numerical features:

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

There are three target classes:

* Setosa
* Versicolor
* Virginica

Each species contains 50 samples.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 🔍 Project Workflow

### 1. Data Loading

The Iris dataset was loaded using Scikit-learn's built-in dataset.

### 2. Data Exploration

The dataset was examined using:

* `head()`
* `info()`
* `describe()`
* Missing-value analysis
* Species distribution analysis

### 3. Exploratory Data Analysis

Visualizations were created to understand relationships between the features and Iris species.

A pairplot showed that **petal length and petal width provide strong separation between the different Iris species**.

### 4. Data Preprocessing

The dataset was divided into:

* **80% training data**
* **20% testing data**

The numerical features were standardized using `StandardScaler`.

### 5. Model Training

A **Logistic Regression** classification model was trained using the scaled training data.

### 6. Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## 📈 Results

The model achieved an accuracy of 93.3333% on the test dataset.

The classification report and confusion matrix were also used to evaluate the performance of the model for each Iris species.

> The result shown above is based on the actual execution of the notebook and should be updated with the final value obtained during model evaluation.

## 💡 Key Observations

* The Iris dataset contains no missing values.
* The dataset is balanced, with 50 samples for each species.
* Petal length and petal width show strong differences between the species.
* Setosa is relatively easy to distinguish from the other two species.
* Versicolor and Virginica have some overlap in their feature values.
* Logistic Regression can effectively classify the Iris species using the available measurements.

## 🏁 Conclusion

This project demonstrates a complete beginner-level data science and machine learning workflow, starting from data exploration and visualization and progressing to preprocessing, model training, and evaluation.

The results show that the measurements of Iris flowers can be used effectively to classify their species using a Logistic Regression model.

## 📁 Project Structure

```text
CodeAlpha_IrisFlowerClassification/
│
├── Iris_Flower_Classification.ipynb
├── README.md
└── requirements.txt
```

## 👩‍💻 Internship

**Program:** CodeAlpha Data Science Internship
**Project:** Iris Flower Species Classification Using Machine Learning
**Domain:** Data Science
**Internship Batch:** 10 August 2026 – 10 September 2026

## 📚 Libraries

The required Python libraries are listed in `requirements.txt`.
