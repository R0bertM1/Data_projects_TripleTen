# Interconnect Churn Model
Project Description

The Interconnect Churn Model is designed to predict customer churn for a telecommunications company, allowing them to identify at-risk customers and take preventive actions. This project leverages machine learning techniques to analyze customer data and provide actionable insights for retaining valuable customers.
Key Features:

    Data preprocessing and cleaning to prepare the dataset for modeling.
    Implementation of various machine learning algorithms, including Gradient Boosting, to predict churn.
    Model evaluation using metrics such as AUC-ROC, accuracy, precision, and recall to compare performance.
    Hyperparameter tuning to optimize model performance.

Findings & Insights:

The project successfully identified key factors contributing to customer churn, with the CatBoost model achieving the highest AUC-ROC score of 0.90. This model allows the company to accurately identify customers at risk of churning and target them with retention strategies.
Tools and Technologies Used

    Programming Languages: Python
    Libraries: Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn
    IDE: Jupyter Notebook


Deployment Instructions

To run this project locally, ensure you have the following installed:

    Python: Version 3.x
    Required Libraries: Listed in requirements.txt

Clone the repository and install dependencies:

bash

    git clone https://github.com/R0bertM1/interconnect-churn-model.git
    cd interconnect-churn-model
    pip install -r requirements.txt

To run the notebook:

bash

    jupyter notebook Interconnect_Churn_Model.ipynb

Roadmap

    Improve model accuracy: Experiment with ensemble models and deep learning approaches.
