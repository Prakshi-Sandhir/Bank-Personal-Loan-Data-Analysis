# Bank-Personal-Loan-Data-Analysis🏦
This project performs data analysis on a dataset related to personal loans provided by a bank. The analysis is done using Python libraries such as pandas, numpy, seaborn, and matplotlib.

## Features
### 1. Data Loading🔃
The dataset is loaded from an Excel file using the pandas library:

- File: Bank_Personal_Loan_Modelling.xlsx
  
Columns:
- ID: Unique identifier for each customer.
- Age: Age of the customer.
- Experience: Years of professional experience.
- Income: Annual income of the customer.
- ZIP Code: Residential zip code.
- Family: Number of family members.
- CCAvg: Average credit card spending.
- Education: Level of education (1: Undergrad, 2: Graduate, 3: Advanced/Professional).
- Mortgage: Value of the mortgage.
Binary columns such as Personal Loan, Securities Account, CD Account, Online, and CreditCard indicate if a customer has a personal loan, a securities account, a certificate of deposit, uses online banking, or has a credit card.
### 2. Data Exploration and Visualization📊
The project includes:

- Displaying the first few rows of the dataset using pandas (df.head()).
- Visualizing key relationships between variables using seaborn and matplotlib to:
- Understand the distribution of income, age, experience, and family size.
- Analyze relationships between income and loan acquisition.
- Determine which factors are correlated with customers having a personal loan.
### 3. Data Preprocessing♻️
Basic data cleaning steps are applied to handle missing or incorrect values:

Handling missing values.
Data type conversions where necessary.
### 4. Correlation Analysis📈
A correlation heatmap is generated to show the relationships between numerical variables in the dataset. This helps in identifying potential predictors for personal loan acquisition.

## Dependencies🔗⚙️
- Python 3.6+
- Pandas
- NumPy
- Seaborn
- Matplotlib
- OpenPyXL (for reading Excel files)
