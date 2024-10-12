# Descriptive Analytics - Customer Churn in Telecommunication 

## Introduction:
The dataset being analyzed in this notebook is the Customer Churn in Telecom dataset. This data captures various customer details, including their demographics, service usage, contract types, payment methods, and whether they have churned or not. The primary goal of this analysis is to explore patterns in customer churn and understand the factors influencing customer retention and churn.

With this notebook, I am performing **Descriptive Analytics** to gain insights into the dataset. By visualizing and summarizing the data, we aim to uncover important trends, identify outliers, and prepare the dataset for more advanced analysis. The key steps include data cleaning, handling missing values, encoding categorical variables, and generating statistical summaries and visualizations to better understand customer behavior.

## Data Import:
- Code to import the necessary libraries (`pandas`) and to upload the dataset `Customer Churn in Telecom.csv` into the environment.

## Data Loading:
- Loads the CSV file into a pandas DataFrame and displays the initial dataset.

## Exploratory Data Analysis (EDA):

### Data Type Identification:
- The notebook checks the data types of columns using `df.dtypes`.

### Handling Missing Values:
- The number of missing values in each column is displayed using `df.isnull().sum()`.

## Data Preparation:

### Encoding Categorical Variables:
- Encodes 'PhoneService' and 'Churn' columns into numerical formats (0, 1).
- Drops the original categorical columns after encoding.

### Changing Data Types:
- Changes the data type of `TotalCharges` from string to float after handling invalid values.

## Statistical Summary:
- Generates a statistical summary of the dataset using `df.describe()`.

## Data Visualization:
- **Pie chart** for customer contract types.
- **Bar chart** for the frequency of multiple lines.
- **Histogram** for tenure distribution.
- **Pie chart** for gender distribution.
- **Bar chart** for payment method frequencies.
- **Bar chart** for churn rate by payment method.
