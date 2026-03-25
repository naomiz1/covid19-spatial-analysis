# COVID-19 Spatial Analysis Using Geographic and Demographic Data

## 📌 Project Overview
This project analyzes the spread of COVID-19 across the United States by integrating geographic, demographic, healthcare, and transportation data. The goal is to understand how different factors such as population density, medical infrastructure, and proximity to transportation hubs influence infection rates.

## 🎯 Research Objectives
- Analyze the relationship between population density and COVID-19 infection rates  
- Evaluate the impact of healthcare accessibility on infection outcomes  
- Investigate how proximity to major airports affects virus transmission  

## 📊 Data Sources
- U.S. Census Bureau (population and demographic data)  
- Department of Health and Human Services (healthcare facilities data)  
- Federal Aviation Administration (airport traffic data)  

## 🛠️ Methodology

### 1. Data Preprocessing
- Cleaned and standardized datasets across multiple sources  
- Handled missing values and inconsistent formats  
- Merged datasets using state and county identifiers  
- Added geographic coordinates (latitude & longitude)  

### 2. Data Integration
- Built a unified database combining:
  - COVID-19 case data  
  - Population data  
  - Healthcare facility data  
  - Airport location data  

### 3. Feature Construction
- Calculated infection rate: Infection Rate = COVID Cases / Population
- Linked geographic proximity between counties and airports  
- Aggregated healthcare facility counts by region  

### 4. Analysis Techniques
- SQL queries for data extraction and transformation  
- Spatial analysis using ArcGIS Online  
- Geographic visualization (heatmaps, scatter maps)  

## 📈 Key Results

- High infection rates are **not always associated with high population density**  
- Several rural regions show **unexpectedly high infection rates**  
- Areas with **limited healthcare facilities** tend to have worse outcomes  
- Regions near **major transportation hubs (airports)** show higher infection intensity  
- Virus spread is influenced by both **mobility patterns and healthcare accessibility**  

## 🗺️ Visualizations
- U.S. infection rate heatmap  
- Population density vs infection rate spatial plot  
- Healthcare facility distribution vs infection rate  
- Airport proximity and infection spread analysis  

## 🧱 Data Pipeline
1. Data collection from multiple public sources  
2. Data cleaning and normalization  
3. Data integration and database construction  
4. SQL-based feature extraction  
5. Spatial visualization and analysis  

## 💻 Tools & Technologies
- SQL  
- Python (data preprocessing)  
- ArcGIS Online  
- Data Visualization  

## 📌 Conclusion
This project demonstrates that COVID-19 spread is influenced by multiple interacting factors, including healthcare access and transportation networks. The findings highlight the importance of improving medical infrastructure in rural areas and monitoring high-mobility regions for effective public health intervention.

## 👤 Authors
Xumeng (Naomi) Zhang, KaYi Jennifer Kwok, Weiyu Qian
