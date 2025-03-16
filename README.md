# Loan Status Prediction using Machine Learning

## Overview

This project aims to predict whether a loan application will be approved or rejected using machine learning techniques. The dataset consists of various factors such as applicant income, loan amount, credit history, and employment details, which are analyzed to build a predictive model.

## Dataset

The dataset contains information about loan applicants, including:

- Applicant Income
- Loan Amount
- Credit History
- Employment Status
- Loan Term
- Marital Status
- Dependents
- Education Level

## Machine Learning Workflow

### 1. Data Preprocessing

- Handle missing values
- Encode categorical variables
- Normalize numerical features
- Split data into training and testing sets

### 2. Exploratory Data Analysis (EDA)

- Visualize data distributions
- Identify correlations between features
- Remove irrelevant or redundant features

### 3. Model Selection & Training

- Train different machine learning models:
  - Logistic Regression
  - Random Forest Classifier
  - Support Vector Machine (SVM)
  - Gradient Boosting (XGBoost)
- Compare model performance using accuracy, precision, recall, and F1-score

### 4. Model Evaluation

- Assess model performance using confusion matrix and classification report
- Perform hyperparameter tuning to improve accuracy

### 5. Deployment

- Deploy the model using Flask or FastAPI to provide real-time predictions

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/balaji9988/Machine-Learning-Project.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Machine-Learning-Project
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## Usage

- Open `Loan_Status_Prediction.ipynb` in Jupyter Notebook
- Execute the cells step by step to train and evaluate the model
- Modify the model parameters and test different algorithms for better accuracy

## Results

- The best-performing model achieved an accuracy of **X%** on the test dataset.
- Feature importance analysis showed that credit history and applicant income had the most significant impact on loan approval.

## Future Improvements

- Use deep learning models for better accuracy.
- Implement automated feature selection methods.
- Deploy the model as a web application with a user-friendly interface.

## Contributing

If you would like to contribute, please fork the repository and submit a pull request with improvements.

## License

This project is licensed under the MIT License. See `LICENSE` for more details.

## Contact

For any queries, reach out to [k balaji] via email: balajicr13\@email.com

