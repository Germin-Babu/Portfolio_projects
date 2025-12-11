🎬 Movies Dataset – Exploratory Data Analysis Using Python                                                                                                 

📊 A complete exploratory analysis project showcasing data cleaning, visualization, and correlation insights on a Kaggle movies dataset.

📌 Project Overview

This project performs an extensive Exploratory Data Analysis (EDA) on a Kaggle movie dataset to uncover trends in movie production, revenue generation, director performance, genres, and factors influencing box-office success.

The analysis includes:

✔ Data cleaning and preprocessing

✔ Identifying missing and duplicate values

✔ Extracting and correcting year data

✔ Sorting and filtering movies based on revenue

✔ Analyzing top-performing countries, directors, and companies

✔ Exploring genre-level revenue trends

✔ Correlation analysis between numerical features

✔ Regression visualizations (budget vs gross, votes vs gross)

This project demonstrates skills in Pandas, NumPy, Seaborn, Matplotlib, and Python-based storytelling with data.


## 📂 Project Structure

```
movie-eda-project/
│
├── notebooks/
│   └── movie_eda.ipynb
│
├── images/
│   └── (your charts here)
│
└── README.md
```



## 🗂️ Dataset Information

Source: Kaggle
Original dataset is not included due to licensing restrictions

Contains the following key variables:

Movie name,
Release year,
Corrected year (extracted from release column),
Budget & Gross revenue,
Company,
Director,
Genre,
Country,
Score,
Votes,


## 🧹 Data Cleaning & Preprocessing

✔ Checked column info and data types

   Using df.info()

✔ Identified and dropped missing values

✔ Removed duplicate rows

✔ Converted budget & gross to integers

✔ Extracted year from the "released" column

✔ Sorted dataset by gross revenue (descending)

## 📊 Exploratory Data Analysis

1️⃣ Top Movie-Producing Countries

Horizontal bar chart of top 10 countries by number of movies produced.

2️⃣ Top 10 Movies by Score

Scatter plot showing highest-rated movies.

3️⃣ Companies with Highest Total Gross Earnings

Bar chart ranking studios by cumulative gross revenue.

4️⃣ Average Gross Revenue per Company

Identifies top-performing production houses by mean revenue.

5️⃣ Top Directors by Number of Movies

Bar chart of the most active directors in the dataset.

6️⃣ Average Gross Revenue per Director

Plot showing which directors generate the highest returns.

7️⃣ Genre Revenue Analysis

Genres ranked by total gross earnings, visualized with a bar plot.

## 🔍 Correlation Analysis

✔ Numeric correlation heatmap

Shows strong positive correlation between:

Budget ↔ Gross revenue (0.74)

Votes ↔ Gross revenue (0.61)

✔ Converted categorical features into numeric codes

Allows full correlation analysis.

✔ Generated correlation pairs

Identifying strongest relationships.

✔ Scatterplots + Regression Lines

Budget vs Gross Earnings

Votes vs Gross Earnings

These reveal strong linear relationships, indicating that higher budgets and more votes are strongly associated with higher box office performance.

## ⭐ Key Insights

Based on your real analysis:

🎯 1. Higher budgets strongly lead to higher gross earnings.

Correlation: 0.74

🎯 2. The number of votes is a strong indicator of box-office success.

Correlation: 0.61

🎯 3. Some directors consistently generate high gross revenue, both in total and on average.

🎯 4. Production companies differ significantly in gross performance, with the top 10 dominating the industry.

🎯 5. Genre plays a major role — certain genres consistently generate more revenue.

🎯 6. The dataset required substantial cleaning, especially removing missing values and correcting year inconsistencies.

## 🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook
