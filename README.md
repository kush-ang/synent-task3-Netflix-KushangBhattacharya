Netflix Global Insights & Trends Analysis
Internship Project | Task 3

Project Overview
This project is an end-to-end data analysis of Netflix's content library. The goal was to visualize global trends, growth patterns, and audience distribution from 1925 to 2020. This task was completed during my Data Analytics internship at [Company Name].

Technical Workflow
1. Data Cleaning (Python)
Since the raw data was messy, I used Python (Pandas) to prepare it for analysis:

Fixed the Rating column where movie durations (min) were incorrectly stored.

Handled missing values in the Country and Cast columns.

Formatted dates to extract the "Year Added" for trend analysis.

2. Data Modeling (Power BI & DAX)
To make the dashboard insightful, I used DAX to create a master "Target Audience" column:

Adults (18+): TV-MA, R, NC-17

Teens (14+): TV-14, PG-13

Kids & Family: TV-PG, PG, G, TV-Y, TV-Y7

Unrated: UR, NR

Key Insights
Content Split: 69% Movies and 31% TV Shows.

Growth Peak: 2019 saw the highest number of content additions on the platform.

Top Countries: USA leads the global library, with India at the 2nd position. Japan and South Korea also feature in the top 10.

Popular Genres: Documentaries and Stand-up Comedy are the top-performing categories.

Audience: The majority of Netflix content is targeted toward the Adult (18+) segment.

How to use this Repository
Python Script: Check the .ipynb file to see the cleaning process.

Dashboard: Download the .pbix file to view the interactive report in Power BI Desktop.
