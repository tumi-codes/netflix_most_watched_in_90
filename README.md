 📊 Netflix 1990s Movie Analysis

📌 Overview

This project analyzes a dataset of Netflix titles to explore trends in movie durations during the 1990s. The goal is to understand how long movies were during this decade and specifically investigate the prevalence of short action movies.

🎯 Objectives

* Filter Netflix data to focus only on movies released in the 1990s
* Visualize the distribution of movie durations
* Identify how many action movies were considered “short” (less than 90 minutes)


🗂️ Dataset

The dataset used in this project is a CSV file named:
'netflix_data.csv'

It contains information about Netflix titles, including:

* Title
* Type (Movie/TV Show)
* Genre
* Duration
* Release Year

> Note: This dataset is adapted from a publicly available Netflix dataset commonly used for data analysis projects.

⚙️ Technologies Used

* Python
* Pandas
* Matplotlib

🔍 Project Workflow

1. Data Loading

The dataset is loaded into a Pandas DataFrame for analysis.

2. Data Filtering

The data is filtered to:

* Include only **movies**
* Include only movies released between **1990 and 1999**

3. Data Visualization

A histogram is created to visualize the distribution of movie durations in the 1990s.

4. Analysis of Action Movies

* The dataset is filtered further to include only **Action** movies
* A loop is used to count how many of these movies have a duration of less than 90 minutes

📈 Key Insight

The project determines the number of short action movies released in the 1990s, providing insight into trends in movie length within that genre.

📬 Contact

If you have any suggestions or feedback, feel free to reach out or open an issue in the repository.
