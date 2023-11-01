# Diabetes Patient Readmission Prediction

![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8%20%7C%203.9-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2.2-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-green)
![Numpy](https://img.shields.io/badge/Numpy-1.23.5-red)

Welcome to the Diabetes Patient Readmission Prediction repository! This project is aimed at developing a machine-learning model to predict whether a diabetes patient is likely to be readmitted to the hospital within 30 days. Predicting readmission can help healthcare providers better allocate resources and improve patient care.

## Table of Contents
- [Background](#background)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)

## Background

Diabetes is a chronic condition that requires continuous monitoring and management. Hospital readmissions for diabetic patients can be costly and stressful for both patients and healthcare providers. Predicting readmission risk can enable healthcare professionals to take proactive measures to prevent readmission, improve patient outcomes, and reduce healthcare costs.

## Installation

To get started with this project, you need to clone the repository to your local machine. Use the following command to clone the repository:

```bash
git clone https://github.com/LucienCastle/diabetes-patient-readmission-prediction.git
```

Next, navigate to the project directory:

```bash
cd diabetes-patient-readmission-prediction
```

To set up the required Python environment, you can use a virtual environment. Create a virtual environment and install the dependencies listed in the `requirements.txt` file:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

## Usage

Once you have installed the required dependencies, you can use the provided Jupyter notebooks to explore the project:

- `readmission-prediction.ipynb`: Explore and preprocess the dataset and Train and evaluate machine learning models for readmission prediction.

You can run these notebooks step by step to understand and interact with the project.

## Data

The dataset used in this project is available in the [uciml directory](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008). It contains patient information, including demographics, medical history, and medications. The target variable is whether a patient was readmitted within 30 days. The dataset is in CSV format.

## Model

The predictive model in this project is built using machine learning techniques. We experiment with various algorithms, including logistic regression, decision trees, and random forests, and many more. The trained models are evaluated based on performance metrics such as accuracy, precision, recall, and F1-score.

## Future Works

- [ ] Deploy on cloud platform GCP/AWS

---

**Disclaimer:** This project is for educational and research purposes only. It should not be used as a substitute for medical advice or diagnosis. Always consult with a qualified healthcare professional for medical decisions and treatments.
