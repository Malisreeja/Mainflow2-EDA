Superstore Sales Analysis

This project analyzes the Superstore dataset (Kaggle) using Python in Google Colab. The goal is to perform data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling to uncover insights about sales, profit, and discounts.

📂 Dataset

Source: Kaggle - Superstore Dataset

Contains transaction-level data with columns like:

Order Date, Ship Date, Sales, Profit, Discount, Category, Sub-Category, Region, Segment, etc.

⚡ Project Workflow
🔹 1. Data Loading & Cleaning

Loaded dataset in Google Colab.

Checked for missing values, duplicates, and handled them.

Converted date columns into datetime format.

🔹 2. Exploratory Data Analysis (EDA)

Summary statistics for Sales, Profit, Discount.

Found that:

Sales are highly skewed.

Profit contains both positive and negative values.

Discounts strongly impact profitability.

🔹 3. Data Visualization

Histograms → Showed sales are skewed; profits vary widely.

Boxplots → Revealed outliers in both sales and profit.

Heatmap → Found negative correlation between Discount & Profit.

🔹 4. Predictive Modeling (Linear Regression)

Built a Linear Regression model to predict Profit using Sales & Discount.

Results:

Positive impact of Sales on Profit.

Negative impact of Discount on Profit.

Model confirms business insight: "High discounts reduce profit margins."

📈 Key Insights

Majority of orders generate small sales values.

Some transactions cause losses due to high discounts.

Managers should be cautious with discount strategies.

Predictive modeling confirms that increasing discounts lowers profit significantly.

🛠️ Tech Stack

Python (Pandas, NumPy, Scikit-learn)

Visualization (Matplotlib, Seaborn)

Google Colab (for development & analysis)

🚀 How to Run the Notebook

Download dataset from Kaggle.

Upload to Google Colab.

Run the notebook cells step by step.

View analysis, visualizations, and regression results.

📌 Conclusion

This project demonstrates how EDA + Visualization + Predictive Modeling can help businesses understand their sales and profit patterns. The insights are useful for decision-making in pricing, discount policies, and sales strategy.

✨ Developed by MALI SREEJA
