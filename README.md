# PRODIGY_DS_02

Titanic Dataset Exploratory Data Analysis (EDA)

Welcome to the Titanic Dataset Exploratory Data Analysis (EDA) repository! In this project, we perform an in-depth exploration of the Titanic dataset, which contains information about passengers aboard the Titanic. The aim is to gain insights into various aspects such as demographics, ticket class, fares, and survival rates.

Dataset Overview:

The Titanic dataset comprises information about passengers including their age, gender, ticket class, fare, cabin, and survival status.
Exploratory Data Analysis (EDA) Steps:

Data Cleaning:

Check the shape of the dataset and general information about variables.
Identify and handle null values:
Replace missing age values with the median age.
Replace NaN cabin values with 'No Cabin'.

Data Visualization:

Plot a histogram to visualize the distribution of passenger ages.
Create a horizontal bar chart to display the gender distribution among passengers.
Generate a bar chart to illustrate the distribution of passengers across different ticket classes.
Plot the distribution of fares to understand ticket price variability.

Explore survival rates:
Plot survival rates by gender.
Plot survival count by ticket class.

Examine correlation between numerical values:
Calculate correlation between 'Survived' and 'Fare', identifying a correlation coefficient of 0.26.

Insights:

Survival rate by sex and class: Analyze the data to observe that survival rates for females are higher compared to males within their respective ticket classes. Additionally, higher ticket class correlates with higher survival rates.

Repository Structure:

Code: Contains Python scripts for data cleaning and visualization.
Data: Includes the Titanic dataset in CSV format.
Visualizations: Stores generated plots for easy access.
README.md: Provides an overview of the project, EDA steps, insights, and repository structure.
