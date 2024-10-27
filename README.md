# Exploratory Data Analysis (EDA) and Data Cleaning on Titanic Dataset

![image](https://github.com/user-attachments/assets/9df1d937-b1bb-4c4d-99cb-fc22e17e10d0)


## Project Overview
This project performs data cleaning and exploratory data analysis (EDA) on the [Titanic dataset from Kaggle](https://www.kaggle.com/c/titanic/data). The main objective is to explore relationships between variables, identify trends, and extract insights that could help predict survival rates among passengers. EDA is a crucial step in the data science workflow, providing a deeper understanding of the data, which is essential for further modeling.

## Dataset

The dataset contains information on passengers aboard the Titanic, including attributes like age, class, sex, fare, and whether they survived the disaster. Key features include:
- `PassengerId`: Unique ID for each passenger
- `Survived`: Survival indicator (1 = Yes, 0 = No)
- `Pclass`: Passenger class (1 = First, 2 = Second, 3 = Third)
- `Name`: Passenger's name
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Ticket fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### Dataset Source

The dataset can be accessed from Kaggle: [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data).

## Project Structure

- `FutureInterns_DS_01_Exploratory_Data_Analysis_.ipynb`: Jupyter notebook containing code for data cleaning, analysis, and visualization.

## Requirements

To run the project, the following packages are needed:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

Install dependencies via:

```bash
pip install pandas numpy matplotlib seaborn
```

## Project Steps

1. **Data Cleaning**:
   - Handling missing values (e.g., in `Age`, `Cabin`, and `Embarked` columns).
   - Converting categorical variables to numerical format.
   - Outlier detection and treatment, if necessary.

2. **Exploratory Data Analysis (EDA)**:
   - **Univariate Analysis**: Analyzing individual variables to understand their distribution and patterns.
   - **Bivariate Analysis**: Exploring relationships between variables, such as `Age` vs. `Survived` or `Pclass` vs. `Fare`.
   - **Multivariate Analysis**: Studying the interaction of multiple variables to see more complex relationships and survival trends.

3. **Visualization**:
   - Graphical representations to identify patterns and trends, using plots such as histograms, bar plots, and scatter plots.

## Key Findings

- **Survival Rates by Class and Gender**: There is a clear correlation between `Pclass`, `Sex`, and `Survival`, with females in first class having a higher survival rate.
- **Impact of Age on Survival**: Younger passengers had higher survival rates, likely due to prioritization.
- **Effect of Fare and Embarkation**: Passengers who paid higher fares, especially those who embarked at Cherbourg, showed higher survival tendencies.

## Usage

1. Download the dataset and place it in the same directory as the notebook or update the path in the notebook code.
2. Run the notebook to perform data cleaning and EDA.
3. Modify and extend the analysis as needed based on your specific objectives.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
