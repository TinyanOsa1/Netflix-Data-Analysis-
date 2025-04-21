# Netflix-Data-Analysis-
This project analyzes Netflix's Movies &amp; TV Shows dataset using Microsoft Excel and Power BI. It focuses on identifying content trends, exploring key metrics like genre, rating, and release year, and creating interactive dashboards to gain insights into Netflix's content strategy and growth.

## Project Overview

This project focuses on analyzing a Netflix dataset obtained from Kaggle, containing **8,807 records** and **12 attributes**. The dataset includes key information such as:

- Title  
- Director  
- Cast  
- Country  
- Date Added  
- Release Year  
- Rating  
- Duration  
- Genre (Listed In)  
- Description  
- Type (Movie/TV Show)  
- Category   

---

## Objectives

- Identify content patterns by rating, country, and year.  
- Explore top genres, most common ratings, and countries of origin.  
- Visualize the growth of Netflix content over time.

---

## Tools Used

- **Microsoft Excel**  
- **Power BI Desktop**

---

## Methodology

### Data Preparation

- Downloaded dataset from Kaggle in `.csv` format.  
- Cleaned the data in Excel:
  - Removed duplicates  
  - Handled missing values:
    
    • Replaced missing values in "Director" column with with real names as it relate to the movie or tv shows.
    
    • Remaining gaps were labeled as "NA"
    
  - Standardized text fields  
  - Dropped irrelevant columns (e.g., *Description*)
  

---

### Analysis

#### Excel

- Used **PivotTables** and **PivotCharts** to summarize key metrics (KPIs)
- Focused on genre distribution, rating frequency, content release over time, and country-wise production stats.
#### Data Visualization 

- Built a custom dashboard using a Netflix-inspired dark red theme.  
- Visuals included:
  - **Bar Charts** (Top 5 Genres, Rating Distribution)  
  - **Doughnut Chart** (Movies vs TV Shows)  
  - **Stacked Area & Column Charts** (Yearly & Country Trends)
  - **Line Charts** (yearly Trends)
  - **Geographic Map Visualizations** 


---

## Key Insights

- The **United States** leads in content production.  
- **TV-MA** is the most frequent rating.  
- Content releases peaked during **2016–2019**.  
- **Movies** greatly outnumber **TV Shows**.  
- Most popular genres are **Drama** and **Comedy**.

---

## Limitations

- External factors (e.g., market trends, COVID-19) were not accounted for.  
- Cultural preferences are not reflected in the dataset.

---

## Recommendations

- **Genre Optimization**: Explore sub-genres for more detailed trends.  
- **Content Diversification**: Invest more in TV shows, documentaries, and regional stories.  
- **Localization**: Increase content targeting emerging regions like **Asia** and **North Africa**.

---

## Next Steps

- Expand analysis with larger or more complex datasets.  
- Integrate streaming metrics (e.g., views, watch time) for deeper insights.  
- Continue refining data cleaning and visualization workflows.

---
# Dashboard 
**Excel**
![Netflix Excel Dashboard](Netflix%20Excel%20Dashboard%20.jpg)
___
**Power Bi**
![Netflix Power BI Dashboard](Netflix%20Power%20Bi%20Dashboard%20.jpg)
