# Netflix-Content-Analysis-Dashboard-Report
Excel–Power BI Project | Netflix Content Analysis | From Raw Streaming Data to Content Insight

### Table of Contents
* [Project Overview](#project-overview)
* [Tools & Technology](#tools--technology)
* [Dataset Overview](#dataset-overview)
* [Data Cleaning & Transformation](#data-cleaning--transformation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Power BI Dashboard](#power-bi-dashboard)
* [Key Metrics](#key-metrics)
* [Findings](#findings)
* [Recommendations](#recommendations)
* [Future Work](#future-work)

### Project Overview
This project focuses on analyzing Netflix’s movie and TV show catalog to uncover insights about content distribution, genre popularity, ratings, production countries, 
and release trends over time. Using data visualization techniques, the project provides a comprehensive view of Netflix’s content strategy and how it has evolved. 
The final output is an interactive Power BI dashboard designed to support data-driven decision-making.

### Tools & Technology
The following tools and technologies were used in executing this project:
- Power BI: Data modeling, visualization, and dashboard creation
- Power Query: Data cleaning and transformation
- Microsoft Excel / CSV: Initial data storage and inspection
- DAX: Creation of calculated measures and key metrics

### Dataset Overview
The dataset contains information about Netflix’s movies and TV shows, including:
- Title name
- Content type (Movie or TV Show)
- Genre(s)
- Rating
- Country of production
- Release year
- Duration
The dataset covers content from multiple decades and across various regions, making it suitable for trend and comparative analysis.

Sample Preview
| show_id | type | title |director | cast | country | date_added | release_year | rating | duration | listed_in | 
|---------|------|-------|---------|------|---------|------------|--------------|--------|----------|-----------|
| s1 | Movie | Dick Johnson Is Dead | Kirsten Johnson |  | United States | September 25, 2021 | 2020 | PG-13 | 90 min | Documentaries |
| s2 | TV Show | Blood & Water |  | Ama Qamata, Khosi Ngema etc | South Africa | September 24, 2021 | 2021 | TV-MA | 2 Seasons | International TV Shows, TV Dramas, TV Mysterie |

### Data Cleaning & Transformation

