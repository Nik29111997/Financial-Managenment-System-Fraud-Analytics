# Financial-Managenment-System-Fraud-Analytics

## Project Overview

Credit card fraud is a significant challenge in the financial sector. This project aims to build a robust machine learning model capable of detecting fraudulent transactions effectively. Using advanced data analysis techniques, we focus on creating a solution that minimizes false positives while ensuring scalability and accuracy.

## Key Features

- **Exploratory Data Analysis (EDA)**: Comprehensive analysis to understand the dataset, identify trends, and handle imbalanced data.
- **Machine Learning Models**: Implementation of multiple algorithms (e.g., Random Forest, Neural Networks) for comparison and selection of the best-performing model.
- **Performance Metrics**: Evaluation using precision, recall, F1-score, and ROC-AUC.
- **Cost-Benefit Analysis**: A detailed analysis to assess the financial impact of detecting fraud and preventing false negatives.

## Project Workflow

### Problem Statement

Detect fraudulent credit card transactions to minimize financial losses and improve customer trust.

### Data Collection and Preprocessing

- **Source**: Kaggle (or other publicly available datasets).
- **Techniques**: Handling imbalanced data, normalization, and feature scaling.

### Model Selection and Training

- **Algorithms used**: Logistic Regression, Random Forest, Neural Networks.
- **Model Evaluation**: Metrics like precision, recall, and AUC-ROC are used for selection.

### Structured Problem Solving

- **Coggle Root Cause Analysis**: A Coggle chart highlights the root causes of fraud and mitigation strategies.
- **Cost-Benefit Analysis**: Evaluation of the financial savings achieved by reducing false negatives.

### Documentation

Detailed project report and PowerPoint presentation included for stakeholders.

## Files and Structure

Credit Card Fraud Detection/ │ ├── data/ │ └── credit_card_fraud.csv (Dataset) │ ├── notebooks/ │ └── Credit Card Fraud Analysis Capstone Project.ipynb (Main analysis and modeling notebook) │ ├── charts/ │ └── root_cause_analysis.png (Coggle Chart) │ ├── reports/ │ ├── cost_benefit_analysis.pdf │ └── fraud_detection_presentation.pptx │ ├── src/ │ ├── app.py (Web application for deployment) │ └── model.py (Training and evaluation script) │ └── README.md (This file)


## Cost-Benefit Analysis

| **Metric**                | **Value**             |
| ------------------------- | --------------------- |
| **Cost of False Positive** | $50 per transaction   |
| **Cost of False Negative** | $1000 per transaction |
| **Annual Fraudulent Loss** | $1,000,000            |
| **Savings Post-Detection** | $750,000 annually     |

### Visualizations

- **Coggle Root Analysis Chart**: 
  ![Coggle Chart](charts/root_cause_analysis.png)

### Model Evaluation Metrics

| **Model**           | **Precision** | **Recall** | **F1-Score** | **AUC-ROC** |
| ------------------- | ------------- | ---------- | ------------ | ----------- |
| Logistic Regression | 0.87          | 0.83       | 0.85         | 0.91        |
| Random Forest       | 0.92          | 0.89       | 0.91         | 0.95        |
| Neural Network      | 0.93          | 0.91       | 0.92         | 0.96        |

## Tools and Technologies

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow, Matplotlib, Seaborn
- **Deployment**: Heroku
- **Visualization**: Coggle, Matplotlib
- **Other Tools**: Jupyter Notebook, PowerPoint

## Getting Started

1. **Clone the repository**:

    ```bash
    git clone https://github.com/username/credit-card-fraud-detection.git
    ```

2. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the notebook**:

    ```bash
    jupyter notebook notebooks/Credit\ Card\ Fraud\ Analysis\ Capstone\ Project.ipynb
    ```

4. **Launch the web app**:

    ```bash
    python src/app.py
    ```

## Future Work

- Incorporate advanced deep learning models for better accuracy.
- Explore additional datasets for improving generalization.
- Add real-time fraud detection capabilities.

## Contributions

Feel free to open issues or submit pull requests to improve the repository.

