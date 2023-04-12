#  Technion-Data-Science-Projects

##Introduction:
This project aims to demonstrate how to perform data analysis using Python, Excel complex functionalities (Power Query + Power Pivot) and Power BI. 

# Python Data Analysis Project
This sub-project includes a sample dataset of churning clients, a power point presentation that explains about the project and a jupyter notebook that showcase various data analysis techniques.

##Goals and Tools:
The purpose of this project is to show how to solve a real business problem – the prediction of whether a customer will churn or not. 
In my jupyter notebook I used the following Python libraries:
Pandas - to work with the dataset. I Used the library's functionality for analyzing, cleaning, exploring, and manipulating data.
NumPy – to perform a wide variety of mathematical operations on arrays.
Matplotlib – to create 2D graphs and plots by using python scripts.
Seaborn – to make statistical graphics in Python.

##Solution Steps:
1. Data Description - Checking label distribution, handling missing values and performing feature quantity.
2. Data Engineering - Data Cleaning, removing non informative features, calculating summary groups from the existing data and adding them as new features.
3. Finding correlations and relationships between different features in the dataset.
4. ML Algorithms – Using the following machine learning models to predict the churn percentage from the modified dataset:

•	Decision tree 

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github.com/orlytaf/Technion-Data-Science-Projects/blob/main/Python%20Data%20Analysis/Visualizations/Decision%20Tree%20plot.png">
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/orlytaf/Technion-Data-Science-Projects/blob/main/Python%20Data%20Analysis/Visualizations/Decision%20Tree%20plot.png">
 <img alt="Decision Tree Plot" src="https://github.com/orlytaf/Technion-Data-Science-Projects/blob/main/Python%20Data%20Analysis/Visualizations/Decision%20Tree%20plot.png">
</picture>

•	Random Forest
•	K Nearest Neighbors

5. Algorithms Introspection - Inspecting various algorithm artifacts and performing Feature importance and overfitting checks.

##Final Output:

A jupyter notebook that describes the flow of different data analysis steps.
The creation of this notebook can also be used as a problem-solving baseline for various business problems.

##Conclusions:

•	In the churn analysis we saw the importance of retaining clients with tenure group of more than 30 months – total charges from long term clients are higher from other tenure groups.
•	It seems better to encourage clients to sign with 1\2 years contract and not month-to-month payment, because clients with 1\2 year contract are less likely to churn.
•	It may be a good idea to check and limit the monthly payment sum of clients, as there is a big increase in clients churn rate when the monthly payment is getting higher than 70$.

