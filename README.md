Movie Studio EDA ANALYSIS
Project Overview

This project analyzes global film performance to guide the strategic launch of a new movie studio. The goal is to identify which types of films deliver the highest return on investment (ROI), revenue, and audience satisfaction, and to translate these insights into actionable business recommendations.

Business Problem

A company plans to establish a new movie studio but lacks industry knowledge. This project addresses that gap by analyzing historical film data to determine:

* Which genres perform best financially

* How production budgets impact returns

* impact of ratings and reviews

* The best release periods to maximize revenue

### Objectives
1. Return on Investment (ROI)

Identify genres that generate the highest returns relative to production cost

Evaluate the relationship between budget and revenue

2. Revenue by Genre

Determine which genres generate the highest box office revenue

Analyze audience preferences using popularity and engagement metrics

3. Reviews and Ratings

Assess how IMDb ratings influence financial success

Identify genres with strong audience approval

4. Seasonality

Identify the best time of year to release films

Analyze revenue trends across seasons

## Methodology

Data Integration: Combined datasets from multiple sources

Data Cleaning: Standardized formats, handled missing values, merged datasets

Exploratory Analysis: Examined relationships between variables

Comparative Analysis: Evaluated performance across genres, budgets, and ratings

Scoring Model: Ranked genres based on ROI, revenue, and ratings

## Datasets Used

Box Office Mojo: Domestic and international revenue

IMDb: Ratings, genres, runtime, votes

Rotten Tomatoes: Critic and audience scores

TheMovieDB: Popularity and engagement metrics

The Numbers: Production budgets and worldwide gross

## Data Preparation

Key steps included:

* Cleaning and standardizing column names

* Converting financial data to numeric formats

* Handling missing values

* Merging datasets using movie titles

* Feature engineering (e.g., total revenue, ROI, season)

## Key Analyses
1. Ratings vs Revenue

Scatter plots used to evaluate correlation between ratings and revenue

Finding: Higher ratings tend to support stronger revenue performance

2. Top Genres by Revenue

Genres split and analyzed individually

Finding:

* Animation

* Sci-Fi

* Adventure
generate the highest average revenue

3. Seasonality Analysis

Movies grouped by release season

Finding:

Summer releases generate the highest average revenue

4. ROI Analysis

ROI calculated using:

ROI = (worldwide_gross - production_budget) / production_budget

## Finding & Recommendation:

Some lower-budget genres yield higher ROI

High budget ≠ high profitability

## Genre Ranking Model

A scoring function was developed to rank genres based on:

* ROI

* Revenue

* Ratings

Each metric was normalized and combined into a final score.
