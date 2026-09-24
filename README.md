# Video Game Sales Analysis

## Project overview

Ice is an online store that sells video games worldwide. In this project, I analyze historical game sales, platforms, genres, review scores, and ESRB ratings to identify patterns that could help plan advertising campaigns for 2017.

The analysis is framed as if it were December 2016. Sales data for 2016 may be incomplete, so recent trends need to be interpreted with that limitation in mind.

## Dataset

The dataset contains game titles, release years, platforms, genres, critic and user scores, ESRB ratings, and sales across North America, Europe, Japan, and other regions. Sales figures are reported in millions of USD.

[Download the dataset](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/games.csv)

## Analysis

The Jupyter Notebook covers:

* **Data preparation:** Standardizing column names, reviewing data types and missing values, handling `"tbd"` user scores, and calculating total sales for each game.
* **Sales trends:** Examining releases by year, platform lifecycles, recent platform sales, and differences in sales distributions.
* **Reviews and genres:** Exploring the relationship between review scores and sales, comparing games across platforms, and identifying sales patterns by genre.
* **Regional markets:** Comparing leading platforms, genres, and ESRB ratings in North America, Europe, and Japan.
* **Hypothesis testing:** Testing whether average user scores differ between Xbox One and PC, and between Action and Sports games.

## Tools and skills

Python, pandas, data visualization, exploratory data analysis, data cleaning, and statistical hypothesis testing.

## Business question

Which patterns in the available data can help Ice identify promising games and plan its 2017 advertising campaigns?

