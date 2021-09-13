
# NPA_Status Prediction (non-performing asset status)

It is a ‘credit’ dataset having information about loan repayment and credit status of customers of a bank. Customers have been categorised as ‘good’ and ‘bad’, based on their NPA_Status (non-performing asset status).


## 🛠 Programming language and packages

- Python
- NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn, Imblearn.




  
## Steps followed for this project

- Data Preprocessing
- Handling Imbalanced data
- Feature Scaling
- Hyperparameter tuning techniques
- Model (Train the model, Test the model)

  
## Project Description

### Data Preprocessing:

- Understanding the raw data from the csv file. Checking the number of numerical features and categorical features. 
- Shape of the data and missing values are calculated. Visually analyzing the corelations of features and dropped highly corelated duplicate feature.
- Based on the different occupation categories, individual category mean is calculated and replaced it to monthly income nan values based on specific occupation category.
- Handling the categorical features- label encoding technique is done.
### Handling Imbalanced data:
- Over sampling is done on Imbalanced data by imblearn package.
- 75% of data is over sampled.
### Feature Scaling:
- Standardisation(standardscaler) is done on data.
### Model creation and hyperparameter tuning:
- KNN, Decision Tree, Random Forest algorithms are used to create the models and hyperparameter tuning technique(GridSearchCV) is done on respective models and models are evaluated.
- Finally test data is tested on the best model and Good_Bad customers are predicted.