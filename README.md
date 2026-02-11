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
Several steps were taken to prepare the dataset for analysis:
- Removed duplicate and null values
- Standardized genre and country fields
- Split multi valued columns (e.g., genres and countries) for better aggregation
- Converted data types for accurate calculations
- Created calculated columns and measures to support analysis
These steps ensured data accuracy, consistency, and reliability.

### Exploratory Data Analysis 
Exploratory analysis was performed to understand overall patterns in the data:
- Distribution of movies versus TV shows
- Popular content ratings
- Most common genres on the platform
- Countries contributing the most content
- Growth of Netflix content over the years
This stage guided the selection of visuals and KPIs included in the dashboard.

### Power BI Dashboard
The Power BI dashboard provides an interactive view of Netflix’s content library. Key features include:
- KPI cards showing total titles, genres, and production locations
- Filters for country-level analysis
- Charts comparing movies and TV shows
- Genre popularity and rating distribution visuals
- Trend analysis over release years
The dashboard allows users to explore insights dynamically.

<img width="1178" height="658" alt="Screenshot 2026-02-05 214659" src="https://github.com/user-attachments/assets/0c585ea7-019b-4365-b743-5ba9a7bc5dca" />


### Key Metrics
The dashboard highlights the following key metrics:
- Total Titles: 8,802
- Total Genres: 515
- Total Production Locations: 749
- Movies: 69.62% of total content
- TV Shows: 30.38% of total content

### Findings
Key insights derived from the analysis include:
- Netflix’s content library is dominated by movies
- TV-MA and TV-14 are the most common content ratings
- International dramas are the most popular genre
- The United States is the leading content producer, followed by India
- Content production has increased significantly since 2015

### Recommendations
Based on the findings, the following recommendations are proposed:
- Expand family-friendly and children-focused content
- Increase investment in TV shows to balance content distribution
- Continue growing regional and international productions
- Leverage popular genres such as drama and documentaries for audience retention

### Future Work
Future improvements to this project could include:
- Sentiment analysis of Netflix content using viewer reviews
- Integration of viewership or subscription data
- Genre performance analysis by region
- Time-based forecasting of content growth
- Comparison with other streaming platforms
