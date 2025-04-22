# Bank Marketing Campaign Analysis

## Project Overview

This project analyzes the Bank Marketing dataset from the UCI Machine Learning Repository to understand customer behavior and identify key factors influencing subscription to term deposits. The goal is to help optimize future marketing campaigns by building and comparing the performance of different machine learning classifiers.

## Business Problem

The primary objective is to predict whether a client will subscribe to a term deposit (binary classification: "yes" or "no"). This prediction can help banks target their marketing efforts more effectively and improve conversion rates.

## Dataset

The dataset used in this project is the "Bank Marketing" dataset, publicly available from the UCI Machine Learning Repository. It contains information about bank clients, including demographics, financial details, and marketing campaign interactions.

## Methodology

1. **Data Loading and Exploration:** The dataset is loaded, cleaned, and explored using descriptive statistics and visualizations to understand its structure and characteristics.
2. **Inferential Statistics:** Inferential statistics are used to analyze the relationship between different categorical features and the target variable (term deposit subscription). This helps identify potential factors influencing customer behavior.
3. **Data Preprocessing:** The data is preprocessed to prepare it for machine learning models. This includes handling missing values, encoding categorical features, and scaling numerical features.
4. **Model Training and Evaluation:** Several machine learning models (K-Nearest Neighbors, Logistic Regression, Decision Tree, and Support Vector Machine) are trained on the preprocessed data. Their performance is evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
5. **Model Comparison and Selection:** The performance of different models is compared to identify the best-performing model for this specific problem.
6. **Reporting and Insights:** The results and insights from the analysis are summarized in a report, including recommendations for optimizing marketing campaigns.

## Folder Structure

bank-marketing-analysis/ ├── data/ │ └── bank-additional-full.csv ├── notebooks/ │ └── BankMarketingCampaignAnalysis.ipynb ├── reports/ │ └── report.html ├── images/ │ └── ... └── README.md
## Results

The project provides valuable insights into customer behavior and the factors influencing their decision to subscribe to term deposits. The model comparison reveals which models perform best for this prediction task, providing a basis for selecting the most suitable model for deployment.

## Usage

1. Clone the repository: `git clone https://github.com/your-username/bank-marketing-analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook BankMarketingCampaignAnalysis.ipynb`

## Contributing

Contributions to this project are welcome. Please follow the standard GitHub workflow for contributing.

## License

This project is licensed under the MIT License.