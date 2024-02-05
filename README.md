# Thomson_Practical_Assignment_11.1
Found here is Blake's submissions for Practice Assignment 11.1

Project: Used Car Price Prediction Modeling

Background
The success of a used car dealership hinges on its capacity to sell its vehicle inventory at the highest possible prices. Unlike brand dealerships, used car dealerships have the flexibility to curate their inventory, making decisions based on perceived demand and customer pricing. Understanding the factors that drive car prices is essential for optimizing inventory selection and maximizing profits.

Objectives

The primary objective of this project is to provide guidance to the dealership regarding which cars are likely to sell for the highest prices. By leveraging machine learning techniques, we aim to identify the key features within the dataset that are correlated with higher-priced vehicles.

Data Problem Definition

The dataset comprises various features associated with used cars, including attributes like year, mileage, condition, fuel type, and more. The challenge lies in identifying the features that have the most significant impact on the selling price of a car. Through comprehensive analysis and modeling, we seek to uncover insights that will assist the dealership in making informed inventory decisions.

Results and Insights

Model Development

Model Attempt 1: Initial exploration involved removing all null values from the dataset, resulting in 68,000 rows. However, the performance metrics indicated poor predictive capability.

Model Attempt 2: Further refinement by removing select columns with high null values expanded the dataset to 330,000 rows. Despite the increase in data volume, the model's performance remained subpar.

Model Attempt 3: Employed different imputation techniques for handling null values, but failed to enhance model performance, leading to reduced accuracy.

Model Attempt 1.B: Applied Ridge regression for hyperparameter tuning, resulting in marginal improvement but still falling short of desired accuracy.

Model Attempt 4 (Successful): Leveraged Label Encoding and RandomForestRegressor, achieving significant improvement in predictive accuracy with an R-squared value of 0.902.


Key Insights

Sparse Dataset Challenge: Dealing with null values emerged as the primary obstacle, addressed through Label Encoding for preprocessing.

Model Selection: RandomForestRegressor outperformed LinearRegression, demonstrating superior predictive capability.

Key Factors: Features such as Year, Mileage, Cylinders, Drive, and Fuel Type emerged as critical determinants of car prices.

Data Diversity Impact: Limited diversity in certain features influenced model decisions, underscoring the importance of data quality and diversity.


Deployment Strategy
The model offers actionable insights into inventory management, empowering the dealership to optimize pricing strategies and make informed inventory decisions.
By leveraging predictive analytics, the dealership can enhance its competitive edge, capitalize on market trends, and maximize profitability.
This project underscores the importance of data-driven decision-making in the automotive industry, offering actionable insights that drive business growth and profitability. Further refinements and optimizations can be made based on ongoing analysis and feedback, ensuring continued relevance and effectiveness in a dynamic market landscape.
