# Netflix Titles Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis on a Netflix dataset containing TV shows and movies available on the platform. The goal is to uncover patterns and insights from the content catalogue such as types of shows, distribution by country, release year, and more.

## 📁 File Structure

- `Netflix_Titles_EDA.ipynb` - Main Jupyter notebook with full analysis
- `netflix_titles.csv` - Dataset used for the analysis

## 📂 Dataset

- Source: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- File: `netflix_titles.csv`
- Rows: 8,800+ titles
- Columns: title, director, cast, country, release year, rating, duration, description, etc.

## 🧰 Tools and Libraries

- Python
- pandas
- matplotlib
- seaborn
- WordCloud

## 📊 Analysis Overview

### 1. Data Cleaning
- Handling missing values
- Ensuring consistent data types
- Converting `date_added` to datetime
- Checking consistency in columns like `duration` and `country`

### 2. Univariate Analysis
- Distribution by type (Movies vs TV Shows)
- Most frequent directors
- Most common categories
- Top countries producing content
- Distribution of content ratings
- Release year trends

### 3. Bivariate Analysis
- Trends of movies and TV shows over time

### 4. Word Cloud
- Visual representation of most frequent terms in the content descriptions

## 📌 Key Insights

- Netflix has a higher proportion of movies than TV shows.
- Most content comes from the United States and India.
- The most common rating is “TV-MA”.
- The volume of content added peaked in 2019.
- The number of releases has decreased since 2020, likely due to the onset of the COVID-19 pandemic.

## 🧠 Conclusions

This EDA provides a general overview of Netflix’s catalogue and its evolution over the years. The analysis can be extended further by incorporating user ratings, genre classification, or combining with IMDb datasets.

## ✅ How to Run

Clone this repo and open the notebook in Jupyter or Google Colab:

```bash
git clone https://github.com/yourusername/netflix-eda.git
cd netflix-eda
