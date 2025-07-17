
# 💼 WealthLens: Financial Overview Dashboard

A clean, visually-rich Power BI dashboard built to monitor and analyze personal financial performance. **WealthLens** helps track income, expenses, savings, and financial targets over time with intuitive visuals and insightful metrics.

---

## 🎯 Objective

- Monitor and evaluate income, expenses, savings, and financial goals
- Visualize spending and saving patterns across categories
- Measure monthly growth and financial health using dynamic KPIs
- Enable user-friendly navigation and interaction through filters, slicers, and buttons

---

## ✨ Key Features

- 📈 **Line Chart**: Shows time-based trends for income, expenses, savings, and targets  
- 🍩 **Donut Charts**: 
  - Breakdown of **Expenses** and **Savings** by category  
  - Tooltip reveals monthly values and changes  
- 📋 **Expandable Financial Table**: 
  - View complete breakdown of income, expenses, and savings  
  - Expand/collapse subcategories  
- 💡 **KPI Cards**:
  - Total income, expenses, savings, and targets  
  - % of savings and monthly growth for each  
  - Font color changes based on positive or negative growth  
- 🧭 **Filters & Controls**:
  - Button slicers for **years** (2021–2024)  
  - Dropdown slicer for **Month-Year**  
  - Calendar and refresh buttons for enhanced interactivity

---

## 🛠️ Tools & Techniques

| Tool        | Purpose                                 |
|-------------|------------------------------------------|
| Power BI    | Data visualization and dashboard design  |
| DAX         | Custom metrics, calculations, KPIs       |
| Power Query | Data shaping and transformation          |
| Excel       | Data source setup and structure          |

---

## 🖼️ Screenshot

![WealthLens Static View](./Assets/dashboard_preview.png)

---

## 📁 Project Files

```
📁 WealthLens-Finance-Dashboard
├── 📄 WealthLens_Dashboard.pbix
├── 📊 FinanceData.xlsx
├── 📁 Assets/
│   ├── dashboard_preview.png
│   └── wealthlens_demo.gif
└── 📄 README.md
```

---

## 🎞️ Dashboard Preview (GIF)

![WealthLens Demo](./Assets/wealthlens_demo.gif)

---

## 🧠 DAX Highlights

- `% Savings`, `% Target`, `% Income`, and `% Expenses`  
- **Monthly Growth** calculation for all financial indicators  
- **Dynamic Line Chart** using `Table1` to feed multiple metrics  
- **Date Dimension (Table2)** for accurate filtering: Year, Month-Year, and Date fields

---

## 📚 Learning Outcomes

- Designed an intuitive **personal finance tracking system** in Power BI  
- Developed advanced DAX calculations for **growth metrics** and **percent indicators**  
- Gained experience in **dynamic visual storytelling** using button slicers and tooltips  
- Built a structured **data model** to handle time intelligence and user interaction  
- Improved aesthetic and functional design to deliver a **dashboard ready for real-world use**
