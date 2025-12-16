# tmdb-movie-analysis
A complete movie data analysis pipeline using TMDB API, Pandas, and Python.  Analyzes box office performance, ROI, and franchise success with visualizations.

##  Overview

This project demonstrates a complete data analysis workflow, from API data extraction to insights generation. Using The Movie Database (TMDB) API, I analyzed 18 movies to understand what drives box office success. The main question here was what makes movies financially successful?There had been found that Franchise movies generate 2.3x more revenue and significantly higher ROI compared to standalone films.

## Working flow

### 1. Data Collection
The first thing to do was API data fetching from TMDB which retrieves movie details, cast, crew, and financial data. From this step we've been able to handle rate limiting and error management.

### 2. Data Cleaning & Processing
Secondly, the biggest part was to extracts nested JSON data (genres, collections, cast) that handles missing values and data type conversions, converts financial data to millions USD, and removes incomplete records.

### 3. Analysis & KPIs
There are also some calculations we made such as Profit and ROI (Return on Investment). We have ranked top 10 generated different movie, compared franchise vs standalone performance, analyzed director and genre success rates, and also customised movie searches (by actor, director, genre).

### 4. Visualization
Our project also included the graphical presentation of some of our results, which are the following: 7 professional charts and graphs, Revenue vs Budget scatter plots, ROI analysis by genre, Yearly box office trends, and Franchise performance comparisons.

---

