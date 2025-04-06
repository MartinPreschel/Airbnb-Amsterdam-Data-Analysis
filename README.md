# Airbnb Amsterdam Data Analysis

## Project Overview
This project analyzes **Airbnb listings in Amsterdam** to uncover pricing patterns, host behaviors, booking trends, and neighborhood dynamics. The insights derived from this analysis aim to support data-driven decisions for hosts, travelers, and policymakers.

### Key Questions:
- **Which neighborhoods have the highest average nightly prices?**
- **How does room type affect the price of a listing?**
- **Do Superhosts charge more than regular hosts?**
- **What types of listings receive the most reviews per month?**
- **Can we group similar listings into distinct clusters?**
- **Is it possible to predict nightly prices based on listing features?**
- **How has availability changed over time across neighborhoods?**

## Dataset Information
The following datasets are used in this analysis:
- **listings.csv.gz** – Airbnb listing data including prices, reviews, location, host type, etc.  
  Source: [Inside Airbnb](http://insideairbnb.com/get-the-data.html)
- **neighbourhoods.geojson** – GeoJSON file of Amsterdam neighborhoods  
  Source: [Data Amsterdam](https://data.amsterdam.nl/)
- **neighbourhoods.csv** – Custom file to map listing neighborhood names to the GeoJSON labels
- **Time series data** – External data sourced via Quandl for availability trend analysis

## Tools & Technologies Used
This analysis was conducted using **Python** and the following key libraries:
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Seaborn** & **Matplotlib** – Data visualization
- **GeoPandas** & **Folium** – Geospatial data analysis and mapping
- **Scikit-learn** – Predictive modeling and clustering
- **Statsmodels** – Time series decomposition and stationarity testing

## Programming Languages
- **Python** (Jupyter Notebooks for the analysis)

## 📂 Folder Structure
The project follows a structured folder system:
```
📂 Airbnb_Amsterdam_Analysis/
│-- 📂 01_Project_Management/        (Project brief, planning notes)
│-- 📂 02_Data/
│    ├── Raw/                        (Original datasets)
│    ├── Cleaned/                    (Cleaned datasets used for analysis)
│-- 📂 03_Notebooks/                 (Python notebooks for each analysis step)
│    ├── 6.1_data_cleaning.ipynb
│    ├── 6.2_exploration.ipynb
│    ├── 6.3_geovisualization.ipynb
│    ├── 6.4_predictive_modeling.ipynb
│    ├── 6.5_clustering.ipynb
│    ├── 6.6_time_series.ipynb
│-- 📂 04_Analysis/
│    ├── Visuals/                    (Generated charts and maps)
│-- 📂 05_Final_Assets/              (Slides, reports, and final presentations)
```

## How to Setup & Run the Project
1. **Prerequisites:** Ensure you have **Python 3.x**, **Jupyter Notebook**, and **Anaconda** installed.
2. **Clone the project**:
   ```bash
   git clone https://github.com/your-username/airbnb-amsterdam-data-analysis.git
   ```
3. **Set up the Python environment**:
   ```bash
   pip install pandas numpy matplotlib seaborn geopandas folium scikit-learn statsmodels
   ```
4. **Start Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
5. **Run the analysis within the provided notebooks**.

## 📊 Tableau Storyboard
Explore the interactive dashboard summarizing key insights from this project:

👉 [Airbnb in Amsterdam – A Data-Driven Exploration](https://public.tableau.com/views/AirbnbinAmsterdam-AData-DrivenExploration/Story1?:language=de-DE&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

---
