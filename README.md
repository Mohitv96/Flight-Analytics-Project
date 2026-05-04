Flight Price Prediction: Data Cleaning & Preprocessing📊 
Project Overview:-This project involves the comprehensive cleaning and feature engineering of a flight dataset containing 15,000 records. The primary goal was to transform raw aviation data into a structured, numerical format optimized for SQL databases and Power BI visualization.  The entire transformation logic is documented and executed within the Flight_data.ipynb Jupyter Notebook. 

Data Cleaning Steps
The following technical workflows were implemented in Flight_data.ipynb:  

Date Normalization: Converted the date_of_journey column into a standard datetime format.  

Time-Series Feature Extraction: Extracted specific day and month columns from the journey date to identify seasonal trends.  

Categorical Encoding: Cleaned the Total_stops column by replacing "non-stop" with 0 and extracting integers from strings like "2 stops".  

Time Transformation: Engineered a custom Python function to convert the Duration string (e.g., "3h 15min") into a total numerical value of duration_total_mins.  

Text Cleaning: Standardized the Additional_info column by converting to lowercase, stripping whitespace, and consolidating "no info" values into "none".  

Dimensionality Reduction: Dropped redundant columns such as the original Duration and index to optimize storage and processing speed.
