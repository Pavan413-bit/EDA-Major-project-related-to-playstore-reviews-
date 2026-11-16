# Google Play Store Apps & Reviews – Exploratory Data Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Google Play Store Apps and User Reviews datasets obtained from Kaggle.

The main objective is to analyse app ratings, categories, prices, installations, reviews and user sentiment to understand patterns and relationships within the Google Play Store.

The project uses Python libraries such as Pandas and NumPy to clean, organise and analyse the datasets.

## Dataset

**Source:** [Google Play Store Apps and Reviews – Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

The project uses two CSV files:

1. `googleplaystore.csv` – Contains app names, categories, ratings, reviews, size, installs, prices and update dates.
2. `googleplaystore_user_reviews.csv` – Contains user reviews, sentiment, sentiment polarity and subjectivity.

## Objectives

- Understand the structure of the datasets.
- Identify and handle missing values and duplicate records.
- Clean and prepare data for analysis.
- Create new features such as Price Type, Install Level and Rating Level.
- Analyse apps based on categories and ratings.
- Combine app information with user review data.
- Calculate descriptive statistics.
- Study distributions and correlations between numerical variables.
- Identify important findings from the analysis.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy

## Project Structure

```text
Google-Play-Store-EDA/
│
├── EDA_Google_Play_Simplified.ipynb
├── googleplaystore.csv
├── googleplaystore_user_reviews.csv
└── README.md
```

## How to Run the Project

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy jupyter
```

4. Place both CSV datasets in the project folder.
5. Open Jupyter Notebook.
6. Run `EDA_Google_Play_Simplified.ipynb` cell by cell.

## Key Analysis Performed

- Data loading and exploration
- Data cleaning and preprocessing
- Feature engineering
- Grouping and aggregation
- Pivot tables and cross-tabulation
- Data reshaping and integration
- Descriptive statistics
- Distribution analysis
- Empirical rule and Central Limit Theorem
- Correlation analysis
- Findings and observations

## Conclusion

This project provides an understanding of Google Play Store applications and their user reviews through Exploratory Data Analysis.

The analysis helps identify patterns in app ratings, popularity, pricing and user sentiment. It also demonstrates how Python and Pandas can be used to clean, organise and analyse real-world datasets.

## Project Type

Academic Minor Project – Exploratory Data Analysis (EDA)

**Course:** CSB314
