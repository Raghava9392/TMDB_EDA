# data_analysis_project
Movie Data Analysis Project using Python – Includes EDA, visualizations, genre extraction, statistical analysis, and insights using TMDB dataset.

Here is a clean and professional **README.md** for your GitHub repository based on your TMDB movie dataset project.

---

# 📊 TMDB Movie Data Analysis Project

This project performs **Exploratory Data Analysis (EDA)** on a curated TMDB movie dataset.
The main goal is to extract insights about **movie popularity, ratings, genres, languages, and trends over time**.

---

## Dataset

The dataset used in this project is included in this repository:

**File:** `tmdb_finale___.csv`
It contains the following key columns:

| Column Name           | Description                        |
| --------------------- | ---------------------------------- |
| `title`               | Movie title                        |
| `original_title`      | Original language title            |
| `overview`            | Short description                  |
| `overview_word_count` | Word count of overview             |
| `release_date`        | Movie release date                 |
| `release_year`        | Extracted year                     |
| `original_language`   | Language code (en, hi, fr…)        |
| `genres`              | List of genres                     |
| `vote_average`        | Movie rating (0–10)                |
| `vote_count`          | No. of people who rated            |
| `popularity`          | Popularity score                   | 


## Project Objectives

* Perform complete **EDA**
* Identify **genre-wise popularity**
* Analyze **language distribution**
* Study **rating vs popularity**
* Explore **release year patterns**
* Visualize key insights with graphs


## Data Cleaning

Cleaning performed in the notebook:

* Dropped Unwanted columns. 
* Converted `release_date` to datetime
* Extracted `release_year`
* Cleaned `genres` list
* Handled missing values
* Added `overview_word_count`


## Visualizations Included

This project includes **Univariate, Bivariate, and Multivariate** graphs:

### Univariate Analysis

* Histogram (ratings, vote_count, popularity)
* Bar chart (genres, languages)
* Countplot (release years)

### Bivariate Analysis

* Scatter plot (Rating vs Popularity)
* Boxplot (Genre vs Rating)


### Multivariate Analysis

* Heatmap (correlation)

---

## 🧠 Key Insights

Some major insights observed:

* **Drama** movies are the most frequent.
* **Action and Sci-fi** movies are the most *popular*.
* **Ratings and popularity are independent** — high rating ≠ high popularity.
* English (`en`) dominates the dataset, followed by Hindi and Spanish.
* Movie production increased heavily after **2010**.

---

## Project Structure

```
data_analysis_project
│── tmdb_finale___.csv
│── tmdb_data_analysis.ipynb
│── README.md
```

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

👨‍💻 Author

POTHULA RAGHAVENDRA REDDY
Email:pothularaghava90@gmail.com
