---
title: DepEd Masterlist 2020-2021
author: Yabut Reinael
date_created: July 30, 2025
last_updated: July 30, 2025
version: v1.0
status: Done
tags:
  - EDA
  - Data
data_sources:
  - Data Source 2
alignment: This projects aims to find insights in the DepEd Schools that is posted in Data Jobs in the DEP page
---
# DepEd School Masterlist Dashboard (S.Y. 2020-2021)

## Project Overview

This project presents a comprehensive visualization of the Department of Education (DepEd) Masterlist of schools for the School Year 2020-2021. The primary goal is to analyze and present key insights into the distribution and characteristics of educational institutions across the Philippines. By leveraging a custom Python script for data extraction, data cleaning in Excel, and visualization capabilities in Power BI, this dashboard provides an at-a-glance understanding of the educational landscape.

## Data Source

The dataset used is the official **DepEd Masterlist of Schools for S.Y. 2020-2021**. It was sourced directly from the Department of Education's official website in PDF format.

- **Source**: Department of Education (DepEd)
    
- **Link**: [Masterlist of Schools S.Y. 2020-2021](https://www.deped.gov.ph/wp-content/uploads/2021/06/SY-2020-2021-Masterlist-of-Schools-Address-only-1-1.pdf)
    

## Tools Used

- **Python**: Used to write a custom script for extracting data from the source PDF.
    
- **Microsoft Excel**: Utilized for the data preparation phase, including cleaning, validation, and structuring.
    
- **Microsoft Power BI**: Used for creating the interactive dashboard, data modeling, and visualization.
    

## Methodology

The project was executed in a three-stage process to transform raw data into an insightful dashboard:

1. **Data Extraction**: The source data was provided as a PDF document. A custom Python script was developed to parse this PDF, extract the school masterlist data, and convert it into a structured CSV file, making it accessible for analysis.
    
2. **Data Preparation**: The CSV file was imported into Microsoft Excel for data cleaning and validation. This stage involved handling missing values, correcting inconsistencies, standardizing naming conventions, and structuring the data into a clean, tabular format suitable for visualization.
    
3. **Data Visualization**: The prepared data was loaded into Microsoft Power BI to create an interactive dashboard. The process involved data modeling and using DAX calculations to derive key metrics, such as percentages for school locales.
    

## Key Findings

- **Regional Distribution**: Region IV-A (CALABARZON) has the highest concentration of schools with 5,060. Region III (Central Luzon) and Region VI (Western Visayas) follow with 3,660 and 3,560 schools, respectively.
    
- **Division-Level Distribution**: At the division level, Iloilo has the most schools with 1,054, followed by Cebu with 904.
    
- **School Locale**: A significant majority of schools, **73.72%** (30,640), are located in "Partially Urban" areas. "Urban" areas host 22.1% (9,180 schools), while "Rural" areas account for 4.18% (1,740 schools).
    
- **Sector Breakdown**: The educational landscape is dominated by **Public** schools, which number 29,840, compared to 11,530 **Private** schools.
    

## Visualizations

The project's visualizations are consolidated into a Power BI dashboard. Key visuals include:

- A horizontal bar chart showing the number of schools per region.
    
- A horizontal bar chart displaying the top school divisions by count.
    
- A donut chart illustrating the percentage and raw count of schools by locale (Urban, Partially Urban, Rural).
    
- Bar charts for school distribution by Legislative District and Sector (Public, Private, SUCs/LUCs).
    

## Code

The Python script used for converting the source PDF to a CSV file is available at the following GitHub repository:

- **Link**: [https://github.com/yabswannalearn/deped_masterlist](https://github.com/yabswannalearn/deped_masterlist)
    

## Challenges and Solutions

- **Challenge**: The primary challenge was that the official data was only available in a PDF format, which is not suitable for direct data analysis.
    
- **Solution**: A custom Python script was created to programmatically extract the data from the PDF and convert it into a structured CSV format. This automated the extraction process and made the data usable for the subsequent stages.
    
- **Challenge**: The raw extracted data contained inconsistencies and needed cleaning.
    
- **Solution**: Microsoft Excel was used for thorough data cleaning and validation, ensuring the accuracy and integrity of the data before visualization.
    

## Community Impact

This project can serve as a valuable resource for various stakeholders in the Philippine community.

- **Educational Planners and Policymakers**: Can use the dashboard to identify regions and divisions with a high density of schools and those that may be underserved, aiding in resource allocation and strategic planning.
    
- **Researchers and NGOs**: Can leverage this data to study the educational landscape, conduct further analysis, and support advocacy for educational equity.
    
- **Local Government Units (LGUs)**: Can gain insights into the educational infrastructure within their locality, helping to plan for community development and support local schools.
    

## Future Work

- **Incorporate Longitudinal Data**: The dashboard could be enhanced by including data from previous and more recent school years to analyze trends over time.
    
- **Integrate Additional Datasets**: Add other relevant data, such as student enrollment numbers, teacher-to-student ratios, or school performance metrics (e.g., National Achievement Test scores), to provide a more holistic view.
    
- **Publish Interactive Dashboard**: Publish the Power BI dashboard online to allow the public to interact with the data directly, increasing its accessibility and impact.
    
- **Geospatial Analysis**: Add a map visualization to show the geographic distribution of schools, which could reveal spatial patterns and clusters.
    

## Contributors

- yabswannalearn
    

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://www.google.com/search?q=https://github.com/yabswannalearn/deped_masterlist/blob/main/LICENSE&authuser=1) file for details.