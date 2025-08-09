# 📊 Sales Performance & Insights Dashboard  

### 🔗 Dashboard Link: *https://app.powerbi.com/view?r=eyJrIjoiNmQ1YWYwMGMtYjBkMC00YzFkLTkxYzgtM2ZlOTIzZGUzNjRlIiwidCI6IjEzOWQ5NmE0LWUxMzktNDZkMy05MDkwLTU0ZDMxNTBlM2NhMiJ9*  

---

## 📝 Problem Statement  

This dashboard provides a **comprehensive view** into product performance, discount strategy, sales trends, and customer behavior for the period **2020–2024**.  

It helps businesses:  
- 📌 Identify top & bottom-performing products by sales, quantity, and profit  
- 📌 Analyze the impact of discounts & promotions on sales  
- 📌 Track seasonal & yearly sales trends  
- 📌 Spot high-performing cities & regions  
- 📌 Optimize profit margins and inventory planning  

By consolidating data into an interactive **Power BI** dashboard, decision-makers can focus on **data-backed strategies** to boost sales, optimize discounts, and improve the product mix.  

---

## ⚙️ Steps Followed  

### **Step 1 – Data Loading**  
- Imported dataset (CSV) into **Power BI Desktop**.  

### **Step 2 – Data Quality Check**  
- Opened **Power Query Editor**  
- Enabled *Column Distribution*, *Column Quality*, and *Column Profile* under View tab  
- Set profiling to **entire dataset**  

### **Step 3 – Data Cleaning & Transformation**  
- Checked for nulls & errors in key columns  
- Verified numeric columns for outliers and correct data types  
- Standardized date formats and applied proper currency formatting  

### **Step 4 – Key Measures & Calculations**  
- 🛍️ **Total Orders**: `COUNTROWS(SalesTable)` → 3,510  
- 💰 **Total Sales**: `SUM(SalesTable[Net Sales])` → ₹129M  
- 📈 **Total Profit**: `SUM(SalesTable[Profit])` → ₹12.23M  
- 🏆 **Top Product**: Apple iPhone 14 – ₹21.4M Sales  
- 📍 **Top City**: Bangalore  
- Created measures for *Sales by City*, *Sales by Product*, *Profit Margin*, *Discount Analysis*, and *Units Sold*  

---

## 📊 Visuals Created  

1. **KPI Cards** – Total Orders, Total Sales, Total Profit, Top Product, Top City  
   ![KPI Cards](https://github.com/user-attachments/assets/076633b8-15da-4842-8150-5446e1e0ddba)

2. **Period Comparison** – Sales, Profit & Quantity Analysis Between Two Time Frames  
   ![Period Comparison](https://github.com/user-attachments/assets/cc854e47-3c1f-422f-8eb8-fa11ec8463dd)  

3. **Scattered Chart** – Profit vs. Sales  
   ![Profit vs Sales](https://github.com/user-attachments/assets/9be906d2-aa83-4c95-aa36-56ab366504c6)    

4. **Bar Charts** – Top 5 & Bottom 5 Products by Sales, Profit, Quantity  
   ![Product Performance](https://github.com/user-attachments/assets/eba07e6f-64fe-433a-8a20-afe4d775de57)    

5. **Maps** – Net Sales by City  
   ![Sales by City](https://github.com/user-attachments/assets/014345ad-7928-4ab2-9573-3b36a44ce0b0)    

6. **Bar Chart** – Average Discount by Promotion Type  
   ![Discount Analysis](https://github.com/user-attachments/assets/c6296892-8da3-4283-9f0b-9eb114461e7c)    

7. **Filters & Slicers** – Date, Product, Promotion, Customer Name  
   ![Filters](https://github.com/user-attachments/assets/c8e3b0ed-8d14-415e-af85-7950fe7adddc)   

8. **Published Dashboard** – Power BI Service View  
   ![Published Dashboard](https://github.com/user-attachments/assets/aea47030-c63b-4591-b552-2ca9f01d2747)  

---

## 📌 Insights  

**1️⃣ Overall Sales Performance**  
- 🛍️ **Total Orders**: 3,510  
- 💰 **Total Sales**: ₹129M  
- 📈 **Total Profit**: ₹12.23M  
- 🏆 **Top Product**: Apple iPhone 14 (₹21.4M Sales, ₹2.14M Profit)  
- 📍 **Top City**: Bangalore
  
![Insights](https://github.com/user-attachments/assets/ac73ed32-f2db-4951-8cb7-22edc1f6de8c)   

**2️⃣ Top Products by Sales**  
![Top Products](https://github.com/user-attachments/assets/603a3dfe-07e5-4ab6-9654-78e1f6222f75)    

**3️⃣ Bottom Products by Sales**  
![Bottom Products](https://github.com/user-attachments/assets/9991d881-9a12-447e-98bc-2f4bb62e829d)       

**4️⃣ Top Cities by Sales**  
![Top Cities](https://github.com/user-attachments/assets/8f92de83-2308-4f4c-afc0-38cef4257a15)


**5️⃣ Promotions Impact**  
![Promotions Impact]("https://github.com/user-attachments/assets/228426ad-e263-4ca8-9f82-e83092184c82)


**6️⃣ Sales Trends**  
![Sales Trends](https://github.com/user-attachments/assets/a509e970-33f5-4a77-92bb-b56d057b1c1c)  

---

## 💡 Business Recommendations  

1. 🌏 Focus marketing efforts on **top cities** – Bangalore, Delhi, Kolkata  
2. 📉 Optimize **low-performing products** with low sales/profit  
3. 🏷 Refine **discount strategies** – leverage top campaigns like *Weekend Fest*  
4. 🎉 Strengthen **festive season campaigns** to capture peak demand  

---

## 🛠 Tools & Technologies Used  
- **Power BI Desktop & Service** – Dashboard creation & publishing  
- **DAX** – Calculated measures & KPIs  
- **Power Query** – Data cleaning & transformation  

---

## 🙋‍♀️ Author

**Pragati Kumari**  
_Data Analyst | Power BI | Excel | SQL | Python_  
🔗 [LinkedIn](#) *(Add your actual profile link)*

---

## 🚀 How to View the Dashboard

1. Download the `.pbix` file  
2. Open in **Power BI Desktop**  
3. Interact using slicers and filters  

---

## 📄 License

Open for learning and portfolio demonstration. Not for commercial use.

