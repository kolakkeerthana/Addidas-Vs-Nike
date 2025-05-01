## 📦 Returns & Customer Feedback Analysis
**A Data-Driven Comparison of Adidas vs Nike**
![image](https://github.com/user-attachments/assets/016c7aa2-aac6-4efe-b585-8f95039a8da8)
Image : medium
This project explores customer return behavior and product satisfaction using a curated Adidas vs Nike dataset (sourced from Kaggle). The primary objective is to identify patterns behind high return rates and how they relate to product ratings, categories, and brands. The analysis was conducted using **Microsoft Excel**, focusing on actionable insights for product lifecycle decisions, inventory planning, and customer satisfaction strategies.

---

## 📊 Objective  
To analyze return patterns and their correlation with customer ratings and product types — supporting smarter decisions in fashion retail sales.

---

## 🧹 Data Preparation

1. **Column Filtering**  
   Non-relevant columns were removed to focus strictly on return behavior and product attributes.

2. **Timestamp Simplification**  
   The `Last Visited` column originally included date and time. Since all visits occurred on the same date, we reduced this field to minute-level granularity.

3. **Null Value Check**  
   - No critical nulls in numerical columns.
   - 3 products lacked descriptions — retained for now but flagged for further review.

4. **Brand & Product Name Normalization**  
   Identified inconsistencies in brand labels:
   - Replaced `"Adidas adidias Originals"` with standardized `"Adidas Originals"` (based on frequency).

5. **Mock Return Rate Simulation**  
   The dataset lacked a `Return Rate (%)`, so a synthetic return rate was generated:
   ```excel
   =ROUND(RAND()*0.3, 2)
   ```
   This simulates realistic return behavior between **0% and 30%** per product.

---

## 📈 Exploratory Data Analysis

### 🔁 Pivot Table: Return Rate by Rating Group
- **Rows**: Rating Category (`Low`, `High`)
- **Values**: Average Return Rate (%)
- Compared across brands and product lines.

- **Rows**: Rating Category (`Low`, `High`)
- **Values**: Average Return Rate (%)
- Compared across brands and product lines.

- **Rows**: Rating Category (`Low`, `High`)
- **Values**: Average Return Rate (%)
- Compared across brands and product lines.

- **Rows**: Rating Category (`Low`, `High`)
- **Values**: Average Return Rate (%)
- Compared across brands and product lines.

- **Rows**: Rating Category (`Low`, `High`)
- **Values**: Average Return Rate (%)
- Compared across brands and product lines.
---

## 🎯 Key Insights

1. **Nike**, although having fewer listings, generates more revenue **per product** even with lower discounts.
2. **Adidas Core** sells the most units but at a lower average price; these products also show **higher satisfaction** (lower return rates).
3. **Adidas Originals** dominates in total sales and revenue — despite a higher return rate.
4. Results are consistent across **USD and EUR regions**, with only minor variations in return ratios.
<img width="1206" alt="image" src="https://github.com/user-attachments/assets/dad717dd-ccfe-4184-9bd0-7cfb97caaf11" />
---

## 💡 Business Recommendations

- **Don’t rely solely on ratings**: High-rated products may still experience high returns — flag them for review.
- **Prioritize return rate monitoring** across brands and product lines — especially in high-volume segments.
- **Refine product quality** in low-rated, high-return segments (like certain Adidas Originals models) to improve profitability.

---

## 🧰 Tools Used

- Microsoft Excel (Pivot Tables, Slicers, Charts, Conditional Formatting)
- Excel Formulas for simulation and aggregation
- Visual dynamic Dashboard with KPI summaries and insights

---

## 📌 Conclusion

This project demonstrates how **basic Excel skills**, when applied thoughtfully, can drive **meaningful insights** in retail analytics. By combining product metrics, return behavior, and customer feedback, businesses can better manage inventory, reduce returns, and enhance satisfaction.
