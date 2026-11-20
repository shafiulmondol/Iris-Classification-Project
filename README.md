# Iris Flower Classification Project

## 📌 Project Overview

This project implements a **Multi-Class Classification Pipeline** using the Iris dataset.

The main objective is to train, evaluate, and compare different machine learning classification algorithms to predict the species of Iris flowers based on their measurements.

Two machine learning algorithms are implemented:

- Logistic Regression
- Decision Tree Classifier

The models are evaluated using multiple classification metrics to identify the better-performing model.

## 🎯 Objectives

- Load and explore the Iris dataset.
- Perform Exploratory Data Analysis (EDA).
- Preprocess the dataset.
- Split the dataset into training and testing sets.
- Apply feature scaling.
- Train multiple machine learning models.
- Evaluate model performance.
- Compare classification algorithms.
- Visualize confusion matrices.
- Perform hyperparameter tuning using GridSearchCV.

## 📂 Project Structure

```text
Iris-Classification-Project/
│
├── data/
│   └── iris_data.xlsx
│
├── figures/
│   ├── decision_tree_confusion_matrix.png
│   └── logistic_confusion_matrix.png
│
├── models/
│   ├── decision_tree.pkl
│   └── logistic_regression.pkl
│
├── results/
│   ├── decision_tree_confusion_matrix.csv
│   ├── logistic_confusion_matrix.csv
│   └── model_comparison.csv
│
├── Iris_Classification_Project.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## 📊 Dataset Information

The project uses the Iris dataset.

| Property | Description |
|---|---|
| Total Samples | 150 |
| Input Features | 4 |
| Target Classes | 3 |
| Target Column | species |

### Input Features

1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

### Target Classes

- Setosa
- Versicolor
- Virginica

## 🛠️ Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## ⚙️ Project Workflow

1. Dataset Loading
2. Data Exploration
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Prediction
9. Model Evaluation
10. Model Comparison
11. Hyperparameter Tuning

## 🤖 Machine Learning Models

### 1. Logistic Regression

Logistic Regression is used as a classification algorithm to predict the species of Iris flowers.

### 2. Decision Tree Classifier

Decision Tree is a tree-based classification algorithm that makes predictions using a sequence of decision rules.

## 📈 Model Performance

The following results were obtained from the test dataset:

| Evaluation Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 93.33% | 96.67% |
| Precision | 93.33% | 96.97% |
| Recall | 93.33% | 96.67% |
| F1-Score | 93.33% | 96.66% |

### Best Performing Model

Based on the test results, the **Decision Tree Classifier** achieved the highest accuracy of 96.67%.

## 📉 Model Evaluation

The following evaluation techniques were used:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

Confusion matrix visualizations are available in the `figures/` directory.

## 🔍 Hyperparameter Tuning

GridSearchCV was used to perform hyperparameter tuning and search for suitable Decision Tree parameters.

The best cross-validation accuracy obtained was 94.17%.

Note: Hyperparameter tuning does not always improve test-set performance.

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project Folder

```bash
cd Iris-Classification-Project
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Notebook

Open the notebook using Jupyter Notebook or Google Colab:

```bash
jupyter notebook Iris_Classification_Project.ipynb
```

Run the notebook cells sequentially.

## 📁 Output Files

- Trained machine learning models are saved in the `models/` directory.
- Confusion matrix images are saved in the `figures/` directory.
- Evaluation results are saved in the `results/` directory.

## 📝 Conclusion

This project demonstrates a complete multi-class machine learning classification workflow using the Iris dataset.

Both Logistic Regression and Decision Tree classifiers were trained and evaluated. Based on the obtained test results, the Decision Tree Classifier performed better than Logistic Regression.

The project provides practical experience in data preprocessing, exploratory data analysis, model training, evaluation, comparison, and hyperparameter tuning.

---

**Project:** Multi-Class Benchmark Classification Pipeline  
**Dataset:** Iris Dataset  
**Task:** Multi-Class Classification  
**Language:** Python
