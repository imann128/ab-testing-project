A/B Testing Project
Overview
This project performs A/B testing on the "Pakistan Largest Ecommerce Dataset" to analyze the impact of discounts and payment methods on customer behavior. It segments orders into groups—Discounted vs. No Discount and COD vs. Digital Payment—and calculates metrics like average order value to provide insights for optimizing ecommerce strategies.
Key Features

Data Cleaning: Preprocesses the dataset by handling missing values and formatting dates.
A/B Group Assignment: Segments orders based on discount status and payment methods.
Metric Calculation: Computes average_order_value for each group.
Output: Generates ab_testing_discount_payment.csv for further analysis.

Technologies Used

Python: Core programming language.
Pandas: Data manipulation and analysis.
Google Colab: Environment for running the notebook.

How to Use

Open A_B_Testing.ipynb in Google Colab or Jupyter Notebook.
Download and unzip the dataset (Pakistan_Largest_Ecommerce_Dataset.zip) to access Pakistan Largest Ecommerce Dataset.csv.
Place the unzipped .csv file in the same directory as the notebook.
Ensure the dataset (Pakistan Largest Ecommerce Dataset.csv) is in the same directory.
Run the notebook cells to preprocess data, assign A/B groups, and calculate metrics.
Explore the output file ab_testing_discount_payment.csv for results.

Dataset
Obtained from Open Data Pakistan
Source: Pakistan Largest Ecommerce Dataset.csv (included in the repository).
Contains ecommerce order details like grand_total, discount_amount, and payment_method.

Results
The notebook prepares a cleaned dataset with A/B groups, ready for statistical tests or visualizations to determine the effectiveness of discounts and payment methods on order values.

Project completed as part of my ecommerce analytics portfolio.
