# Movies Mini Project

This repository contains a data analysis project that explores movie data from the Internet Movie Database (IMDB). The aim of the project is to identify factors affecting a movie's ranking and analyze trends in the dataset.

---

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Visualizations](#visualizations)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results](#results)
- [Contributing](#contributing)

---

## Introduction

Movies vary significantly in popularity, and highly ranked films often generate higher revenue and audience engagement. This project aims to:
1. Investigate trends in movie rankings over time.
2. Analyze the impact of genre and other factors on rankings.
3. Create visualizations to better understand the dataset.

By analyzing the provided IMDB data, we can predict which movies might be successful and identify common patterns among high-ranking films.

---

## Dataset

The dataset used for this analysis contains movie information including:
- **Title**: Name of the movie.
- **Genre**: Genre(s) of the movie.
- **Year**: Year the movie was released.
- **Rank**: IMDB ranking of the movie.
- **Director**: First and last names of the movie's director.

### Source:
- The dataset is from the Internet Movie Database (IMDB) and was preprocessed in a separate notebook.
- A cleaned version of the data (`cleaned_movies.csv`) is included in this repository.

---

## Project Workflow

1. **Define the Problem**: Identify trends and relationships affecting movie rankings.
2. **Data Collection**: Import and explore the dataset using Python libraries like `pandas` and `matplotlib`.
3. **Data Cleaning**: Handle missing values and prepare the dataset for analysis.
4. **Feature Engineering**: Combine the director's first and last name into a single column.
5. **Visualizations**:
   - Distribution of movie ranks (Histogram).
   - Frequency of movie genres (Bar chart).
   - Trend of average movie rank over time (Line plot).

---

## Visualizations

### Key Insights:
1. **Rank Distribution**: Most movies have ranks clustered around 5-7 on the IMDB scale.
2. **Genre Frequency**: A bar chart highlights the most common genres, focusing on the top 10.
3. **Rank Over Time**: Average movie rank has varied across different release years, visualized using a line chart.

Screenshots of the graphs and additional analyses are included in the repository.

---

## Technologies Used

- **Python**: Data analysis and visualization.
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` for data visualization.
- **Google Colab**: Environment for running Python code.
- **GitHub**: Version control and repository hosting.

---

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Shaziyehtajik/data-and-python.git
   cd movies-mini-project
