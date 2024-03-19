# Netflix Dataset Analysis

## Overview
This repository contains Python code for analyzing and visualizing the Netflix dataset. The dataset includes information about movies and TV shows available on the Netflix platform, such as titles, directors, cast, countries, release years, ratings, durations, genres, and descriptions.

## Dataset Information
- **Source:** The dataset used in this analysis is obtained from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows).
- **Contents:** The dataset (`netflix_titles.csv`) contains the following columns:
  - `show_id`: Unique identifier for each show/movie.
  - `type`: Type of content (Movie or TV Show).
  - `title`: Title of the show/movie.
  - `director`: Director(s) of the show/movie.
  - `cast`: Cast of the show/movie.
  - `country`: Country/Countries where the show/movie was produced.
  - `date_added`: Date when the show/movie was added to Netflix.
  - `release_year`: Year of release of the show/movie.
  - `rating`: Rating of the show/movie.
  - `duration`: Duration of the show/movie.
  - `listed_in`: Genres/categories of the show/movie.
  - `description`: Brief description of the show/movie.

## Analysis and Visualization
The analysis and visualization code include the following:
- Data loading and initial exploration
- Data cleaning to handle missing values
- Visualization of the distribution of types (Movies vs. TV Shows)
- Visualization of the distribution of ratings
- Exploration of the relationship between types and ratings
- Pie charts for the distribution of types and ratings

## Usage
To run the analysis and visualization code:
1. Ensure you have Python installed on your system.
2. Install the required libraries using pip: `pip install numpy pandas matplotlib seaborn`.
3. Open and run the `netflix_analysis.ipynb` notebook using Jupyter Notebook or JupyterLab.

## Contribution
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.

## Acknowledgments
- This project is created for educational purposes.
- Special thanks to [Kaggle](https://www.kaggle.com/shivamb) for providing the Netflix dataset.

