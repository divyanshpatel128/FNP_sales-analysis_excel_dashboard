# FNP_sales-analysis_excel_dashboard
![image](https://github.com/user-attachments/assets/1721b30f-bc17-4cc3-86aa-07cd9bd78548)


As a data enthusiast, I created this Excel-based dashboard to help businesses in the gifting industry—like Ferns N Petals (FNP)—uncover actionable insights across sales, delivery, and product trends.

## ❓ Questions to Analyze

To optimize performance and customer experience, I asked:

- Which months generate the highest revenue?
- What are the top-performing products and categories?
- Which cities bring the most orders?
- How does performance vary by day of week and occasion?
- What’s the average delivery time, and how can it improve?

---

## 🧠 Excel Skills Used

This project highlights the advanced capabilities of Excel:

- 📊 Pivot Tables  
- 📈 Pivot Charts  
- 🧮 DAX (Data Analysis Expressions)  
- 🔍 Power Query (ETL)  
- 💪 Power Pivot (Data Modeling)

---

## 📊 Skill: Power Query (ETL)
![image](https://github.com/user-attachments/assets/6b4811a5-19bf-4b87-b217-f8230074907c)


### 📥 Extract

- Imported multiple raw data tables including sales orders, delivery records, and product details.

### 🔄 Transform

- Cleaned column formats, removed nulls, standardized date and category fields.
- Combined datasets into a master `data_table` to ensure clean model integration.

### 🔗 Load

- Loaded cleaned queries into the Data Model to create a powerful backend foundation for PivotTables and DAX.

---

## 📊 Analysis Breakdown

### 💡 Monthly Sales & Quantity Performance

- September and February show revenue spikes driven by seasonal campaigns.
- Majority of orders peak during those months—highlighting promotional impact.

### 📍 Top 10 Cities by Orders

- Imphal, Dibrugarh, and Kadi lead in order volume—offering clues on regional growth.

### 🎁 Top Revenue Products

- Premium gifts like “Magnum Set” and “Quirk Gift” dominate top revenue—suggesting high-margin potential.

### 📅 Revenue by Days

- Sunday and Tuesday bring in the highest revenue, which helps optimize ad spend and staffing.

### 🎉 Revenue by Occasions

- Anniversary and Raksha Bandhan outperform all other occasions—great for focused campaigns.

### 📦 Categories

- “Colors” and “Sweets” bring consistent revenue—ideal for bundling or upselling.

---

## 🧮 Skill: Power Pivot
![image](https://github.com/user-attachments/assets/df724d8c-4491-4042-b48b-1fc1c18ec15c)


- Created a star schema model connecting `Orders`, `Products`, `Categories`, and `Occasions`.
- Linked all tables through unique IDs to maintain clean relationships and allow for one-click filtering.

---

## 📈 Skill: Pivot Charts & DAX

- Added DAX measures like:
```dax
Total Revenue := SUM(data_table[order_amount])
Average Delivery Days := AVERAGE(data_table[delivered_day])
Average order price :=DIVIDE([Total Revenue],[Total Orders])
```

- Interactive charts show:
  - Revenue by product
  - Orders by city
  - Category comparison

---

## 📌 File Summary

- https://github.com/divyanshpatel128/FNP_sales-analysis_excel_dashboard/tree/main/data_set — Excel dashboard file  
- Screenshots and visuals for presentation

---

## 🔚 Conclusion

This project illustrates how Excel—when used beyond the basics—can deliver business intelligence. With Power Query, PivotTables, and DAX, I turned raw data into a strategic dashboard.

Perfect for portfolio, interviews, and real-world business scenarios.

---

## 👤 Created by: Divyansh Patel  
_Aspiring Data Analyst | Excel Automation Enthusiast_

