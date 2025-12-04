🎬 Bollywood Movies Dashboard — README
📌 Overview

This Power BI dashboard provides an analytical overview of Bollywood movies, showcasing budget, revenue, release periods, lead actors, music directors, and screen distribution.
The goal is to highlight box office performance, industry trends, and movie-wise comparisons through interactive visuals.

🔗 Data Sources
1) Local Excel File

Source: bollywood_movies.xlsx

Connection Type: Import

Columns Used:

Movie_Name

Budget

Revenue

Release_Period (Normal/Holiday)

Lead_Star

Music_Director

Number_of_Screens

Notes

Data cleaned in Power Query

Null/missing values handled

Data types corrected (Text/Number)

🧩 Data Model Details

Fact Columns: Budget, Revenue, Number_of_Screens

Dimensions: Movie_Name, Lead_Star, Music_Director, Release_Period

Transformations:

Duplicates removed

Budget & Revenue converted to numeric values

Categorized release periods (Holiday/Normal)

📏 Measures Used
Total Budget = SUM(Budget)
Total Revenue = SUM(Revenue)
Movie Count = COUNT(Movie_Name)
Sum of Screens = SUM(Number_of_Screens)

📊 Visuals Included
1) Total Budget (Card)

Shows total industry budget represented in billions.

2) Total Revenue (Card)

Displays total revenue generated from all listed movies.

3) Movies Count by Release Period (Donut Chart)

Compares movies released on Holiday vs Normal days.

4) Revenue (INR) by Movie Name (Pie Chart)

Highlights revenue contribution of each movie.

5) Movie Count by Lead Star (Bar Chart)

Shows how many movies each actor has led.

6) Total Number of Screens by Movie Name (Column Chart)

Compares theatre screen count for each film.

7) Movie Count by Music Director (Donut Chart)

Analyzes how many movies each music director has worked on.

🌱 Key Insights

Total Industry Budget: 404bn

Total Revenue: 255bn

Majority movies released on normal periods

Akshay Kumar leads with the highest movie count

Music directors like Pritam and Himesh dominate the dataset

Show what the dashboard looks like.---  ![Dashboard Preview](https://github.com/Sonu6290/Bollywood-Movies-DataSets/blob/main/Bollywood%20Movies%20Datasets.png)

