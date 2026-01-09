# Sales-Data-Cleaning-Validation-Analysis-using-Pandas
📌 Project Overview:

This project focuses on end-to-end sales data cleaning, validation, and analysis using Python (Pandas). The objective is to improve data quality by handling duplicates, missing values, invalid records, and outliers before performing business analysis. The project simulates real-world data quality challenges faced by data analysts.

🎯 Objectives:

Clean and standardize raw sales data
Validate business rules across financial, date, and payment fields
Perform customer, product, and sales analysis
Create derived metrics for better decision-making

🗂 Dataset Description:

The dataset contains sales transaction data with fields such as:
Order & Customer details
Product and category information
Pricing, discounts, profit, and total amount
Dates, delivery details, payment status, and feedback
(Note: Dataset used for learning and analysis purposes)

Tools & Technologies:

Python
Pandas
NumPy
Google Colab / Jupyter Notebook

 Key Tasks Performed
 Data Cleaning:

Removed duplicate records (Order_ID, Customer_ID, Email)
Handled missing values with logical defaults
Fixed invalid values (negative price, quantity, profit, age)
Corrected typos in categorical columns (Gender, Payment_Mode)
Standardized text and date formats

🔍 Data Validation:

Validated Total_Amount ≥ Price × Quantity
Checked Delivery_Date ≥ Order_Date
Identified outliers in Profit using IQR
Replaced invalid feedback scores
Validated payment status consistency
Checked invalid phone numbers and emails

⚙️ Feature Engineering:

Total_Purchase = Price × Quantity
Discounted_Price calculation
Delivery_Duration in days
Age_Group classification
Profit_Margin calculation
Encoding categorical variables

📊 Analysis & Aggregation:

Top products and customers by revenue
Average profit and discount by category
Customer loyalty analysis
Country and category-wise sales
Feedback score analysis

📈 Key Insights:

Identified high-value customers and VIP segments
Highlighted products generating maximum revenue
Ensured financial and delivery data consistency
Improved data reliability for downstream analytics.
