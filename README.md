**Movie Dataset Analysis — Pandas + Matplotlib**
**Project Overview**

This project explores a movie dataset using Pandas for data analysis and Matplotlib for visualization.
The dataset includes details like movie name, rating, genre, release year, director, budget, gross income, and more.

**Data Cleaning & Preparation**

**Steps performed:**

Displayed dataset overview using head(), tail(), info(), and dtypes()

Checked dataset shape, size, and duplicate values

Removed duplicate rows using drop_duplicates()

Checked for missing data with isnull().sum() and removed nulls with dropna()

Converted year column to datetime using pd.to_datetime()

Filtered and analyzed subsets (e.g., movies from Canada or PG-rated films in Brazil)

Verified unique entries like directors, countries, and stars

**Data Exploration**

**Explored:**

Number of movies by genre

Distribution of movies by country

Top directors and their average IMDb scores

Correlation between budget and gross revenue

Movies released per year trend

**Visualizations (Matplotlib)**

**Bar Chart:** Average IMDb Score by Genre

**Line Chart:** Movies Released per Year

**Scatter Plot**: Budget vs Gross

**Horizontal Bar Chart:** Top 10 Directors by Score

**Bar Chart**: Top 10 Highest Grossing Movies

**Technologies Used**

Python

Pandas

Matplotlib

**Files**

movies.csv — Raw dataset

movies_cleaned.csv — Cleaned dataset

movie_analysis.py — Analysis and visualization code

**Key Learnings**

Data cleaning and transformation in Pandas

Handling missing and duplicate data

Creating visual insights using Matplotlib
