# 🚗 Car Sales Dashboard – Power BI Project

## 📌 Project Overview  
Welcome to the **Car Sales Dashboard** project!  
This Power BI dashboard is designed for a car dealership to provide **dynamic, interactive, and real-time insights** into sales performance.  
By visualizing key metrics and trends, the dashboard empowers stakeholders to:  
- Make **data-driven decisions**  
- Monitor progress  
- Identify growth opportunities  

---

## 🎯 Objective  
The primary goal of this project is to design and develop a comprehensive dashboard that:  
- 📊 Tracks critical **Key Performance Indicators (KPIs)** related to car sales  
- 📈 Visualizes sales trends and distributions across various dimensions  
- ⏱️ Enables real-time monitoring and strategic analysis  
- ✅ Supports decision-making with interactive charts and detailed grids  

---

## 📊 KPI Requirements  

### 🔹 Sales Overview  
- **YTD (Year-to-Date) Total Sales**  
- **MTD (Month-to-Date) Total Sales**  
- **YOY (Year-over-Year) Growth in Total Sales**  
- **Difference between YTD Sales and Previous YTD (PTYD) Sales**

### 🔹 Average Price Analysis  
- **YTD Average Price**  
- **MTD Average Price**  
- **YOY Growth in Average Price**  
- **Difference between YTD Average Price and PTYD Average Price**

### 🔹 Cars Sold Metrics  
- **YTD Cars Sold**  
- **MTD Cars Sold**  
- **YOY Growth in Cars Sold**  
- **Difference between YTD Cars Sold and PTYD Cars Sold**

---

## 📈 Charts & Visualizations  

| Chart Title                   | Description |
|-------------------------------|-------------|
| **YTD Sales Weekly Trend**    | Line chart showing weekly YTD sales trend *(X-axis: Weeks, Y-axis: Total Sales Amount)* |
| **YTD Total Sales by Body Style** | Pie chart displaying distribution of YTD sales across car body styles |
| **YTD Total Sales by Color**  | Pie chart showing contribution of car colors to YTD total sales |
| **YTD Cars Sold by Dealer Region** | Map chart visualizing geographic distribution of YTD cars sold by region |
| **Company-Wise Sales Trend Grid** | Tabular grid listing each company with their YTD sales figures |
| **Detailed Car Sales Grid**   | Table showing all car sales data including model, body style, color, amount, region, and date |

---

## 🧩 Data Model & Sources  
The dashboard is built on a robust data model integrating multiple sources:  
- **Sales Transactions Table** → Contains individual car sales records  
- **Car Details Table** → Includes model, body style, color, and pricing  
- **Dealer Information Table** → Provides regional and company-level data  
- **Date Table** → Supports time-based calculations and filtering  
<img width="1455" height="817" alt="Screenshot 2025-08-04 201312" src="https://github.com/user-attachments/assets/0e5d5688-d009-4d98-97fa-d6385f767a47" />
<img width="1445" height="805" alt="Screenshot 2025-08-04 201349" src="https://github.com/user-attachments/assets/f253d60e-9857-448b-951b-02bbac2ffe25" />

---

## ⚙️ Features & Interactivity  
- 🔍 **Slicers** for filtering by date, region, body style, and color  
- 📌 **Drill-through** capabilities for detailed analysis  
- 💡 **Dynamic tooltips** for contextual data insights  
- 📱 **Responsive layout** optimized for desktop and mobile views  

---

## 📁 File Structure  

```plaintext
CarSalesDashboard/
│
├── README.md               # Project documentation
├── CarSalesDashboard.pbix  # Power BI dashboard file
├── Data/
│   ├── SalesData.csv       # Raw sales data
│   ├── CarDetails.csv      # Car specifications
│   └── DealerInfo.csv      # Dealer and region data
└── Assets/
    └── Screenshots/        # Dashboard preview images
