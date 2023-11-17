# NYC-Airbnb-Investment-Insights
## Overview 
Led a comprehensive project focused on analyzing key metrics of NYC Airbnb data, employing strategic data-driven approaches to prioritize vacation rental properties, estimate annual revenue, and provide strategic insights for informed property investment decisions.
## Key Contributions
### Data Exploration and Cleaning
- Explored and reviewed NYC Airbnb dataset, identifying potential data cleaning challenges.
- Documented data cleaning steps and maintained a version history for reference.
### Filtering Listings:
- Filtered listings based on relevance, considering factors like rental activity, minimum night requirements, and recent reviews.
- Documented all removed rows, ensuring transparency in data cleaning steps.
### Prioritizing Property Types:
- Estimated rental activity using number_of_reviews_ltm as a proxy for property rental frequency.
- Identified top-performing neighborhoods through standardized capitalization and removal of trailing spaces in the neighborhood colum.
### Property Size Preferences:
- Cleaned the bedrooms column, creating a new column (bedrooms_clean) to substitute empty cells with zeros.
- Built a pivot table to determine the most popular number of bedrooms for vacation rentals.
### Calculating Occupancy:
- Cleaned the calendar data, converting the available column into a numeric value (occupied).
- Added a new column (day_of_week) using the WEEKDAY() function for analysis of popular weekdays vs weekends.
- Created a pivot table to calculate the average occupancy rate for each listing.
### Methodology:
- Utilized Excel for data exploration, cleaning, and pivot table analysis.
- Employed data filtering and proxy metrics for strategic decision-making.
- Applied advanced Excel functions for effective data standardization and analysis.
### Impact:
The project empowered stakeholders with data-driven insights for property investment decisions. By strategically analyzing rental activity, prioritizing neighborhoods, and understanding property size preferences, the project provided valuable guidance for optimizing investment choices. The estimated annual revenue of $6,948,586.22 for Lower East Side one-bedroom listings further enhanced decision-making capabilities, ensuring a strategic and informed approach to property investment in the NYC Airbnb market.
## Live Demo
[Link to Live Demo](https://docs.google.com/spreadsheets/d/1fCJS1ph2IX5sgJ2kZOO88lmfXCBiBDsvzbdTh0HmIbw/edit?usp=sharing)

