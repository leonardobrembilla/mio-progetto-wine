# 🍷 Wine Classification with Support Vector Machine (SVM)

## 📌 Project Overview

This project was developed as part of the **Start2Impact University – Advanced Machine Learning** course.

The objective is to build a supervised Machine Learning model capable of accurately classifying different types of Italian wines based on their chemical characteristics.

The project follows a complete Machine Learning workflow, from data exploration to model optimization and evaluation, using a **Support Vector Machine (SVM)** classifier.

---

## 📂 Dataset

**Dataset:** Wine Dataset (Scikit-learn)

The dataset contains:

- **178 wine samples**
- **13 chemical features**
- **3 wine classes (cultivars)**

The target variable identifies the wine cultivar based on its chemical composition.

---

## 📊 Exploratory Data Analysis (EDA)

The exploratory analysis includes:

- Dataset overview
- Statistical summary
- Missing values check
- Feature distribution analysis
- Correlation analysis
- Data visualization

These analyses help understand the relationships among chemical properties before training the model.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Train/Test Split
- Feature Scaling using **StandardScaler**
- Scikit-learn **Pipeline**

Scaling is particularly important because Support Vector Machines are sensitive to feature magnitudes.

---

## 🤖 Machine Learning Model

The classification model used is:

- **Support Vector Machine (SVM)**

The model is optimized using **GridSearchCV**, which automatically searches for the best hyperparameter combination.

---

## 📈 Model Evaluation

The model is evaluated using several classification metrics:

- Accuracy
- Cross Validation
- Classification Report
- Confusion Matrix
- Permutation Feature Importance

These evaluation techniques provide a robust assessment of the classifier's predictive performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
├── LeonardoBrembillaML.ipynb
├── README.md
├── requirements.txt
└── wine.csv

```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/wine-classification-svm.git
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook LeonardoBrembillaML(2).ipynb
```

or run it directly with **Google Colab**.

---

## 🎯 Learning Objectives

This project demonstrates the ability to:

- Perform Exploratory Data Analysis (EDA)
- Prepare data for Machine Learning
- Build preprocessing pipelines
- Train a Support Vector Machine classifier
- Optimize hyperparameters using GridSearchCV
- Evaluate model performance with multiple metrics
- Interpret feature importance using Permutation Importance
- Apply Machine Learning best practices

---

## 👨‍💻 Author

**Leonardo Brembilla**

Data Scientist

GitHub: https://github.com/leonardobrembilla

LinkedIn: https://www.linkedin.com/in/leonardobrembilla

---

## 📄 License

This project was created for educational purposes as part of the Start2Impact University Advanced Machine Learning course.
