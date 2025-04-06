# Data-Preparation-Analysis-and-Visualization-Project
Cleaned and prepared the dataset by refining columns, removing duplicates, handling missing values, and filtering outliers, followed by insightful visualizations like pie charts, bar charts, box plots, and KDE plots to analyze trends effectively.

# *Project Overview:*
The requirement was to clean and analyze a vehicle dataset (data.csv) for insights. Columns irrelevant for analysis were dropped, and others were renamed for clarity. Duplicate rows and missing values were handled, and outliers were removed using the IQR method. Visualizations included a pie chart (Drive Mode), line plot (Year trends), horizontal bar chart (Make), histogram (Price), box plot (Price vs. Vehicle Size), stacked bar chart (Vehicle Size), and KDE plot (Highway MPG). These steps ensured a refined dataset and effective analysis. Let me know if you need more information.

# *Project Work Done: Data Preparation, Analysis, and Visualization:*

*Data Import and Exploration:*
-Imported the dataset (data.csv) and previewed its structure using .head(), .tail(), and .dtypes.

*Data Cleaning and Transformation:*
-Dropped irrelevant columns, such as "Engine Fuel Type" and "Market Category."
-Renamed columns for better readability (e.g., "Engine HP" → "HP," "Driven_Wheels" → "Drive Mode").
-Removed duplicate rows and handled missing values by dropping them.

*Outlier Detection and Removal:*
-Applied the IQR method to numeric columns to identify and remove outliers, ensuring a cleaner dataset.

*Dataframe Shape and Sampling:*
-Checked the updated shape of the dataframe and sampled random rows for a quick review of data diversity.

*Visualizations:*
-Created several plots for better data understanding:
Pie Chart: Showed the proportion of "Drive Mode" categories.
Line Plot: Illustrated trends over "Year."
Horizontal Bar Chart: Displayed vehicle counts by "Make."
Histogram: Visualized price distribution.
Box Plot: Compared "Price" across "Vehicle Size" categories.
Stacked Bar Chart: Represented counts for "Vehicle Size."
KDE Plot: Displayed the density of Highway MPG (MPG-H).

# *How to Run:* 
To run this project, download the Jupyter Notebook source file and dataset, place them in your Jupyter Notebook environment folder, open the file, and start working on it.
