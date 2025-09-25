# Task-3
Dashboard Design
Dashboard Design – Interactive Sales Dashboard (Power BI)

📄 Objective
Design an interactive dashboard in Power BI for business stakeholders that highlights key KPIs (Sales, Profit, Growth) and allows decision-makers to quickly understand performance.

Dataset used: **Sample Superstore Sales Dataset (public dataset from Kaggle).

---

🛠️ Tools Used
- Power BI Desktop** – for data import, transformation, and dashboard design.
- Built-in Power BI visuals** (Cards, Line Charts, Bar Charts, Slicers, Navigation Buttons).
- Export to PDF / PPT** – to create a summary for stakeholders.

---

📝 What I Did

1. Data Loading & Preparation
- Imported the Superstore dataset into Power BI Desktop.
- Verified data types for key fields (dates, numeric columns).
- Ensured date fields are in correct datetime format for time-series analysis.

2. Dashboard Pages / Structure
I created a **multi-page dashboard**:

1. Page 1 – Overview (KPI Dashboard)  
   - KPI Cards for **Total Sales, Total Profit, Total Orders**.
   - Region-wise bar chart of sales.
   - Slicer for **Country** (applies to all pages).

2. Page 2 – Time-Series Analysis
   - Line charts showing **Sales** and **Profit** trends over time.
   - Filters to view by region and category.
   - Same Country slicer synced from Page 1.

3. Page 3 – Category & Region Insights 
   - Bar chart of Sales by Category.
   - Bar chart of Profit by Region.
   - Drill-down capability to view subcategories.
   - Country slicer synced here as well.

4. Page 4 – Summary Page  
   - Text box summarising the key insights from Pages 1–3 (performance overview, trends, and category/region highlights).
   - KPI cards repeated as a recap.
   - This acts as the “story conclusion” for stakeholders.

3. Dashboard Design Principles Applied
- **Right KPIs:** Focused on Sales, Profit, Growth metrics relevant to business stakeholders.
- **Slicers/Filters:** Added a Country slicer and synced across pages for interactivity.
- **Time-Series Analysis:** Included line charts for sales and profit trends over time.
- **Cards for Totals:** Used KPI cards for totals and summary.
- **Consistent Theme:** Kept colours simple and consistent across all pages.
- **Navigation Menu:** Added “Next” and “Back” buttons to move between pages like slides.

### 4. Deliverables Created
- **Interactive Power BI Dashboard (.pbix)** – complete with four pages.
- **PPT / PDF Summary** – exported visuals with main findings for presentation.

---

## 📊 Key Insights Example
- Sales and Profit are growing steadily over time in most regions.
- Technology and Furniture drive the highest revenue; Office Supplies is steady but smaller.
- Western regions outperform others in profit margins.
- Seasonal peaks and dips can be identified through time-series charts.

---

## 📁 Repository Contents
- `DashboardDesign.pbix` – Power BI file with the interactive dashboard.
- `DashboardSummary.pdf` – PDF export of the dashboard pages for quick viewing.
- `README.md` – This file, explaining what was done.

---

## 🚀 Outcome
By completing this task, I:
- Learned to create a multi-page, interactive dashboard in Power BI.
- Understood how to choose the right KPIs and visuals for business stakeholders.
- Used slicers, cards, and consistent design to make the dashboard easy to read.
- Produced a shareable report (PDF / PPT) summarising the main insights for decision-makers.

