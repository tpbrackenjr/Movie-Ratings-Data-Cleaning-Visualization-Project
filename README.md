# Movie-Ratings-Data-Cleaning-Visualization-Project
I asked ChatGPT to generate a messy movie ratings dataset and cleaned it using **Python** in **Jupyter Notebook**. After cleaning the data, I created visualizations in both **R** and **Power BI**.

Movie Ratings Data Cleaning & Visualization Project

I asked ChatGPT to generate a messy movie ratings dataset and cleaned it using **Python** in **Jupyter Notebook**. After cleaning the data, I created visualizations in both **R** and **Power BI**.

## 🧽 Data Cleaning (Python)
Steps performed in Python using pandas:
- Standardized column names (lowercase, underscores)
- Removed duplicate entries based on a custom `movie_id`
- Cleaned and standardized values in the `watched` column
- Filled in missing values (e.g., added release year for *Avatar*)
- Converted `year` to integer and clipped ratings between 1 and 5
- Exported the cleaned dataset to `.csv`

## 📊 Visualizations
- **R (ggplot2)**: 
  - Bar chart of average movie ratings
  - Histogram of rating distribution
  - Boxplot showing variation in ratings
- **Power BI**:
  - Interactive dashboard with slicers by reviewer
  - Clustered column chart of average ratings

## 🛠️ Tools Used
- Python (pandas, matplotlib)
- R (ggplot2, tidyverse)
- Power BI
- Jupyter Notebook
- GitHub

## 📁 Files
- `movie_ratings_messy.csv`: Original generated data
- `movie_ratings_clean.csv`: Cleaned version
- `movie_data_analysis.ipynb`: Jupyter Notebook with code and visuals
- `Movie_Data_Task.pdf`: Power BI export
- `README.md`: This file!

## 💡 What I Learned
This project helped me practice:
- Real-world data cleaning techniques in pandas
- Writing R code inside Jupyter using the R kernel
- Creating clean, meaningful visualizations in multiple tools
- Saving and sharing work in a reproducible format (Jupyter/GitHub)
