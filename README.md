# Steam Top 100 Games — Data Analysis

This project explores the Steam Top 100 Games dataset and applies data cleaning, preprocessing, encoding, and exploratory data analysis (EDA) to uncover insights about player counts, reviews, and release trends.

## Project Overview

The main idea of this project is to practice data wrangling and exploratory analysis using Python libraries.
We focused on:

Cleaning and preparing the dataset (handling missing values, encoding categories, converting dates).

Performing One-Hot Encoding and Categorical Encoding for review summaries.

Creating new features such as Release Year.

Visualizing trends in players, reviews, and release years.

## Dataset

The dataset steam_top_100.csv contains information about the top 100 games on Steam.

Key columns:

Steam id → Unique identifier

Game → Title of the game

Current players → Number of current active players

Peak players today → Maximum players in the current day

Release date → Original release date of the game

Release Year → Extracted from Release date

Review summary → Player review category (e.g., Very Positive, Mixed)

Review summary encoded → Numerical encoding of reviews

Total reviews → Number of player reviews

Tags → Genre and descriptive tags

## Data Preprocessing

Review Summary Encoding
Converted review categories into ordered numerical values:

Overwhelmingly Positive → 3

Very Positive → 2

Mostly Positive → 1

Mixed → 0

Release Date

Converted to datetime format.

Extracted Release Year for time-series insights.

Total Reviews

Replaced missing values with the median.

Converted to integer datatype. 

## Goals

1- Data Cleaning & Preparation

Handle missing values in reviews and total reviews.

Convert Release date to datetime and extract Release Year.

Encode categorical variables such as Review summary.

2- Exploratory Data Analysis (EDA)

Identify top games by current players, peak players, and total reviews.

Analyze review distributions (Very Positive, Mixed, etc.).

Visualize release trends by year.

Explore patterns in player counts using descriptive statistics and boxplots.

3- Practical Learning

Strengthen skills in pandas, seaborn, matplotlib, and preprocessing with scikit-learn.

Practice feature engineering for categorical and datetime variables.

Build clear, interpretable visualizations of gaming trends.
