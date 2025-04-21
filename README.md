🛒 Supermarket Sales Analysis & Regression
This project explores and models a real-world supermarket sales dataset. It combines exploratory data analysis (EDA) with regression modeling to understand key business trends and predict total sales based on product and customer features.

📂 Project Overview
📊 EDA: Explore trends by gender, product line, branch, payment method, and time.

🧠 Regression: Build a linear regression model to predict the Total purchase value.

📅 Time Series Insights: Analyze busy hours, peak days, and revenue fluctuations.

📈 Visualizations: Beautiful plots using Seaborn & Matplotlib.

📁 Dataset Info
The dataset used is Supermarket_Sales.csv, which contains:

Sales transactions from 3 branches in different cities

Key features:

Invoice ID, City, Customer Type, Gender

Product Line, Unit Price, Quantity, Tax, Total

Date, Time, Payment Method, Rating

🔧 Tools & Libraries
Python 3.x

pandas

seaborn

matplotlib

scikit-learn

🔍 Main Steps
Data Cleaning

Handled missing values

Converted Date and Time to datetime objects

Extracted time-based features like Hour, Month, Day

EDA (Exploratory Data Analysis)

Univariate plots: Gender, Product line, Payment methods

Bivariate analysis: Product vs Total, Gender vs Rating

Correlation heatmap & pairplots

Revenue trends by day and hour

Regression Modeling

Built a Linear Regression model to predict Total sale value

Evaluated using R² score and residual analysis
