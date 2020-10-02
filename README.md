# Project Cinema
Data Scientist:
- Ismael Araujo


## Repository and Data

This repository contains data collection, cleaning, and analyses of data sets of movies released from 1990 to 2020.

It was used data sets provided by Flatiron School and data sets downloaded from IMDb

## Structure

Images -- contains images with graphics linked in README
project-cinema.ipynb -- it's the notebook with data wrangling, data cleaning, data analyses, and visualization.
README.md - contains a brief introduction to the project
DataSets - data sets used for the analyses


## Project Overview

In this project, we will analyze the recent cinematographic industry and what factors can influence the success of a movie and/or movie studios. We will walk through the most profitable films and genres and identify patterns. The main objective is to identify trends and correlations to create recommendations to companies interested in entering the movie industry.

## Objectives

### Answer the fallowing questions:

1. Is there any connection between the top 20 most profitable movies of all time?
2. Do higher budgets reflect in higher profits?
3. What are the top 10 genres with the most movies launched since 1990?
4. What groups of genres bring the highest box office revenue and ROI?
5. What genres bring the highest box office revenue and ROI?



## Approach
1. Understand the business problem
- What is considered "currently" in the industry?
Understand the market
- How do movie studios make money?
- How much percent to the get out of the revenue?
Understand what aspects can help a movie to become profitable?
- What type of movies makes the most money?
- What genres have the best and worst returns per dollar invested?
- Are there any patterns in successful movies?

## Conclusions and Recommendations

### Out of the top 20 most profitable movies:
- 18 of them are part of a franchise of movies
- 13 of them are continuations of previous movies
- 5 of them are the first movie of a franchise
- 2 of them haven't had a continuation yet, but they are underway
- Only Beauty and the Beast and Titanic aren't part of a franchise yet.

Correlation between the data: 
Higher budget and higher box office are positively correlated. However, it is not guaranteed that a higher budget will bring higher revenue. It will depend on the quality and reception of the final product.

![correlation](https://github.com/Ismaeltrevi/project-cinema/blob/master/Images/regcorr.png)
=======

Budget and box office have a strong positive correlation 
Duration and average vote have a moderate correlation 
Budget and duration have a moderate correlation.

![correlation](https://github.com/Ismaeltrevi/project-cinema/blob/master/Images/budget_vs_box_office.png)

The genres with more movies launched between 1990 and 2020 are:
Drama, Comedy, Horror, Thriller, Action, Biography, Adventure, Romance, and Crime.


![profitable_movies](https://github.com/Ismaeltrevi/project-cinema/blob/master/Images/most_profitable_movies.png)


The individual genres that bring the highest in box office revenue are:
- Animation  -   121.788071 million dollars
- Adventure  -   104.248915 million dollars
- Sci-Fi    -    68.416803 million dollars
- Action    -    53.555004 million dollars
- Fantasy   -    49.365756 million dollars

![profitable_movies](https://github.com/Ismaeltrevi/project-cinema/blob/master/Images/least_profitable_genres.png)

## Recommendations:
- Invest in franchises, such as Halo and Gears.
- Invest in movies that grab all the public.
- Drama and Comedy might face higher competition since they are in larger quantities.
- Animation, Adventure, and Sci-Fi bring the highest profits. It is a good idea to invest on them.
