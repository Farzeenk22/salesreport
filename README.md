# Beverage Sales Dashboard 2026 (Power BI)

An interactive Power BI dashboard analyzing beverage sales performance across brands, retailers, U.S. regions, and months, complete with both Desktop and Mobile layouts.

## Project Overview
This project explores retail beverage sales data to uncover revenue trends, top-performing brands, and regional demand. The dataset contains **1,000 rows** and **11 columns** (`Retailer`, `Retailer ID`, `Date`, `Region`, `State`, `Beverage Brand`, `Price per Unit`, `Units Sold`, `Revenue`, `Month Name`, and `Month`).

## Data Preparation (Power Query)
Before building the visuals, the raw dataset was cleaned and transformed in Power Query:
* **Calculated Revenue:** Created a new `Revenue` column by multiplying `Units Sold` by `Price per Unit`.
* **Date Feature Extraction:** Extracted `Month Name` and `Month` (month number) from the `Date` column to enable chronological monthly trend sorting.

## Key Metrics & Visuals
* **Headline KPIs:** Total Revenue (**$8.48M**), Average Price/Unit (**$0.49**), and Total Units Sold (**17M**).
* **Monthly Revenue Trend:** Column chart tracking monthly revenue fluctuations, peaking in December (**$1.02M**) and July (**$0.97M**).
* **Retailer Market Share:** Pie chart breaking down unit sales across retailers (**Sodapop** leads with **56.33%**, followed by **FizzySip** at **20.52%** and **BevCo** at **18.26%**).
* **Geographic Distribution:** Interactive dark-mode map showing units sold across U.S. states and regions.
* **Interactive Filtering:** Button slicer allowing users to filter the entire report by **Beverage Brand** (*Coca-Cola, Dasani Water, Diet Coke, Fanta, Powerade, Sprite*).
* **Mobile-Responsive Layout:** Dedicated vertical mobile view optimized for smartphone screens.

## Dashboard Preview

### Desktop View
![Desktop Dashboard](screenshot<img width="1165" height="652" alt="Screenshot 2026-11-17 113238" src="https://github.com/user-attachments/assets/bcb74753-9039-40e5-96d0-0cd865dd857f" />
s/desktop_view.png)

### Mobile View
![Mobile Dashboard](screen<img width="417" height="688" alt="Screenshot 2026-11-17 120309" src="https://github.com/user-attachments/assets/8baee359-d04e-4e42-888c-331c665c1bbe" /><img width="411" height="655" alt="Screenshot 2026-11-17 120414" src="https://github.com/user-attachments/assets/72b063dc-cb78-4d8f-afc1-2fec7e81fff7" />
shots/mobile_view.png)

## Files in Repository
* `sales_dashboard.pbix` – Complete Power BI Desktop report file (includes Desktop and Mobile views).
* `sales_data.csv` – Dataset used for the analysis.
* `screenshots/` – High-resolution captures of the desktop and mobile layouts.

