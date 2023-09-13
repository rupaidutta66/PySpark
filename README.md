# Bundesliga Analysis with PySpark
This repository contains PySpark code to analyze Bundesliga football data, specifically focusing on the last decade (2013-2023). The analysis aims to answer several questions related to team performance, relegation, and more.

## Table of Contents
Prerequisites
Getting Started
Usage
Questions Answered

# Prerequisites
Before running the code, ensure you have the following installed:

Python
PySpark
Jupyter Notebook or Google Colab (for running PySpark in a notebook environment)
You also need the following datasets in CSV format:

match.csv: Contains match data, including team names, division, and match results.
Teams_in_matches.csv: Maps match IDs to unique team IDs.
teams.csv: Provides additional information about teams, including season, stadium capacity, etc.
unique_teams.csv: Maps unique team IDs to team names.

# Getting Started
1. Clone this repository to your local machine:

git clone <repository_url>
cd bundesliga-analysis-pyspark

2. Place the CSV dataset files (match.csv, Teams_in_matches.csv, teams.csv, unique_teams.csv) in the same directory as the code.

3. Open the code in your preferred Python environment (e.g., Jupyter Notebook or Google Colab).

4. Run the code by executing each cell. Ensure the necessary libraries and functions are imported.

# Usage
The provided PySpark code is organized into sections to answer specific questions related to Bundesliga football. Each section begins with a question and includes code to perform the analysis and provide answers.

# Questions Answered
Here are the questions answered by this analysis:

1. Who are the winners of the D1 division in the Germany Football Association (Bundesliga) in the last decade?
2. Which teams have been relegated in the past 10 years?
3. Does Octoberfest affect the performance of Bundesliga?
4. Which season of Bundesliga was the most competitive in the last decade?
5. What's the best month to watch Bundesliga?

Each question is addressed within the code, and the results are displayed.

Feel free to customize this README file further based on your specific needs and add any additional information or sections that you find relevant.
