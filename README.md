# Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning. The dataset used is the popular [Titanic dataset](https://www.kaggle.com/c/titanic/data) from Kaggle, which includes details about the passengers, such as age, gender, class, and whether they survived.

## Project Overview

The goal of this project is to predict the `Survived` status (0 or 1) of Titanic passengers based on their features. This project is a beginner-friendly example of a machine learning classification task and covers the full pipeline from data preprocessing to model evaluation.

### Dataset

The dataset includes the following columns:

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Target variable indicating survival (1) or non-survival (0).
- **Pclass**: Ticket class (1st, 2nd, or 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Project Structure

- `titanic_project.ipynb`: Jupyter notebook containing the code for data cleaning, model building, evaluation, and hyperparameter tuning.
- `README.md`: Project documentation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ro484/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `titanic_project.ipynb` in Jupyter Notebook:

   ```bash
   jupyter notebook titanic_project.ipynb
   ```

## Project Workflow

1. **Data Loading and Exploration**: Load the dataset, explore its structure, and check for missing values.
2. **Data Cleaning**: Handle missing values, drop irrelevant columns, and encode categorical data.
3. **Feature Selection and Splitting**: Select features, define the target, and split the dataset into training and testing sets.
4. **Model Training**: Train a Random Forest classifier to predict survival.
5. **Evaluation**: Evaluate model performance with accuracy and classification metrics.
6. **Hyperparameter Tuning** (optional): Use `GridSearchCV` to optimize the model's hyperparameters.

## Model Performance

- The model achieved an accuracy of approximately 82% on the test set.
- Detailed performance metrics (precision, recall, F1-score) are included in the notebook.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Dataset source: [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)

