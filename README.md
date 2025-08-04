# CineNova Studios Movie Data Analysis

## Project Overview
CineNova Studios is planning an entry into the film industry and is seeking strategic insights to produce high-grossing movies. This project analyzes historical movie data to identify key patterns, trends, and success factors that can inform CineNova’s production and investment decisions.

## Objectives
The core objectives of this project are:

Identify the most profitable movie genres currently dominating the box office.

Evaluate key factors (e.g., genre, budget, release date) that contribute to a film’s financial success.

Analyze audience reception and critical ratings to understand their influence on box office performance.

Quantify the relationship between production budgets and revenue to determine optimal investment levels.

Assess market trends over recent years to identify emerging opportunities for new film content.

## Data Sources
The project uses data from multiple sources:

bom.movie_gross.csv – 3,387 rows, 5 columns

tmdb.movies.csv – 26,517 rows, 10 columns

tn.movie_budgets.csv – 5,782 rows, 6 columns

rt.movie_info.tsv – 1,560 rows, 12 columns

rt.reviews.tsv – 54,432 rows, 8 columns

im.db (IMDb SQLite database) – Genres, average ratings, and vote counts were extracted into a dataframe with 73,856 rows

## Data Cleaning
Verified and corrected data types, especially date and numeric fields.

Replaced null values with median for skewed numerical distributions.

Filled missing categorical values with mode.

Removed irrelevant columns and confirmed no duplicate entries across datasets.

Converted string-based date fields to proper datetime format for temporal analysis.

## Exploratory Data Analysis (EDA)
Performed both univariate and multivariate analysis on factors such as budget, release year, genre, and gross revenue.

Used bar graphs and heatmaps to visualize distributions, trends, and correlations.

Created additional columns like profit and return ratio to assess financial performance more precisely.

## Key Insights
Certain genres consistently yield higher profits.

Movies with larger production budgets often result in higher worldwide gross, but the return on investment varies.

Release dates and timing (especially holidays and summer seasons) have a measurable impact on performance.

Positive audience ratings and critical reception generally correlate with higher revenue.

## Recommendations
Focus on producing movies within top-performing genres.

Optimize budget allocation based on return ratios, not just gross income.

Schedule releases strategically during high-yield months.

Consider audience and critic ratings as part of the greenlighting process.

## Technologies Used
Python (pandas, seaborn, matplotlib, datetime)

SQLite

Jupyter Notebook

This project aims to provide CineNova Studios, which is preparing a massive expansion into the film industry, with some data-driven insights for strategic investment decisions. By examining historical movie data, including production budgets, ratings, popularity, revenues, release schedules, and genre performance, this analysis aims to identify the key elements that steer box office success. Additionally, this analysis summarizes the patterns of high-performing films. It offers insights to help CineNova allocate resources accordingly, maximize returns, and stay at the forefront of the competitive entertainment landscape.

Tableau link - https://public.tableau.com/app/profile/amos.obaga/viz/Bookt2_17543374462820/Dashboard1?publish=yes
