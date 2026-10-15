# Fetal Health Classification Using Machine Learning

A machine learning project for classifying fetal health conditions using Cardiotocography (CTG) data. The project explores multiple classification algorithms, compares their performance, and evaluates predictions using standard machine learning metrics.

## 📌 Project Overview

Fetal health monitoring is important for identifying potential risks during pregnancy. This project uses machine learning techniques to classify fetal health based on features extracted from CTG data.

The notebook explores different classification models, performs hyperparameter experimentation, and compares their performance using accuracy, precision, recall, F1-score, confusion matrices, and ROC-AUC analysis.

## 🎯 Objectives

- Analyze fetal health data using Python.
- Explore correlations between dataset features.
- Train and evaluate multiple machine learning classifiers.
- Experiment with model hyperparameters to improve classification performance.
- Compare models using classification metrics and visualizations.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly
- **Machine Learning:** Scikit-learn, XGBoost
- **Dataset Format:** Excel (`.xlsx`)
- **Development Environment:** Jupyter Notebook

## 🤖 Machine Learning Algorithms

The notebook experiments with the following algorithms:

| Algorithm | Purpose |
|---|---|
| Logistic Regression | Classification using a linear decision boundary |
| Decision Tree | Classification using feature-based decision rules |
| Random Forest | Ensemble classification using multiple decision trees |
| Support Vector Machine (SVM) | Classification using decision boundaries and kernels |
| K-Nearest Neighbors (KNN) | Classification based on neighboring data points |
| XGBoost | Gradient-boosted decision trees |
| Voting Classifier | Combines predictions from multiple classifiers |

## 📊 Model Evaluation

The project evaluates model performance using:

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of positive predictions that are correct, calculated per class.
- **Recall:** Proportion of actual class instances correctly identified.
- **F1-score:** Harmonic mean of precision and recall.
- **Confusion Matrix:** Comparison of actual and predicted classes.
- **ROC-AUC:** Assessment of classification discrimination performance.

The notebook also includes hyperparameter experiments and visual comparisons of model performance.

## 📁 Project Structure

```text
Fetal-Health-Classification/
│
├── Fetal_health.ipynb
├── balanced_dataset.xlsx
├── README.md
└── requirements.txt
```

**Note:** `balanced_dataset.xlsx` is the dataset file referenced in the notebook. Include it in the repository or update the notebook to point to its actual location. Do not upload sensitive or restricted data.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Fetal-Health-Classification.git
cd Fetal-Health-Classification
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**macOS/Linux**
```bash
source venv/bin/activate
```

**Windows**
```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn xgboost imbalanced-learn scipy tabulate wordcloud lightgbm openpyxl jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Fetal_health.ipynb` and execute the cells in order after ensuring the dataset is available at the expected path.

## 📈 Results

The notebook contains a model comparison table with the following reported accuracy values:

| Model | Reported Accuracy |
|---|---:|
| Random Forest | 99.00% |
| SVM | 99.00% |
| XGBoost | 98.39% |
| KNN | 98.26% |
| Decision Tree | 97.92% |
| Voting Classifier | 97.00% |

These figures are taken from the comparison table in the notebook. They should be treated as reported results rather than independently verified results; rerun the experiments and validate the evaluation procedure before presenting them as final performance claims.

## 📄 Research Publication

This project is associated with research published through an IEEE conference.

- **Publication:** Fetal Health Prediction Using Machine Learning Models on CTG Data
- **Platform:** IEEE Xplore
- **Publication Link:** [Read the Research Paper on IEEE Xplore](https://xplorestaging.ieee.org/document/11256515)

For more details, refer to the official IEEE Xplore publication page.

## 🔬 Future Improvements

- Apply systematic cross-validation for reliable model selection.
- Use a separate, untouched test set for final evaluation.
- Analyze class-wise recall and confusion matrices.
- Improve reproducibility with saved model configurations and fixed random seeds.
- Build a simple interface for demonstrating model predictions.
- Evaluate the model on independent data before considering real-world applications.


