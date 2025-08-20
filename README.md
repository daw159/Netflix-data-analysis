📺 Netflix Data Analysis

This project analyzes the Netflix Titles Dataset (from Kaggle) using Python, Pandas, and Matplotlib.
The goal is to clean the dataset and explore trends in Netflix Movies and TV Shows.

📂 Dataset

Source: Netflix Titles Dataset on Kaggle

Rows: ~8800

Columns used:

type → Movie or TV Show

title → Name of the content

country → Country of origin

release_year → Year of release

rating → Age rating (e.g., TV-MA, PG-13)

duration → Duration in minutes (movies) or number of seasons (shows)

🧹 Data Cleaning

Removed unnecessary columns (like description).

Handled missing values using dropna().

Removed duplicate records.

Cleaned the duration column to convert strings (e.g., "90 min") into numbers.

📊 Analysis & Visualizations

Movies vs TV Shows → Bar chart comparing counts.

Ratings Distribution → Pie chart of content ratings.

Duration of Movies → Histogram showing movie lengths.

Release Year vs Number of Shows → Scatter plot to visualize trends.

Top 10 Countries → Bar chart of countries producing most content.

Year-wise Movies and Shows → Line plot comparing releases over time.

🛠️ Tools Used

Python

Pandas → data cleaning and grouping

Matplotlib → charts and visualizations

🚀 Key Insights

Netflix has more Movies than TV Shows.

The most common ratings are TV-MA and TV-14.

Most movies are between 80–120 minutes long.

Number of TV Shows has grown significantly after 2015.

USA and India are the top content producers.
