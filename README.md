# 🫀 Machine Learning for Heart Disease Detection

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## 📌 Overview

Heart disease is one of the leading causes of death worldwide. Early and accurate detection is critical to saving lives — yet traditional diagnosis methods rely heavily on costly tests and specialist expertise that may not be universally accessible.

This project applies supervised machine learning techniques to predict the presence of heart disease in patients based on clinical and demographic features. By training and evaluating multiple ML models on real-world medical data, this work demonstrates how data-driven approaches can support — and potentially augment — clinical decision-making in healthcare.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) to uncover patterns and correlations in heart disease data
- Preprocess and engineer features to optimize model performance
- Train and compare multiple machine learning classifiers
- Evaluate models using appropriate metrics (accuracy, precision, recall, F1-score, ROC-AUC)
- Identify the most predictive clinical features for heart disease

---

## 📊 Dataset

The project uses a structured clinical dataset containing patient records with the following types of features:

| Feature Type | Examples |
|---|---|
| Demographic | Age, Sex |
| Clinical | Chest pain type, resting blood pressure, cholesterol |
| Diagnostic | Fasting blood sugar, ECG results, exercise-induced angina |
| Target | Heart disease presence (binary: 0 / 1) |

> The dataset is based on the well-known **Cleveland Heart Disease dataset** from the UCI Machine Learning Repository.

---

## 🔬 Methodology

The project follows a standard machine learning pipeline:

1. **Data Loading & Exploration** — Understanding distributions, missing values, and class balance
2. **Exploratory Data Analysis (EDA)** — Statistical summaries and visualizations to reveal feature relationships
3. **Data Preprocessing** — Handling missing values, encoding categorical variables, feature scaling
4. **Model Training** — Training and tuning multiple classifiers including:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
5. **Model Evaluation** — Comparing models using cross-validation and classification metrics
6. **Feature Importance Analysis** — Identifying which features contribute most to prediction

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **Environment:** Jupyter Notebook
- **Core Libraries:**
  - `pandas`, `numpy` — Data manipulation
  - `matplotlib`, `seaborn` — Data visualization
  - `scikit-learn` — Machine learning models and evaluation

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8+ and `pip` installed on your machine.

### 1. Clone the Repository

```bash
git clone https://github.com/quangkhaidataka/Machine-Learning-For-Detecting-Heart-Disease.git
cd Machine-Learning-For-Detecting-Heart-Disease
```

### 2. Install Dependencies

It is recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
```

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open `heart-disease-statistic-project.ipynb` in your browser and run the cells sequentially (`Shift + Enter` or **Run All**).

---

## 📈 Results

The models were evaluated on a held-out test set. Key findings include:

- Identified strong correlations between features such as **chest pain type**, **maximum heart rate**, and **ST depression** with heart disease presence
- Achieved competitive classification performance across multiple models
- Random Forest and SVM consistently ranked among the top-performing classifiers

> Detailed metrics and visualizations are available inside the notebook.

---

## 📁 Project Structure

```
Machine-Learning-For-Detecting-Heart-Disease/
│
├── heart-disease-statistic-project.ipynb   # Main analysis notebook
└── README.md                               # Project documentation
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Quang Khai**
- GitHub: [@quangkhaidataka](https://github.com/quangkhaidataka)
