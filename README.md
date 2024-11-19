# Python-Hospitality-Analysis
- **Project Objective:**  
  - 1. Conduct an analysis of booking trends, revenue, and occupancy rates for AtliQ Hotels.  
  - 2. Generate data insights to support decision-making for hotel management by visualizing and summarizing key performance metrics.

- **Purpose of Data Analysis:**  
  - Provide insights into booking and occupancy patterns, revenue distribution, and customer preferences to help drive strategic decisions.

- **Importance of Analyzing Hotel Data:**  
  - Identifies key trends in bookings and occupancy that aid in resource allocation, marketing strategies, and customer satisfaction improvements.

- **Role of Reports:**  
  - Facilitate effective planning around hotel occupancy, revenue forecasting, and customer engagement strategies.

## **Datasets**

- **dim_date.csv** - Date dimension data
- **dim_hotels.csv** - Details about hotel properties
- **dim_rooms.csv** - Information on different room types
- **fact_aggregated_bookings.csv** - Aggregated booking data
- **fact_bookings.csv** - Detailed booking records

## **Project Steps**

- **Data Import and Exploration:**  
  - Imported libraries and loaded datasets into Pandas DataFrames.  
  - Conducted initial data exploration to understand dataset structures and key attributes.

- **Data Cleaning:**  
  - Checked for and handled missing values, duplicates, and other data quality issues.

- **Data Transformation:**  
  - Merged datasets to create a unified data view.  
  - Created new features such as occupancy rates and revenue metrics.

- **Insights Generation:**  
  - Generated visualizations and summaries to derive insights, including:
    - Booking platform distribution
    - Revenue contribution by city
    - Occupancy rates by hotel and month
    - Comparative analyses of hotel performance across different locations

## **Key Visualizations**

- **Booking Platform Distribution:**  
  - A bar chart displaying the count of bookings per platform.

- **Hotel Locations by City:**  
  - A bar chart showing the number of hotels in each city.

- **Occupancy Rates by City:**  
  - A bar chart showing average occupancy rates by city.

- **Revenue by Booking Platform:**  
  - A pie chart illustrating revenue distribution across platforms.

## **Technical & Analytical Skills**

- [x] **Proficiency in data manipulation using Pandas**
- [x] **Visualization skills with Matplotlib**
- [x] **Data cleaning, including handling missing values and duplicates**
- [x] **Merging datasets to create comprehensive data views**
- [x] **Generating actionable insights and reports from complex datasets**

## **How to Run**

- Clone the repository:
  ```bash
  git clone <repository-url>
  ```
- Open `exercise_solution.ipynb` in Jupyter Notebook or Jupyter Lab.
- Run all cells in sequence to reproduce the analysis.

## **Dependencies**

- **Python 3.x**
- **pandas**
- **matplotlib**

- Install dependencies using:
  ```bash
  pip install pandas matplotlib
  ```
