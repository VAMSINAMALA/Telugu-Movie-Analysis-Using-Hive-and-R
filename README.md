📊 Telugu Movie Data Analysis using Hive and R
📌 Project Overview

This project focuses on analyzing Telugu movie data using Big Data technologies like Hive and R for visualization. The goal is to extract meaningful insights about movie trends, audience preferences, and factors influencing movie success.

🎯 Objectives
Analyze Telugu movie dataset to identify trends
Understand audience preferences based on ratings
Study genre popularity and runtime patterns
Perform big data querying using Hive
Visualize insights using R and Python
📂 Dataset Details
Total Records: 1400 movies
Attributes:
Movie Name
Year
Certificate
Genre
Overview
Runtime
Rating
Movie Ratings Count
⚙️ Technologies Used
Python (Pandas, NumPy) → Data preprocessing
Hive (HDFS) → Querying large datasets
R Programming → Data visualization
Google Colab → Development environment
Hortonworks Sandbox → Hive setup
🧹 Data Preprocessing
Handled missing values:
Year → Replaced with median
Certificate & Genre → "Unknown"
Overview → "No overview available"
Removed duplicates
Standardized data formats
Cleaned string values
🔍 Key Analysis Performed
📅 Year-wise Analysis
Count of movies released each year
Trend of movie production over time
⭐ Rating Analysis
Top 10 highest-rated movies
Movies with low ratings (<5)
Average rating per year
🎭 Genre Analysis
Most popular genres (Action, Romance, etc.)
Count of movies per genre
⏱ Runtime Analysis
Movies longer than 150 minutes
Runtime distribution trends
🔎 Content Analysis
Keyword-based search (e.g., "love" movies)
🛠 Sample Hive Queries
-- Movies released in 2020
SELECT movie, year FROM telugu_movies WHERE year = 2020;

-- Top 10 highest-rated movies
SELECT movie, rating FROM telugu_movies ORDER BY rating DESC LIMIT 10;

-- Count movies by genre
SELECT genre, COUNT(*) FROM telugu_movies GROUP BY genre;
📊 Visualizations
Rating distribution (Histogram)
Movies released per year (Line chart)
Top genres (Bar chart)
Runtime distribution (Box plot)
Rating vs Runtime (Scatter plot)
Certificate-wise movie count
📈 Key Insights
Action and Romance are the most popular genres
Majority of movies fall in mid-range ratings (4–7)
Some movies have very long runtimes (>150 mins)
Audience engagement is higher for blockbuster movies
Missing rating data is significant (data quality issue)
🏁 Conclusion

This project demonstrates how Big Data tools like Hive combined with data visualization techniques can uncover valuable insights in the entertainment industry. It helps understand:

Audience preferences
Movie success factors
Industry trends
📚 Future Scope
Build a movie recommendation system
Predict movie success using ML models
Include box office data for deeper analysis
👨‍💻 Contributors
N. Vamsi
Team Members

If you want, I can also:
✅ Make this into a PDF report
✅ Add GitHub badges & professional formatting
✅ Customize it for job/interview use (very important for you)

proper cp version

Got it 👍 — here is a clean COPY-PASTE READY README (proper formatting for GitHub):

📊 Telugu Movie Data Analysis using Hive and R
📌 Project Overview

This project analyzes Telugu movie data using Big Data technologies like Hive and visualization tools like R. It focuses on extracting meaningful insights such as trends, audience preferences, genre popularity, and factors affecting movie success.

🎯 Objectives
Analyze Telugu movie dataset using Hive queries
Identify trends in movie production over the years
Understand audience preferences using ratings
Explore genre distribution and popularity
Visualize insights using R and Python
📂 Dataset Information
Total Records: 1400
Attributes:
Movie Name
Year
Certificate
Genre
Overview
Runtime
Rating
Movie Ratings Count
⚙️ Technologies Used
Python (Pandas, NumPy) – Data Preprocessing
Hive (HDFS) – Big Data Query Processing
R Programming – Visualization
Google Colab – Development
Hortonworks Sandbox – Hive Environment
🧹 Data Preprocessing
Handled missing values:
Year → Filled with median
Certificate & Genre → "Unknown"
Overview → "No overview available"
Removed duplicates
Standardized data types
Cleaned text fields
🔍 Analysis Performed
📅 Year-wise Analysis
Number of movies released each year
Trends in movie production
⭐ Rating Analysis
Top 10 highest-rated movies
Movies with rating less than 5
Average rating per year
🎭 Genre Analysis
Most common genres
Count of movies per genre
⏱ Runtime Analysis
Movies with runtime > 150 minutes
Runtime distribution
🔎 Content Analysis
Movies containing keywords like "love"
