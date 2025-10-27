# netflix-powerbi-analysis
Data cleaning and visualization project analyzing Netflix content using Python and Power BI.
# 🎬 Netflix Data Analysis – Power BI Dashboard

## 🧠 Project Overview
This project explores Netflix’s catalog to uncover insights about content distribution, popular genres, and show types.  
I used **Python** for data cleaning and **Power BI** for visualization and storytelling.

---

## 🧹 Data Cleaning (Python)
Before importing the data into Power BI, I performed a full cleaning process using **Pandas**.  
Key steps included:

- Removing extra spaces and converting dates to datetime format  
- Filling missing values in columns such as *director*, *cast*, *country*, *rating*, and *duration*  
- Splitting the *duration* column into separate numeric and unit columns  
- Standardizing column names (lowercase, no spaces)  
- Dropping irrelevant columns for visualization  
- Saving the cleaned dataset to `cleaned_netflix.csv`  
