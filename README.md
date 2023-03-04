
# Titanic EDA and ML Predictions

This project is an exploratory data analysis (EDA) and machine learning (ML) predictions on the famous Titanic dataset. The Titanic dataset is a classic dataset used for ML beginners as it is easily available and contains valuable insights.

The project aims to explore the data, understand the features, identify patterns and relationships, and build a predictive model to predict whether a passenger on the Titanic would survive or not.


## Dataset
The Titanic dataset contains information about the passengers who were aboard the Titanic when it sank. The dataset contains 891 rows and 12 columns. The columns are described below:

- PassengerId: Unique ID for each passenger
- Survived: Whether the passenger survived or not (0 = No, 1 = Yes)
- Pclass: The class of the passenger's ticket (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name: The passenger's name
- Sex: The passenger's gender
- Age: The passenger's age
- SibSp: The number of siblings/spouses the passenger had aboard the Titanic
- Parch: The number of parents/children the passenger had aboard the Titanic
- Ticket: The passenger's ticket number
- Fare: The fare paid by the passenger
- Cabin: The passenger's cabin number
- Embarked: The port where the passenger embarked (C = Cherbourg, Q = Queenstown, S = Southampton)



## Project Structure

The project is structured into two main parts: EDA and ML Predictions.

- Exploratory Data Analysis: This notebook contains the EDA performed on the Titanic dataset. It includes data cleaning, feature engineering, visualizations, and statistical analysis to understand the data.

- ML Predictions: This notebook contains the ML predictions on the Titanic dataset. It includes preprocessing, model selection, hyperparameter tuning, and evaluation to predict whether a passenger on the Titanic would survive or not.



## Dependencies

The following dependencies are required to run the notebooks:

- Python 3
- Jupyter Notebook
- Scikit-Learn
- Pandas
- Numpy
- Matplotlib
- seaborn




## Conclusion

In conclusion, this project explored the Titanic dataset, performed EDA, and built an ML model to predict whether a passenger on the Titanic would survive or not, also multiple models were compared and cross validated to find the best possible model. The ML model achieved an accuracy of 82%, which is a good prediction for this dataset.