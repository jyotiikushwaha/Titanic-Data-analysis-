## Titanic Survival Analysis

Exploratory data analysis and survival prediction on the Titanic passenger dataset.

## Overview

This project explores which factors influenced passenger survival on the Titanic, such as gender, age, passenger class, and family size. It also builds a machine learning model to predict whether a passenger survived.

## Dataset

- **Source:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- **Files:** `train.csv`,

| Column | Description |
|---|---|
| PassengerId | Unique passenger ID |
| Pclass | Ticket class (1st, 2nd, 3rd) |
| Name | Passenger name |
| Sex | Gender |
| Age | Age in years |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation (C, Q, S) |

## Project Structure

```
titanic-analysis/
├── data/
│   ├── train.csv
│   └── test.csv
├── titanic_analysis.ipynb   
├── requirements.txt
└── README.md
```

## Methodology

1. **Data cleaning:** handled missing values in `Age`, `Cabin`, and `Embarked` [describe your approach, e.g. median imputation].
2. **Exploratory data analysis:** analyzed survival rates by gender, class, age group, and family size using visualizations..

## Key Findings

- [e.g. Women had a much higher survival rate than men.]
- [e.g. 1st class passengers survived at a higher rate than 3rd class.]
- [e.g. Children had better survival odds than adults.]

## Technologies Used

- Python 3
- pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Installation and Usage

```bash
# Clone the repository
git clone https://github.com/<your-username>/titanic-analysis.git
cd titanic-analysis

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook titanic_analysis.ipynb
```


## Future Improvements

- Hyperparameter tuning with GridSearchCV
- Try gradient boosting models (XGBoost, LightGBM)
- More advanced feature engineering

## License

This project is licensed under the MIT License.