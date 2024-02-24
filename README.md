SUMMARY of the Project
The data science project outlined here digs into the analysis of employee performance at INX Future Inc. 
The primary objective is to determine the performance ratings of employees based on various factors present in their data, such as total work experience, gender, department, and current role.

The project aims to achieve several goals which includes:

1. Department wise performances
2. Top 3 Important Factors effecting employee performance
3. A trained model which can predict the employee performance based on factors as inputs. This will be used to hire employees.
4. Recommendations to improve the employee performance based on insights from analysis.
The dataset provided, comprises 1200 records, each containing 28 features. These features are classified into quantitative and qualitative categories, with 9 being qualitative and 19 quantitative.
The dataset includes employee IDs, which are alphanumeric and deemed irrelevant for predicting performance ratings.

The dataset is a supervised learning multiclass classification, it has 27 features and a target variable (Performance Rating). It has no missing record (Null or NaN values).

There were few outliers present in the dataset which were handled and removed using Interquartile Range method. 
The features which were categorical in nature were handled and converted to Numerical type using Manual Encoding.

The Machine Learning Algorithms which were used to build models are as follows:

1. Logistic Regression
2. Support Vector Machine
3. Decision Tree
4. Random Forest
5. Gradient Boosting
6. K-Nearest Neighbour
Out of these, Random Forest and Gradient Boosting Algorithms performed best with accuracy score of ~ 90%.

To determine the most influential features affecting performance ratings, Feature Importance techniques provided by the machine learning models are utilized.

Overall, the project successfully achieves its objectives through the application of machine learning models and visualization techniques, providing valuable insights into employee performance and guiding recommendations for improvement.
