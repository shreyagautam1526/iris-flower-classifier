"# iris-flower-classifier"
A machine learning project built in Google Colab to classify iris flowers into three species using Random Forest Classifier. This project demonstrates complete ML workflow from data exploration to model evaluation.
📋 Table of Contents

About
Dataset
Features
Getting Started with Colab
Project Workflow
Results
How to Use
Code Overview
Model Performance
Technologies Used
Installation & Setup
Contributing
License


📖 About
This is a Google Colab-based Machine Learning project for iris flower classification. The project covers:

✅ Data loading and exploration using Scikit-learn
✅ Exploratory Data Analysis (EDA) with visualization
✅ Data preprocessing and feature scaling
✅ Training multiple classification models
✅ Model evaluation and comparison
✅ Visualization of results and metrics

Perfect for: Beginners learning ML in Colab, portfolio building, and understanding the complete ML workflow.

📊 Dataset
Overview:

Name: Iris Dataset (built-in Scikit-learn)
Samples: 150 flower measurements
Features: 4 numerical measurements
Classes: 3 iris species
Loading Method: from sklearn.datasets import load_iris

Features:
FeatureDescriptionRangeSepal LengthLength of flower sepal4.3 - 7.9 cmSepal WidthWidth of flower sepal2.0 - 4.4 cmPetal LengthLength of flower petal1.0 - 6.9 cmPetal WidthWidth of flower petal0.1 - 2.5 cm
Target Classes:
ClassSpeciesSamples0Setosa501Versicolor502Virginica50

✨ Features Implemented
✅ Data Exploration

Load data from Scikit-learn
Display basic statistics
Check data shape and missing values
Understand feature distributions

✅ Exploratory Data Analysis

Feature distribution plots
Box plots for each class
Statistical summary
Data visualization with Matplotlib/Seaborn

✅ Data Preprocessing

80-20 train-test split
Feature scaling using StandardScaler
Handling class distribution

✅ Model Training

Logistic Regression
K-Nearest Neighbors (KNN)
Random Forest Classifier
Support Vector Machine (SVM)

✅ Model Evaluation

Accuracy score calculation
Precision, Recall, F1-score
Classification Report
Confusion Matrix visualization

✅ Visualization

Feature distribution plots
Correlation heatmap
Confusion matrix heatmap
Model accuracy comparison

📊 Project Workflow
┌─────────────────────────────────────────────┐
│ GOOGLE COLAB NOTEBOOK                       │
├─────────────────────────────────────────────┤
│                                             │
│ Cell 1: Install & Import Libraries          │
│ ↓                                           │
│ Cell 2: Load Dataset                        │
│ ↓                                           │
│ Cell 3: Exploratory Data Analysis           │
│ ↓                                           │
│ Cell 4: Data Preprocessing                  │
│ ↓                                           │
│ Cell 5: Train Multiple Models               │
│ ↓                                           │
│ Cell 6: Model Evaluation & Comparison       │
│ ↓                                           │
│ Cell 7: Visualizations & Results            │
│ ↓                                           │
│ ✅ COMPLETE - View Results!                 │
│                                             │
└─────────────────────────────────────────────┘

📈 Model Performance
            precision  recall  f1-score   support

setosa       1.00      1.00     1.00        12
versicolor   0.78      1.00     0.88         7
virginica    1.00      0.82     0.90        11

accuracy                        0.93        30
macro avg    0.93      0.94     0.92        30
weighted avg  0.95      0.93    0.93        30

🔧 Code Overview
Complete Code Structure in Colab:
Cell 1: Libraries & Setup
  ├─ pip install requirements
  └─ Import all libraries

Cell 2: Data Loading
  ├─ Load iris dataset
  └─ Create DataFrame

Cell 3: Exploratory Analysis
  ├─ Statistics & info
  └─ Visualizations

Cell 4: Preprocessing
  ├─ Train-test split
  └─ Feature scaling

Cell 5: Model Training
  ├─ Initialize models
  └─ Train on data

Cell 6: Evaluation
  ├─ Make predictions
  └─ Calculate metrics

Cell 7: Visualization
  ├─ Confusion matrix
  └─ Model comparison

  💾 Installation & Setup
Running in Google Colab (Easiest):
1. Go to: https://colab.research.google.com
2. New Notebook
3. Copy-paste code from each cell
4. Run cells (Ctrl+Enter)
5. View results!

Running Locally:
bash
# Clone repository
git clone https://github.com/your-username/iris-flower-classifier.git
cd iris-flower-classifier

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook iris-flower-classifier.ipynb

📝 License
This project is licensed under the MIT License - free to use!

👤 Author
Shreya Gautam

Email: your-shreyagautam1526@gmail.com
GitHub: shreyagautam1526
LinkedIn: www.linkedin.com/in/shreya-gautam-60a735318


🔗 Links & Resources
Dataset:

Iris Dataset - Scikit-learn
Original Data Source

Documentation:

Google Colab Guide
Scikit-learn Docs
Pandas Documentation
Matplotlib Tutorial

Learning Resources:

Google Colab Tutorial
Scikit-learn Tutorial
Machine Learning Basics

Made with ❤️ in Google Colab
⭐ If you found this helpful, star the repository!
🚀 Start Learning ML Today in Google Colab!
