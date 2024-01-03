# Bank Loan Default Prediction Model 🏦🔍

## Overview

This project focuses on developing a predictive model to determine whether a person is likely to default on a bank loan. By leveraging machine learning algorithms, we aim to provide a tool for banks to assess the creditworthiness of loan applicants and make informed decisions about loan approvals.

## Table of Contents

- [Objective](#objective)
- [Features](#features)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Objective 🎯

The primary goal of this project is to create a robust machine learning model that predicts whether a person is likely to default on a bank loan. This predictive tool can assist financial institutions in assessing risks associated with loan approvals and enhance decision-making processes.

## Features 📊

The following features are considered in the loan default prediction model:

- **Credit Score**: The credit score of the loan applicant.
- **Income**: Monthly income of the applicant.
- **Loan Amount**: The amount of the loan applied for.
- **Loan Term**: The duration of the loan in months.
- **Marriage Status**: Whether the applicant is married or not.
- **Employment Status**: Whether the applicant is employed or not.

## Data Collection 📈

A dataset containing historical loan information, including both default and non-default cases, was collected for model training. The dataset has been provided in this repository for those that want to carry out further analysis.
## Data Preprocessing 🛠️

Prior to model training, the dataset underwent preprocessing steps, including handling missing values, skewness transformation, encoding categorical variables, and scaling numerical features. This ensures that the model receives clean and standardized input.

## Modeling 🤖

Various machine learning algorithms, such as Random Forest, Logistic Regression, and GradientBoostingClassifier were explored. Hyperparameter tuning and cross-validation techniques were employed to optimize model performance. The chosen model was trained on the preprocessed dataset.

## Evaluation 📉

The model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score. Additionally, a confusion matrix was generated to assess the true positive, true negative, false positive, and false negative predictions.

## Usage 🚀

To use the project:

1. Clone the repository: `git clone https://github.com/Aycodez/Loan-Prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the prediction script: `python Bank-LoanPrediction.ipynb`

## Contributing 🤝

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
