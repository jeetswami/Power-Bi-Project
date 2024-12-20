# Zomato Business Analysis - Power BI Dashboard

## **Overview**
This project is a comprehensive analysis of Zomato's restaurant data across various continents, countries, and cities. The interactive Power BI report helps the business unearth hidden anomalies, evaluate performance metrics, and make data-driven decisions.  

## **Features**
The report includes:
1. **Global Insights**: View data at a global level, with drill-down capabilities to continents, countries, and cities.
2. **Performance Metrics**:
   - Top-performing restaurants by average ratings and lowest average cost.
   - Count of restaurants based on geographical and service filters.
3. **Interactive Filters**:
   - Filter by geography, services (online delivery/table booking), and rating colors.
4. **Cuisines Analysis**:
   - Top-ranking restaurants by the variety of cuisines served.
5. **User-Friendly Navigation**:
   - Multi-page report aligned with Zomato's branding and optimized for desktop and mobile devices.

## **Data Workflow**
1. **Data Import**:
   - Imported restaurant data from multiple Excel files (e.g., Africa, Asia, Europe).
2. **Data Cleaning**:
   - Corrected city names and removed unnecessary columns.
   - Created separate columns for restaurant names, addresses, and cuisines served.
3. **Data Modeling**:
   - Defined relationships between tables with appropriate cardinality.
   - Created user-defined geographical hierarchies.
4. **DAX Measures**:
   - `Restaurant Count`, `Average Cost`, `Average Rating`, and `Cuisine Count`.
   - Added calculated columns such as `Rating Color` and `Continent`.

## **Data Visualization**
The report is divided into:
1. **World Wide Analysis Report**:
   - **Card Visuals** for average cost, average rating, and restaurant count.
   - **Map Visual** showing restaurant distribution by continent, country, and city.
   - **Top 5 Restaurants** by cost and ratings using infographic visuals.
2. **Restaurant Analysis Report**:
   - Filters for rating colors, countries, and cities.
   - Detailed restaurant information (address, cuisines, etc.) in grid visuals.
   - Gauges for selected restaurant’s average cost and rating.

## **Files in the Repository**
- `Zomato_Analysis_Report.pbix`: Power BI report file.
- `data/`: Sample data files.
- `DAX_Scripts.txt`: DAX calculations used in the project.
- `screenshots/`: Report and visualization screenshots.

## Screenshots
## Dashboard Overview

- [World Wide Analysis Dashboard] ![5](https://github.com/user-attachments/assets/56c5f937-931f-42ae-ab4d-6f5b5f03ac8c)

- [Restaurant Analysis Report] ![6](https://github.com/user-attachments/assets/2c4b95ef-fca9-4fa4-b825-0882b2ca65ec)

## Mobile Layouts

![1](https://github.com/user-attachments/assets/7c8c45ff-4adf-4106-a437-47abf5634c84)

![2](https://github.com/user-attachments/assets/d52b8675-3a3b-4489-8093-0929a863ec0f)

![3](https://github.com/user-attachments/assets/eb9b2b8b-26cd-4a67-8dd6-3af25ded7931)

![4](https://github.com/user-attachments/assets/be76605b-6966-4585-a69e-bbc9c6507174)














