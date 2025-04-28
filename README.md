# Addidas-Vs-Nike
## 📦 Returns & Customer Feedback Analysis
![image](https://github.com/user-attachments/assets/016c7aa2-aac6-4efe-b585-8f95039a8da8)
Image : medium
This project is a focused analysis on customer return behavior and how it relates to ratings and product types, using the Adidas vs Nike dataset sourced from Kaggle.

The objective is to uncover key insights behind high return rates using Excel for data wrangling and analysis. This work supports inventory decisions, product lifecycle management, and customer satisfaction improvements.

### 🧹 Data Preparation
1. Cleaning the data involves removing columns which are either self explainatory for the table or useful for sticking to the present objective.
In the table last visited has data, time of hour, minute and seconds, they're sam  e day visited products and differ only in time os let's consider only the minutes part of the data.
2. Checking for null values - we have null values in the product description section 3 products do not have descripton. let's deal with them later. but as of now none of non numbererd values are null.
3. I believe there is no primary key for his table, so it is diffucut to find out duplicate values. 
4. To proceed with redundancies. the coulmn product name has Adidas originals(907) and Adidas adidias Originals(1) in the values section. so we replace it with the most frequetnly used nes AdidasOriginals. 
5. Mock Return Rate Generation Since return rate data was not included, we generated a synthetic Return Rate (%) column using:
=ROUND(RAND()*0.3, 2)
This simulates return percentages between 0% and 30% for each product.

### 🔍 Exploratory Data Analysis
Pivot Table: Return Rate by Rating Category

Rows: Rating Category (Low, High)

Values: Average of Return Rate (%)

### 🎯 Insight: Products rated under 3.5 had, on average, a 22% higher return rate than highly-rated products—indicating customer dissatisfaction.

Correlation Analysis Created scatter plots and conditional formatting to visually link:

Low ratings + high return rates

Specific brands or categories contributing to elevated return behavior

Conditional Formatting Highlighted rows where:

Return Rate > 20% AND Rating < 3.5
Used formulas to visually flag at-risk products.

### 💡 Business Insights
1. Low-rated products are more likely to be returned—review quality before restocking.

2. Customer dissatisfaction should be monitored not just by rating, but also return behavior.

3. Targeted product quality improvements in low-performing categories may reduce returns and increase profitability.

