# 🧠 RetailVisor – Sales Analytics Dashboard using Power BI

RetailVisor is a professional business intelligence dashboard designed using Power BI. It enables users to analyze retail sales data with visual clarity and interactive filters. The dashboard delivers key insights into sales trends, profit analysis, product performance, and state-wise distribution, supporting informed decision-making.

---

## 🚀 Overview

- **Tool**: Power BI Desktop  
- **Purpose**: Analyze sales data and provide insights  
- **Scope**: Track sales, profit, and product trends across regions and categories  
- **Duration**: One-year data (12 months)

---

## 🔧 Tools & Technologies

- Power BI Desktop  
- Microsoft Excel / SQL (for preprocessing if required)  
- DAX (Data Analysis Expressions)  
- Power BI Map and Custom Visuals

---

## 🗂️ Data Description

| Feature           | Description                              |
|------------------|------------------------------------------|
| Order ID         | Unique transaction ID                    |
| Order Date       | Date of order                            |
| Product Category | Furniture, Office Supplies, Technology   |
| State            | U.S. States                              |
| Sales            | Revenue generated                        |
| Profit           | Profit earned                            |
| Quantity         | Number of items sold                     |

---

## 📊 Key DAX Metrics

| Measure           | Formula / Purpose                              |
|-------------------|------------------------------------------------|
| Total Sales       | `SUM(Sales)`                                   |
| Total Profit      | `SUM(Profit)`                                  |
| Profit Margin     | `(SUM(Profit) / SUM(Sales))`                   |
| Total Orders      | `DISTINCTCOUNT(Order ID)`                      |
| Product Quantity  | `SUM(Quantity)`                                |

---

## 📈 Visualizations

| Visual                          | Purpose                                                                 |
|----------------------------------|-------------------------------------------------------------------------|
| **KPI Cards**                   | Show Total Sales, Profit, Orders, Profit Margin                         |
| **Line Chart**                 | Monthly trend of Sales and Profit                                       |
| **Bar Chart (Horizontal)**     | Top Products by Sales, categorized by Product Category                  |
| **Map with Pie Charts**        | State-wise quantity sold with category distribution                    |
| **Slicers (Month, Year, State, Category)** | Enable quick filtering of data                              |
| **Reset Filters Button**       | Clears all filters using bookmark functionality                        |
| **Conditional Formatting Cards**| Green for good profit margin, Red for poor performance (DAX-based)     |

---

## 📌 Insights Gained

- Technology dominates in sales but has thinner margins.
- November and December are peak months — likely due to holiday seasons.
- Canon and Fellowes products top the sales list.
- California, Texas, and New York lead in product quantity sold.

---

## 🧱 Challenges Faced

- Crafting DAX formulas for dynamic color cards.  
- Designing an informative yet uncluttered layout.  
- Customizing map visuals with meaningful pie overlays.  
- Maintaining responsiveness of visuals with multiple slicers active.

---

## ✅ Conclusion

RetailVisor successfully converts raw retail data into insightful visuals. The interactive Power BI dashboard equips users to:
- Monitor key performance indicators (KPIs),
- Identify high-performing products and states,
- Adjust strategies based on monthly and category-wise performance.

---

## 🔮 Future Scope

- Connect to live SQL database or cloud APIs  
- Add forecasting for future sales trends  
- Embed dashboard into Power BI Service with scheduled updates  
- Integrate email alerts for critical performance drops

---

## 🖼️ Preview

> ![Sales Dashboard Screenshot](./your-image-path.png)

---

## 👨‍💻 Developed By
**Vivek Kadam (Ganu)**  
3rd Year Engineering Student – AI & DS  
RetailVisor Project – 2025

