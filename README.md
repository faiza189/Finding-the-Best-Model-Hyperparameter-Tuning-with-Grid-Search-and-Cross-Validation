# Hyperparameter Tuning with GridSearchCV and Cross-Validation

This tutorial presents a complete hands-on guide to hyperparameter tuning using Grid Search and Cross-Validation in `scikit-learn`. It focuses on optimizing two classifiers — Support Vector Machine (SVM) and K-Nearest Neighbors (KNN) — using the Breast Cancer Wisconsin dataset. The goal is to show students how to systematically improve model performance while avoiding common tuning pitfalls like overfitting and data leakage.

## 📁 Contents

- `hyperparameter_tuning_tutorial.ipynb`: Complete notebook with theory, implementation, and evaluation
- `README.md`: This file, including instructions and project overview
- `requirements.txt`: Python dependencies to run the notebook
- `tutorial.docx` or `tutorial.pdf`: (Optional) Written report for academic submission
- `LICENSE`: (Optional) Open-source license

## 📊 Dataset

We use the Breast Cancer Wisconsin (Diagnostic) dataset available in `scikit-learn`. It contains:
- 569 samples
- 30 numeric features
- Binary target: malignant (1) or benign (0)

It is well-suited for classification and supports learning concepts like model tuning, scaling, and validation.

## 🧠 Key Learning Objectives

- Understand the difference between hyperparameters and model parameters
- Apply Grid Search (`GridSearchCV`) to tune SVM and KNN classifiers
- Use cross-validation to evaluate generalization performance
- Compare models visually and interpret results with confusion matrices and reports

## 🚀 How to Run the Notebook

1. Clone this repository:
```
git clone https://github.com/your-username/hyperparameter-tuning.git
cd hyperparameter-tuning
```

2. Install required packages:
```
pip install -r requirements.txt
```

3. Launch the notebook:
```
jupyter notebook hyperparameter_tuning_tutorial.ipynb
```

---

## ♿ Accessibility Features

- Clean markdown structure with step-by-step explanations
- Confusion matrices and charts include axis labels and titles
- Colorblind-friendly visuals
- Compatible with screen readers and academic formatting tools

---

## 🔗 GitHub Submission Guidelines

Your repository should contain:
| File                              | Description                                          |
|-----------------------------------|------------------------------------------------------|
| `hyperparameter_tuning_tutorial.ipynb` | Full notebook with code, plots, and analysis       |
| `README.md`                       | Overview, setup, and learning objectives             |
| `requirements.txt`                | Python packages used in this project                 |
| `tutorial.docx` or `tutorial.pdf` | Final report with theory and reflection              |
| `LICENSE` *(optional)*            | For open-source compliance (e.g., MIT)               |

Example to include in report:
```
GitHub Repository:
https://github.com/your-username/hyperparameter-tuning
```

---

## 📚 Acknowledgements

- Dataset from UCI Machine Learning Repository via `scikit-learn`
- Libraries: `scikit-learn`, `pandas`, `matplotlib`, `seaborn`
- Inspired by pedagogical guidance from Bergstra & Bengio (2012), Kohavi (1995), and Pedregosa et al. (2011)
