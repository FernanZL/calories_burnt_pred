# Data analysis and Regression Model Training for Calories Expenditure.

This project consists of EDA, data filter (with sql commands) and model training with Kaggle's Calories Expenditure dataset. You can download the data from the competition's [page](https://www.kaggle.com/competitions/playground-series-s5e5/data)


## Included Files

- 'calories_burnt_pred.ipynb': notebook containing the preprocessing and model.

## Requirements

To run the project, Python 3.9 and the following libraries are required:  
- pandas
- duckdb
- seaborn
- matplotlib  
- numpy  
- scikit-learn 
- jupyter  
- lightgbm  
- optuna  

To install the dependencies, you can use the following command:

```bash
pip install numpy pandas scikit-learn lightgbm optuna jupyter duckdb seaborn matplotlib
```

## Download the Dataset
Before running the project, download the dataset from Kaggle, using the link provided above and place it in the same directory as the Jupyter notebook ('calories_burnt_pred.ipynb').

## How to run

1. Clone the repository
If you don't have Git installed, first [install](https://git-scm.com/) it, then run this command in your terminal to clone the repository:

```bash
git clone https://github.com/FernanZL/calories_burnt_pred.git
```

2. Install the dependencies
Once you have cloned the repository, install the necessary libraries using the following command:
```bash
pip install numpy pandas scikit-learn lightgbm optuna jupyter duckdb seaborn matplotlib
```

3. Open the notebook
To open the notebook in Jupyter, run the following command in the terminal:

```bash
jupyter notebook calories_burnt_pred.ipynb
```

Within the Jupyter notebook, you can run the code cells one by one by pressing Shift + Enter to perform the analysis and get the results.
