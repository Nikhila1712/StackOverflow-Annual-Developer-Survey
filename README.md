# StackOverflow-Annual-Developer-Survey
This repository contains an analysis of the Stack Overflow Developer Survey data. The analysis aims to explore various aspects of developers' demographics, work preferences, and compensation. The dataset has been cleaned and processed to ensure accurate and meaningful insights.

# Overview
The Stack Overflow Developer Survey is a comprehensive survey that collects data on developers' demographics, employment, coding activities, education levels, and more. This repository provides an in-depth analysis of the survey data, focusing on key questions such as the impact of education on employment, the most popular methods of learning to code, and the distribution of employment statuses among developers.

# Data Cleaning
The dataset has undergone extensive cleaning to ensure high-quality analysis. The following steps were performed:

Drop Columns with High Missing Values: Columns with more than 50% missing values were removed.
Fill Missing Values in Categorical Columns: Missing values in categorical columns were filled with the mode (most frequent value).
Fill Missing Values in Numerical Columns: Missing values in numerical columns were filled with the median.
Convert Data Types: Ensure numerical columns are in the correct data types for analysis.
Handle Specific Columns: Specific attention was given to columns like YearsCodePro to convert them to numeric values and handle errors appropriately.
