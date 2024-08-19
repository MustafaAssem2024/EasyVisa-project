EasyVisa Project

Project Overview

The EasyVisa project is designed to streamline the visa approval process by utilizing machine learning models to predict the likelihood of visa approval based on various applicant and employment features. This project addresses the challenges faced by businesses in the United States in identifying and attracting the right talent, both locally and internationally. By analyzing historical visa application data, the project aims to facilitate the OFLC (Office of Foreign Labor Certification) in making more efficient and data-driven decisions.

Objective

The objective of the EasyVisa project is to build a classification model that can predict whether a visa application will be certified or denied. The model helps in:

Facilitating the process of visa approvals by providing data-driven recommendations.
Identifying key features that significantly influence the case status of visa applications.
Recommending suitable profiles for applicants with a higher likelihood of visa certification.
Data Description

The dataset contains various attributes related to the employee and employer, such as:

case_id: ID of each visa application.
continent: Continent of the employee.
education_of_employee: Education level of the employee.
has_job_experience: Whether the employee has job experience (Y/N).
requires_job_training: Whether the employee requires job training (Y/N).
no_of_employees: Number of employees in the employer's company.
yr_of_estab: Year the employer's company was established.
region_of_employment: Intended region of employment in the U.S.
prevailing_wage: Average wage paid for the occupation in the area of intended employment.
unit_of_wage: Unit of the prevailing wage (Hourly, Weekly, Monthly, Yearly).
full_time_position: Whether the position is full-time or part-time.
case_status: Whether the visa was certified or denied.
Project Structure

The project is divided into the following sections:

Data Import and Preprocessing: Loading the dataset, performing initial sanity checks, handling missing values, and preparing the data for modeling.
Exploratory Data Analysis (EDA): Analyzing the dataset to gain insights into key features that influence visa approval.
Feature Engineering: Creating new features and handling outliers to improve model performance.
Model Building: Implementing various classification models (e.g., Decision Trees, Random Forest, XGBoost, etc.) to predict visa approval.
Model Evaluation and Tuning: Evaluating model performance using metrics like accuracy, F1 score, precision, and recall. Hyperparameter tuning to optimize the models.
Conclusion and Recommendations: Summarizing the findings, recommending the best-performing model, and providing actionable insights for stakeholders.

Model Evaluation

The following models were evaluated in this project:

Decision Tree Classifier
Bagging Classifier
Random Forest Classifier
AdaBoost Classifier
Gradient Boosting Classifier
XGBoost Classifier
Stacking Classifier

After evaluating the models, the XGBoost Classifier (tuned) was identified as the best-performing model with a balance of accuracy and F1 score. This model is recommended for predicting visa approvals.

Conclusion and Recommendations

The analysis shows that key factors like education level, job experience, and prevailing wage significantly influence the likelihood of visa approval. The XGBoost model, after tuning, offers the best performance and is recommended for deployment. The insights gained from this project can help OFLC prioritize applications, saving time and resources.

Future Work

Future improvements could include:

Incorporating additional data sources to enhance model accuracy.
Experimenting with deep learning models for better prediction performance.
Implementing the model in a real-time decision support system for visa processing.
