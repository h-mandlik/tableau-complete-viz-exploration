# Tableau Visualization Practice Project – Sales Dataset

📊 This project is a hands-on Tableau workbook created to explore and practice **all major chart types**, **sets**, **filters**, and **parameters** using a structured dataset containing orders, returns, and users. The goal is to gain mastery over Tableau’s core visual features and interactivity controls.

---

## 📁 Dataset Used

The project uses three tables:

### 📦 Orders Table (Main Data Source)
- Contains sales transactions with fields like:  
  `Order ID, Order Date, Region, Customer Segment, Profit, Sales, Discount, Product Category, Product Sub-Category, etc.`

### 🔁 Returns Table
- Fields: `Order ID, Status` (used for return tracking or joins)

### 👤 Users Table
- Fields: `Region, Manager` (used for manager-wise or region-wise mapping)

---

## 📊 Visualizations Created

| Chart Type | Columns Used | Description |
|------------|--------------|-------------|
| **Bar Chart** | Region (X), SUM(Profit) (Y) | Profit across regions |
| **Stacked Column Chart** | Region (X), SUM(Profit) (Y) | Shows how profit is distributed |
| **100% Stacked Column** | Region (X), SUM(Profit) (Y) | Relative profit contribution per region |
| **Stacked Bar Chart** | SUM(Profit) (X), Region (Y) | Horizontal layout of profit per region |
| **100% Stacked Bar** | Same as above | Shows proportional contributions |
| **Area Chart** | YEAR(Order Date) (X), SUM(Profit) (Y) | Profit trends over time |
| **Line Chart** | YEAR(Order Date) (X), SUM(Sales) (Y) | Sales growth over years |
| **Scatter Plot** | SUM(Sales), SUM(Profit) | Analyzes correlation between sales and profit |
| **Pie Chart** | Customer Segment, SUM(Sales), SUM(Profit) | Share of segments by sales and profit |
| **Tree Map** | Customer Segment, SUM(Sales) | Space-efficient segment-wise sales |
| **Sales Filter Practice** | Product Sub-Category, SUM(Sales) | Used filters and slicers for dynamic exploration |
| **Symbol Map** | State, SUM(Sales) | Sales mapped geographically using points |
| **Filled Map** | State, SUM(Sales) | Heatmap-like geographic sales view |
| **Funnel Chart** | Region, SUM(Sales) | Sales funnel showing central region as top performer |
| **Packed Bubbles** | Region, SUM(Sales) | Circular size-coded sales comparison |
| **Set (Static/Manual)** | Product Sub-Category | Used set for filtering sales values across categories |
| **Parameter – Top N** | Product Sub-Category, SUM(Sales) | Created a parameter to dynamically show Top N items (e.g., Office Machines ranked highest) |
| **Parameter + Set – Bottom N** | Product Sub-Category, SUM(Sales) | Combined logic to extract Bottom N items (e.g., Rubber Bands lowest with 15,007 sales) |

---

## 🛠️ Key Features Practiced

- ✅ Filters (both interactive and global)
- ✅ Manual and dynamic **Sets**
- ✅ Top N / Bottom N filtering using **Parameters**
- ✅ Combined **Sets + Parameters**
- ✅ Basic **joins/relationships** using Returns and Users tables
- ✅ **Dual-axis charts**, **tooltip customization**, and **chart sorting**
- ✅ Dashboard filters using dropdowns and checklists

---

## 📷 Dashboard & Chart Previews

Screenshots available in the `images/` folder.

> Example:  
> ![Bar Chart Example](data/Profit - Region.png)  
> ![Top N Parameter Filter](images/parameter_top_n.png)

---

## 📂 Project Structure

