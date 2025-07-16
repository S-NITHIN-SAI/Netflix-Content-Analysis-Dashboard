# Netflix-Content-Analysis-Dashboard
This Tableau-based data visualization project explores Netflix's global content catalog (movies, TV shows) to uncover trends in content production, regional preferences, and genre popularity. The dataset includes show_id, type, title, director, country, date_added, release_year, rating, duration, and listed_in (genres).

Key Objectives

Identify content distribution by type (movie vs. TV show), country, and release year.

Analyze genre trends and seasonal content additions.

Visualize content maturity ratings and average durations.

Dataset

Source: Netflix Movies and TV Shows (Kaggle)

Columns Used:

type: Movie or TV show.

country: Production country(ies).

release_year: Year of content creation.

date_added: When content was added to Netflix.

rating: Maturity rating (e.g., PG-13, TV-MA).

duration: Movie runtime or TV show seasons.

listed_in: Genre(s).

Visualizations & Insights

Global Content Heatmap:

Finding: 70% of Netflix’s catalog is produced by the USA, India, and the UK.

Viz: Geographic map highlighting content volume by country.

Genre Trends (2015-2023):

Finding: “International Movies” and “Dramas” dominate the catalog. Documentaries show rapid growth (+120% since 2018).

Viz: Stacked bar chart by release year and genre.

Content Type Analysis:

Finding: Movies comprise 68% of the catalog. TV-MA (mature) is the most common rating.

Viz: Pie charts for type/rating distribution.

Monthly Additions:

Finding: Q4 (Oct-Dec) sees peak content additions (holiday strategy).

Viz: Line graph of monthly additions (2016-2021).

Tableau Dashboard Features

Interactive filters for country, rating, and year.

Dynamic tooltips showing title, director, and duration.

Top 10 genre rankings via treemaps.

Tools Used

Data Cleaning: Python (Pandas) to handle missing director/country values.

Visualization: Tableau Public (View Dashboard)
