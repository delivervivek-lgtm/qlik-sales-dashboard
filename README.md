# Qlik Sense: Financial Sales Dashboard

### 🔴 Live Demo (Video)


https://github.com/user-attachments/assets/9ca3f4ce-1d97-4555-9461-95b95b032701



---

### 📖 Project Objective

The goal of this dashboard is to provide a high-level overview of sales, profit, and product performance. It allows executives to analyze performance by country and product and see cumulative sales trends over time, all based on a sample financial dataset.

---

### 🛠️ Technical Skills Implemented

This project demonstrates my ability to use Qlik Sense's most powerful features:

* **Set Analysis:** Used Set Analysis (e.g., `Sum({1} Sales)`) to create the "Total Company Sales" KPI, providing a stable baseline for comparison against filtered data.
* **Table Calculations:**
    * **Rank:** Used `Rank(Sum(Sales))` to build the "Product Rank" table, which updates dynamically based on user selections.
    * **Running Total:** Used `Rangesum(Above(...))` to calculate the cumulative sales trend in the line chart.
* **Visualizations & Design:**
    * **Combo Chart:** Built a dual-axis chart (bars + line) to show `Sum(Sales)` and `Profit Margin` by segment.
    * **Master Items:** Created reusable drill-down dimensions and measures.
    * **Associative Model:** The final dashboard is fully interactive, allowing users to click any data point to filter the entire application.

---

### 📊 Final Dashboard
<img width="1919" height="856" alt="Qlick Dashoard Picture" src="https://github.com/user-attachments/assets/21d49aca-7696-4a7c-b96e-2db90dec93f7" />


