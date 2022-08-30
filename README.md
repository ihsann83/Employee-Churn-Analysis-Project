# Employee-Churn-Analysis-Project

First of all, I used exploratory data analysis and data visualization techniques to observe the structure of the data, outliers, missing values and features that affect the target variable.

Then, I performed data pre-processing operations such as Scaling and Label Encoding to increase the accuracy score of Gradient Descent Based or Distance-Based algorithms. I performed Cluster Analysis based on the obtained information during exploratory data analysis and data visualization processes.

The purpose of clustering analysis is to cluster data with similar characteristics. I used the K-means algorithm to make cluster analysis. However, I provided the K-means algorithm with information about the number of clusters it will make predictions. I scaled the data which I applied to the K-means algorithm. In order to find the optimal number of clusters, I used the Elbow method. Briefly, I tried to predict the set to which individuals are related by using K-means and I evaluated the estimation results.

Once the data is ready to be applied to the model, I splitted the data into train and test. Then, I built a model to predict whether employees will churn or not. I trained the models with the train set, tested the success of the model with the test set.

I tried to make predictions by using the algorithms Gradient Boosting Classifier, K Neighbors Classifier, Random Forest Classifier. I used scikit-learn Confusion Metrics module for accuracy calculation and the Yellowbrick module for model selection and visualization.

In the final step, I deployed the model using Streamlit tool.

# Tasks

#### 1. Exploratory Data Analysis
- Importing Modules
- Loading Dataset
- Data Insigts

#### 2. Data Visualization
- Employees Left
- Determine Number of Projects
- Determine Time Spent in Company
- Subplots of Features

#### 3. Data Pre-Processing
- Scaling
- Label Encoding

#### 4. Cluster Analysis
- Find the optimal number of clusters (k) using the elbow method for for K-means.
- Determine the clusters by using K-Means then Evaluate predicted results.

#### 5. Model Building
- Split Data as Train and Test set
- Built Gradient Boosting Classifier, Evaluate Model Performance and Predict Test Data
- Built K Neighbors Classifier and Evaluate Model Performance and Predict Test Data
- Built Random Forest Classifier and Evaluate Model Performance and Predict Test Data

#### 6. Model Deployement

- Save and Export the Model as .pkl
- Save and Export Variables as .pkl 

# Determines

In this project you will have HR data of a company. A study is requested from you to predict which employee will churn by using this data.

The HR dataset has 14,999 samples. In the given dataset, you have two types of employee one who stayed and another who left the company.

You can describe 10 attributes in detail as:

- ***satisfaction_level:*** It is employee satisfaction point, which ranges from 0-1.

- ***last_evaluation:*** It is evaluated performance by the employer, which also ranges from 0-1.

- ***number_projects:*** How many of projects assigned to an employee?

- ***average_monthly_hours:*** How many hours in averega an employee worked in a month?

- **time_spent_company:** time_spent_company means employee experience. The number of years spent by an employee in the company.

- ***work_accident:*** Whether an employee has had a work accident or not.

- ***promotion_last_5years:*** Whether an employee has had a promotion in the last 5 years or not.

- ***Departments:*** Employee's working department/division.

- ***Salary:*** Salary level of the employee such as low, medium and high.

- ***left:*** Whether the employee has left the company or not.

