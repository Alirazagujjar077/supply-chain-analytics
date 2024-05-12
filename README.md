# supply-chain-analytics
This repository contains Python code for analyzing supply chain data and predicting late delivery using classification models.
Supply Chain Analytics and Late Delivery Prediction
Overview:
This repository contains Python code for analyzing supply chain data and predicting late delivery using classification models.

Dataset:
The dataset used in this project is the DataCo Supply Chain Dataset, which includes various features related to orders, customers, products, and delivery information.

Analysis and Cleaning:
Imported necessary libraries such as Pandas, NumPy, Matplotlib, Seaborn.
Mounted Google Drive to access the dataset from Google Colab.
Loaded the dataset and performed data cleaning:
Handled missing values in specific columns.
Created new features by combining existing ones.
Renamed and formatted column names for consistency.
Grouped data for analysis by various categories like delivery status, market, region, customer segment, etc.
Data Visualization:
Visualized the distribution of sales and customer segments.
Analyzed market distribution and category-wise sales.
Explored delivery status distribution and late delivery risks.
Plotted a scatterplot to understand the relationship between scheduled and actual shipment days.
Late Delivery Prediction:
Prepared data for modeling by encoding categorical variables.
Split the dataset into training and testing sets.
Utilized Random Forest, Support Vector Machines, and Gaussian Naive Bayes classifiers for late delivery prediction.
Evaluated model performance using accuracy, recall, and F1 score.
Created a DataFrame to compare classification results.
Instructions for Usage:
Clone the repository to your local machine.
Ensure you have Python installed along with necessary libraries (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn).
Access the dataset from Google Drive or modify the code to load data from your local system.
Run the Python script in your preferred environment (e.g., Jupyter Notebook, Google Colab).
Analyze the results and explore insights gained from the data.
