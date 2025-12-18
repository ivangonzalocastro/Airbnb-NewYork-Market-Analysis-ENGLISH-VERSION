# Airbnb New York Market Analysis ENGLISH VERSION
_Data Normalization, Modeling &amp; Visualization with Excel and Power BI_

## Project Overview 📌 
This project analyzes Airbnb listings in New York City with the goal of understanding how location, room type, availability, pricing, and reputation impact accommodation prices and user experience.
The analysis follows a diagnostic analytics approach, transforming a raw dataset into a clean, structured data model and delivering interactive dashboards that support informed decision-making for travelers and market analysis.

![grabacion para porfolio](https://github.com/user-attachments/assets/2b766e3f-48eb-4740-86c6-575df208eced)

## Business Objective 🎯 
To evaluate how pricing behavior varies across neighborhoods, room types, and quality indicators, helping users better understand the Airbnb market and identify patterns related to location, flexibility, and reputation.

## Target Audience 👥 
Airbnb users planning business or leisure trips
Analysts interested in pricing and location-based analysis
Recruiters and teams evaluating data analytics and BI skills
No prior technical knowledge is required to interpret the dashboards.

## Dataset 🗂️
Source: Kaggle
Scope: Airbnb listings in New York City
Key attributes include:
- Location (neighborhood & borough)
- Room type
- Price per night
- Availability (365 days)
- Minimum nights
- Reviews & ratings
- Host verification
- Cancellation policies

## Data Preparation & Normalization (Excel) 🧹
Before importing the data into Power BI, the dataset was normalized using Excel, applying:
VLOOKUP / XLOOKUP to:
- Create reference tables (room type, neighborhoods, cancellation policy)
- Replace repeated categorical values with surrogate keys
- Column standardization and consistency checks
- Separation of main and satellite tables for relational modeling
This process reduced redundancy and improved data integrity.

## Data Modeling (Power BI) 🧩
A relational data model was built using a star-schema-like structure:
Fact Table: Airbnb Listings
Dimension Tables:
- Neighborhood
- Borough
- Room Type
- Cancellation Policy
- Host Verification
Relationships were defined using primary and foreign keys to enable efficient filtering and aggregation.

## Power Query Transformations ⚙️
Key transformations performed in Power Query include:
- Data type corrections
- Currency cleaning (removal of symbols, regional formatting)
- Error handling and row filtering
- Date formatting
- Sorting and trimming outliers

## DAX Measures & KPIs 📐
Several calculated measures were created, including:
- Average price per night
- Maximum and minimum price
- Average availability per year
- Average minimum nights
- Review and rating averages
- Total listings count
- Most frequent neighborhood and borough (mode)
These measures power the dashboards and KPIs.

## Dashboards & Visual Analysis 📊
<img width="846" height="470" alt="Captura de pantalla 2025-12-18 175744" src="https://github.com/user-attachments/assets/413ce116-4431-4c09-b924-4d1201d7bd9a" />

The Power BI report is structured into multiple analytical views:
### 🔹 Neighborhood Analysis
- Average price by neighborhood and borough
- Availability and room type distribution
- Identification of high-cost and high-density areas
<img width="863" height="486" alt="Captura de pantalla 2025-12-18 175809" src="https://github.com/user-attachments/assets/f036d417-13e7-4c96-98be-b51a2a665438" />

### 🔹 Quality & Reputation
- Relationship between ratings, number of reviews, and price
- Comparison of reputation across boroughs and neighborhoods
<img width="861" height="483" alt="Captura de pantalla 2025-12-18 175819" src="https://github.com/user-attachments/assets/ca3f6742-a6ff-47ff-947f-5ec61768db5c" />

### 🔹 Booking Rules & Availability
- Minimum nights vs availability
- Cancellation policies by area
- Percentage of verified hosts
<img width="858" height="486" alt="Captura de pantalla 2025-12-18 175835" src="https://github.com/user-attachments/assets/fd18b61f-7351-4b77-93ad-64f7bc3f1844" />


## Key Findings 🔍
Contrary to the initial hypothesis, Manhattan is not the most expensive borough on average; Staten Island shows the highest average prices.
There is no strong correlation between price and guest rating, indicating that higher prices do not guarantee better reviews.
Booking flexibility and host verification vary significantly by location.

## Tools & Skills Demonstrated 🛠️
Excel: Data normalization, VLOOKUP, XLOOKUP
Power BI:
Data modeling & relationships
Power Query transformations
DAX measures & KPIs
Interactive dashboards & tooltips
Data Visualization & Storytelling
Analytical thinking & business insight
