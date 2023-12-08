# Mobile Phone Transactions Fraud Detection

In the era of digital transactions, the rise in mobile phone-based financial activities has rendered the monitoring of fraudulent transactions both increasingly vital and challenging. The absence of an effective fraud detection system can lead to severe consequences, including significant financial losses for both individuals and businesses, erosion of customer trust, and escalated operational costs for financial institutions.

This project delves into the realm of fraud detection within mobile phone transactions by utilizing a highly imbalanced dataset. It employs a range of supervised machine learning techniques, such as Logistic Regression, K Nearest Neighbor, Random Forest, and XGBoost, implemented within a Jupyter Notebook environment. The project's primary objective is to identify fraudulent transactions effectively and to equip participants with the skills required for hyperparameter tuning and machine learning model development in the context of fraud detection.

## Python Environment and Setup

This project was developed in a Python environment, specifically designed to support data analysis and machine learning tasks. Key libraries used include Pandas for data manipulation, Scikit-learn for machine learning models and pipelines, and SHAP for model interpretability. The project is compatible with standard Python environments that support Jupyter Notebooks.

Please run `test_environment.ipynb`. It checks the versions of your python and some packages (like pandas, shap, etc). If the notebook returns all OK, you should be able to run the code without issues. If some FAILs are returned, you need to install/update those packages first.

## Project structure

#### Part I: Data Cleaning and Exploratory Data Analysis (EDA)

In the first part, the focus was on data cleaning and performing an Exploratory Data Analysis (EDA) to understand the dataset's characteristics and nuances. This section is crucial for laying the groundwork for effective model building.

Notebook location: /src/CChen_FinalProject(Part1).ipynb

#### Part II: Preprocessing, Modeling, and Interpretability

The second part involved preprocessing the data, constructing machine learning pipelines, and tuning hyperparameters. This stage also includes the evaluation of model results and interpreting the outcomes to derive meaningful insights.

Notebook location: /src/CChen_FinalProject(Part2).ipynb

## Initial Fraud Detection Dataset

The original dataset for fraud detection is sourced from Kaggle(https://www.kaggle.com/datasets/ealaxi/paysim1). However, this project primarily utilizes a preprocessed version of the data, located in the /data directory for ease of access and enhanced efficiency in processing and analysis.

## Author

Chujun Chen (chujun_chen@brown.edu)

## License

This project is licensed under the MIT License.
