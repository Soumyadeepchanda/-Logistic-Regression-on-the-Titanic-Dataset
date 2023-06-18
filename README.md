# Logistic-Regression-on-the-Titanic-Dataset
This project aims to predict the survival of passengers on the Titanic using logistic regression. The Titanic dataset is a well-known dataset that contains information about the passengers aboard the Titanic, including whether they survived or not.

### Dataset
The dataset used in this project is the Titanic dataset, which can be found in the file titanic.csv. It contains the following columns:

-PassengerId: Unique identifier for each passenger
-Survived: Survival status (0 = No, 1 = Yes)
-Pclass: Passenger class (1 = 1st class, 2 = 2nd class, 3 = 3rd class)
-Name: Passenger's name
-Sex: Passenger's sex (Male or Female)
-Age: Passenger's age
-SibSp: Number of siblings/spouses aboard
-Parch: Number of parents/children aboard
-Ticket: Ticket number
-Fare: Fare paid for the ticket
-Cabin: Cabin number
-Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### Dependencies
The following libraries are used in this project:

-Pandas: For data manipulation and analysis
-NumPy: For numerical operations
-Scikit-learn: For machine learning algorithms
-Matplotlib: For data visualization
-Seaborn: For enhanced data visualization
### Usage
Clone the repository:
-git clone https://github.com/yourusername/Logistic-Regression-on-the-Titanic-Dataset.git

Install the required dependencies:
-pip install pandas numpy scikit-learn matplotlib seaborn

Run the logistic_regression.py script:
-python logistic_regression.py

### Results
The logistic regression model predicts the survival of passengers based on the provided features. The accuracy of the model on the test dataset is 72.97%. Additionally, various visualizations are generated to explore the dataset and gain insights into the relationships between different variables.
