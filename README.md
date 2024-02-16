# Capstone_Final_Project

## Project/Goals

The primary objective of this project is to showcase proficiency in key data science skills, including data wrangling, unravelling nuanced trends / correlations and visualization. Additionally completing this project ensured I utilized all the skills / knowledge I had gain with respect to the following:

SQL: Query proficiency including SELECT, INSERT, UPDATE, DELETE, and JOIN statements.

Python Programming: proficiency in in writing python code, and using libraries and frameworks specifically designed for data analytics, such as NumPy, Pandas, Matplotlib, Seaborn. Python concepts like Functions, Methods etc.

Data Collection/Retrieval, Analysis and Exploration: Proficiency in accessing & integrating relevant data from diverse sources (using APIs or from Databases), Cleaning and transforming data, loading data into a database, Performing EDA, including using both descriptive statistics and visualizations.

Visualizations: Proficiency in using Tableau to provide meaningful insights, and effectively communicate trends, comparisons, and correlations within the datasets to key stakeholders.

In completing this Project, I utilized datasets sourced by querying the API from Aviation Stack, encompassing real time and historical global aviation/flight data. The dataset contained a number of quantitative and categorical features such as departure time, arrival time, arrival delay, departure delay, airline, origin and destination airport, among others. The goal was to provide a comprehensive understanding of & visual insights to enable key stakeholders determine flight departure delay trends and appropriate plan their future air travel with minimal flight delays.


## Process

1.	Data Collection

Datasets for this project by querying the API from Aviation Stack, encompassing real time and historical global aviation/flight data, encompassing quantitative and categorical features such as departure time, arrival time, arrival delay, departure delay, airline, origin and destination airport, among others.

-	Explored the structure of the APIs. Queried the APIs endpoints to retrieve information and studied the Data returned.

-	Parsed JSON object and converted same into Pandas Data frame. Created an SQLite database, merged and store the data in the Database. Also saved Dataframe as CSV.

2.	Data Cleaning and Preparation

Performed Data cleaning and EDA to explore the possible relationships within the data and utilized visualizations, such as box plots. 

Data cleaning processes were employed to ensure accuracy and consistency including handling missing values, standardizing formats, and validating data. Inconsistencies and outliers were identified and addressed to prevent skewing of results.

3.	Tableau Integration and Interactive Dashboards

Tableau, a powerful data visualization tool, was employed for its versatility and user-friendly interface. The cleaned datasets were imported into Tableau, relationships between variables were established, Custom calculations and aggregations were performed to derive meaningful insights, and various visualization types were utilized to effectively communicate trends, comparisons, and correlations within the datasets.
Created interactive dashboards in Tableau, incorporated filters, parameters, and tooltips to enhance user interactivity and provided an intuitive and informative visual representation of the flight departure delays at key Canadian Airports.


## Results

Key Findings & Trends:
•	Flights with scheduled departure time in the evenings or during peak hours, have higher likelihood of delays.
•	The Calgary International Airport (YYC) has the least average flight delays out of all the 4 major Canadian international airports.
•	Airlines with the least average delay include Air India, Copa Airlines and Egypt Air.
Understanding these factors can help in making informed decisions, such as avoiding peak departure times to minimize the risk of flight delays.



## Challenges 
    
Choosing the right API endpoint (Retrieving the right data from the API).
Data limitation with API (I could only query the API for historical data for one date per query and also had limitations on the number of queries).
Deciding on the most effective visualization to appropriately pass across “the message” to key stakeholders.
Time constraint (while completing the project) due to multiple pressing demands at work and at home.


## Future Goals

•	Given additional time and resources, more data collection to span across multiple years to avoid any biases / skewed analysis.
•	Use more advanced Python code to achieve same task (fewer lines of code).
•	Started working on project early (Time management).
•	Refine visualizations for enhanced clarity and aesthetics.
•	Conduct further analysis to uncover additional insights.
•	Consider additional external factors that might have contributed to the trends observed in the data.

