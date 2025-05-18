This document outlines the steps taken to perform a comprehensive exploratory data analysis on California’s PM₂.₅ and AQI dataset. 
It is designed to guide you through loading, cleaning, summarizing, visualizing, and interpreting the air-quality data.

### 1. Project Structure

<img width="634" alt="image" src="https://github.com/user-attachments/assets/44b29b8f-52f7-421f-8cf9-fc43e580d2f9" />


### 2. Setup & Dependencies

Required libraries:

pandas

matplotlib

seaborn

### 3.  Data Loading & Cleaning
 i have used the datasets from kaggle to find the airquality of California.

 <img width="726" alt="image" src="https://github.com/user-attachments/assets/7144598a-632b-417e-8179-8346455f1586" />

<img width="653" alt="image" src="https://github.com/user-attachments/assets/3576125c-b6eb-4422-a003-2ce9bcea5bcc" />


### 4. Descriptive Statistics

<img width="822" alt="image" src="https://github.com/user-attachments/assets/682e5dd5-c68c-4b57-855c-0543cef37a8f" />


### 5.Temporal Trends:

Clear seasonal patterns were observed, with PM2.5 and AQI peaking during certain months, likely due to wildfires or weather conditions.
Rolling averages and time series decomposition revealed both long-term trends and seasonal cycles.
Geographic Patterns:

Some counties consistently report higher PM2.5 concentrations, indicating regional pollution hotspots.
County-wise analysis highlighted areas that may require targeted interventions.
Correlation Analysis:

There is a strong positive correlation between PM2.5 concentration and AQI, as expected.
Other numeric variables showed varying degrees of correlation, but PM2.5 remains the primary driver of AQI.
Outlier & Distribution Analysis:

Outliers were detected, especially during known pollution events.
Distribution fitting and Q-Q plots confirmed that both PM2.5 and AQI deviate from normality.


 ## Recommendations
 
### Policy & Public Health:

Focus air quality improvement efforts on counties with persistently high PM2.5 levels.
Issue public health advisories during high pollution months to protect vulnerable populations.
Further Analysis:

Investigate the causes of outliers and high pollution events (e.g., wildfires, industrial activity).
Use the cleaned and analyzed data for predictive modeling or forecasting future air quality trends.
Community Engagement:

Educate the public about seasonal air quality patterns and encourage actions to reduce exposure during high-risk periods.

