# NETFLIX-EDA
📺 Netflix Dataset Analysis
📌 Project Overview

This project analyzes the Netflix Titles Dataset using Python (Pandas, Seaborn, Matplotlib).
The goal is to understand content trends like types, genres, release years, countries, ratings, and durations.

📂 Dataset Details

Total Records: 8807

Total Columns: 12

Columns:

show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

🔎 Data Preprocessing

Handled missing values (director, cast, country, rating).

Replaced null director with “Unknown”.

Filled missing country with mode value.

Checked duplicates → 0 found.

📊 Exploratory Data Analysis (EDA)
🔹 Content Type Distribution

Movies: 6131

TV Shows: 2676
➡️ Movies dominate Netflix (~70%).

🔹 Country Distribution

Top 5:

United States – 3649

India – 972

United Kingdom – 419

Japan – 245

South Korea – 199

🔹 Release Year Analysis

Range: 1925 – 2021

Peak: 2017–2019

🔹 Top Genres

Documentaries, Stand-Up Comedy, Dramas, Comedies, Action & Adventure.

🔹 Ratings

Most common: TV-MA, TV-14, TV-PG, R, PG-13

Wide age coverage (Kids → Adults).

🔹 Movie Duration

Average: ~90 minutes

Most movies: 80–120 minutes

📈 Visualizations Used

Countplot: Movies vs TV Shows

Histogram: Release Year, Movie Duration

Line Plot: Content Trends over Time

Barplot: Top Countries, Top Genres

Heatmap: Feature Correlation

Pairplot: Feature Distribution

🧾 Key Insights

Netflix is movie-heavy, but TV shows are rising.

US & India lead in content production.

2017–2019 peak years for content release.

Documentaries & Comedies dominate genres.

Netflix provides content for all age groups.

🛠️ Tech Stack

Python 🐍

Pandas 📑

Seaborn 🎨

Matplotlib 📊

🚀 Future Work

Sentiment analysis of descriptions.

Recommendation system based on genres & ratings.

Time-series analysis of content growth trends.

✨ Author: Adarsh Kumar
📧 Contact: adar843462@gmail.com
