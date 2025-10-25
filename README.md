# 📊 Interactive Sales Dashboard in Excel 📈

Welcome! This project demonstrates an end-to-end data analysis workflow, transforming a raw, 100,000+ row relational dataset into a fully interactive, one-page dashboard... **entirely within Excel**. 🚀

## 📸 Dashboard Preview

Here is a static screenshot of the final dashboard. The live, interactive version is available in the project files!


<img width="1429" height="786" alt="Dashboard_Grocery - Excel 25-10-2025 2_10_47" src="https://github.com/user-attachments/assets/e7dfb7e6-ef95-4f2b-830d-cff62e32cddd" />

*(Note: The above image is a static screenshot. The fully interactive dashboard is available in the `Sales_Dashboard_Lite.xlsx` file.)*

---

## 🎯 Project Objective

The goal was to simulate a real-world business intelligence task. Given a complex, multi-file sales dataset, the objective was to clean, model, and visualize the data to answer key business questions:

* ❓ What are the total sales and units sold?
* ❓ Who are the top-performing employees?
* ❓ Which product categories and countries are driving the most revenue?
* ❓ How do sales trend over time?

---

## 🛠️ Skills & Tools Demonstrated

* **Data Modeling (ETL):** Imported and integrated 7 distinct `.csv` files (Orders, Products, Customers, etc.).
* **Advanced Formulas:** Used `IFERROR(INDEX(MATCH))` to create a relational data model, linking tables (Orders, Products, Customers, Employees).
* **Feature Engineering:** Created new calculated columns (`OrderYear`, `OrderMonth`, `Revenue_PreDiscount`) to enable deeper time-based analysis.
* **Pivot Tables & Charts:** Aggregated over 100,000 data rows to build all charts and KPIs.
* **Dashboarding:** Designed a user-friendly, one-page dashboard.
* **Interactivity:** Implemented **Slicers** that control all charts and KPI cards simultaneously.
* **File Management:** Optimized the final `.xlsx` file by deleting the raw data sheet, relying on the Pivot Cache to create a "Lite" (1-2MB) interactive file from a 50MB+ source.

---

## 💡 Key Dashboard Features

* **Dynamic KPI Cards:** "Total Sales" and "Total Units Sold" cards that update instantly with all filter selections.
* **Geographic Analysis:** A live **Map Chart** visualizing sales by country.
* **Performance Tracking:** Top 10 Products and Top 10 Employees charts.
* **Trend Analysis:** A line chart showing sales over time.
* **Interactive Slicers:** Filter the *entire* dashboard by Year, Country, Category, or Employee.

---

## 🗂️ Data Sources

* **Kaggle Dataset:** The original, raw dataset was sourced from this [Kaggle Sales Dataset](https://www.kaggle.com/datasets/andrexibiza/grocery-sales-dataset).
* **Google Drive (Large File):** Due to GitHub's 25MB file limit, the main 100,000+ row "Orders" `.csv` file is hosted on Google Drive.
    * **[➡️ Download the large 'Orders.csv' file here](https://docs.google.com/spreadsheets/d/1ZaZTmtfQTtIJcGud2Mruva_KRwX526RX/edit?usp=sharing&ouid=114354495920273637040&rtpof=true&sd=true)**
* **Other Files:** All smaller lookup tables (`products.csv`, `customers.csv`, etc.) are in the `/data` folder.

---

## 🚀 How to Interact with this Dashboard

1.  Download the **`Sales_Dashboard_Lite.xlsx`** file from this repository.
2.  Open the file in Microsoft Excel (2013 or newer).
3.  Click on any of the slicers on the "Dashboard" sheet.
4.  Watch all the charts and KPI cards update instantly! ✨
