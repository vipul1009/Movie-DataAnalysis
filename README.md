# Movie Data Analysis Project

## Overview
This project analyzes a dataset of over **9,000 movies** to gain insights into **movie trends, popularity, and audience preferences**. The dataset includes details like movie titles, release years, genres, popularity scores, and vote counts. The analysis is performed using **Python**, with data preprocessing, cleaning, and visualization to extract meaningful insights.

## Features
- **Data Cleaning & Preprocessing**
  - Converted `Release_Date` to year format
  - Removed unnecessary columns (`Overview`, `Original_Language`, `Poster_Url`)
  - Checked for and removed duplicate entries
  - Categorized `Vote_Average` into 4 categories
  - Split `Genre` column for better analysis
- **Exploratory Data Analysis (EDA)**
  - Identified the most frequent movie genres
  - Found movies with highest and lowest popularity
  - Analyzed trends in movie releases over the years
  - Categorized movies based on popularity
- **Data Visualization**
  - Bar charts for genre frequency
  - Histograms for release year distribution
  - Scatter plots for popularity trends

## Dataset
The dataset used (`mymoviedb.csv`) contains the following columns:
- `Release_Date`: Year of release
- `Title`: Movie name
- `Overview`: Movie description (removed in analysis)
- `Popularity`: Popularity score
- `Vote_Count`: Number of votes
- `Vote_Average`: Average user rating
- `Original_Language`: Language (removed in analysis)
- `Genre`: Movie genres (split into multiple rows per movie)
- `Poster_Url`: Image link (removed in analysis)

## Technologies Used
- **Python** (Data Analysis & Visualization)
- **Pandas** (Data Preprocessing)
- **NumPy** (Mathematical Operations)
- **Matplotlib & Seaborn** (Data Visualization)
- **Jupyter Notebook / Google Colab** (Execution Environment)


## Project Structure
```
movie-data-analysis/
│-- data/
│   ├── mymoviedb.csv  # Movie dataset
│-- notebooks/
│   ├── movie_analysis.ipynb  # Jupyter Notebook with code
│-- README.md  # Project documentation
│-- requirements.txt  # Python dependencies
```

## Key Insights
### Q1: What is the most frequent movie genre?
- **Drama** is the most frequent genre, appearing in **14%** of all movies.

### Q2: Which genre has the highest votes?
- Drama has the highest number of popular movies (**25.5%** of dataset).

### Q3: What movie has the highest popularity?
- **"Spider-Man: No Way Home"** (Popularity Score: **5083.954**)
  - Genres: **Action, Adventure, Science Fiction**

### Q4: What movie has the lowest popularity?
- **"The United States vs. Billie Holiday" & "Threads"** (Popularity Score: **13.354**)
  - Genres: **Music, Drama, History, War, Sci-Fi**

### Q5: Which year had the most movie releases?
- **2020** had the highest number of movie releases.

## Visualizations
1. **Genre Distribution:** Bar chart showing the most frequent movie genres.
2. **Vote Distribution:** Histogram showing rating categories.
3. **Popularity Trends:** Scatter plots showing the most and least popular movies.
4. **Yearly Releases:** Histogram highlighting movie production trends over the years.


