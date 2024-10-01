# PRODIGY_DS_04
# Direct Marketing Campaign Prediction Using Decision Tree Modeling
* Project Overview

This project was completed as part of my Data Science internship at PRODIGY. The goal of the analysis is to predict whether a client will subscribe to a term deposit (variable y) based on direct marketing campaigns (phone calls) data from a Portuguese banking institution. The dataset includes a range of features related to client demographics, previous interactions, and socio-economic context.

* Dataset Description
  
The dataset contains details of marketing campaigns carried out by the bank. Each row corresponds to a client, with various attributes recorded. The classification target is to predict whether the client subscribed to a term deposit (binary classification).

*Key Features:

age: Age of the client.
job: Type of job (e.g., admin, blue-collar, entrepreneur).
marital: Marital status (e.g., single, married, divorced).
education: Client's level of education.
default: Whether the client has credit in default (binary).
housing: Whether the client has a housing loan (binary).
loan: Whether the client has a personal loan (binary).
contact: Contact communication type (cellular or telephone).
month: Last contact month of the year.
campaign: Number of contacts performed during this campaign.
pdays: Number of days since the client was last contacted from a previous campaign.
previous: Number of contacts performed before this campaign.
poutcome: Outcome of the previous campaign (e.g., success, failure).
y: The target variable, indicating if the client subscribed to a term deposit (yes/no).
Project Workflow

* Data Preprocessing:

Handled missing data.
Encoded categorical variables (e.g., job, marital, education) into numerical format for model training.
Performed feature scaling to normalize numerical features where needed.

* Exploratory Data Analysis (EDA):
  
Visualized the distribution of various features.
Generated heatmaps and correlation matrices to identify relationships between variables.
Explored trends within client demographics and their relationship with subscription rates.

* Decision Tree Modeling:

Applied decision tree classification to predict the probability of a client subscribing to a term deposit.
Evaluated the model using key metrics such as accuracy, precision, recall, and F1-score.
Visualized the decision tree to understand the decision-making process and key features driving the prediction.

* Model Evaluation:

Conducted cross-validation to test model robustness.
Compared different metrics to ensure optimal decision-making, particularly in identifying potential clients for future campaigns.

* Key Insights
  
Clients contacted multiple times during the campaign were more likely to subscribe.
Certain job categories, such as "admin" and "management," showed a higher probability of subscribing to a term deposit.
The decision tree model highlighted key factors such as campaign, previous, and poutcome as strong predictors for client subscription.
Tools and Libraries
Pandas: Data manipulation and preprocessing.
Scikit-learn: Decision tree modeling and evaluation.
Seaborn & Matplotlib: Data visualization (heatmaps, correlation matrices, decision tree plots)
