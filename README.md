# Netflix Content Strategy — In-Depth Exploratory Data Analysis

## 📌 Overview

This repository contains an in-depth Exploratory Data Analysis (EDA) focused on understanding **Netflix’s content strategy** using the Netflix Movies & TV Shows dataset.

The analysis aims to explore trends across years, content types, geographic production, ratings, genres, and insights that could help inform strategic decisions about content growth and audience reach. :contentReference[oaicite:0]{index=0}

---

## 🧠 Objective

The primary goals of this project are:

- To perform thorough data cleaning and structuring of the Netflix dataset.
- To explore content distributions across different features such as:
  - Genre
  - Type (Movie vs TV Show)
  - Rating
  - Country of origin
  - Release year and addition year
- To derive insights into how Netflix’s content library has evolved over time.
- To visualise patterns that reflect Netflix’s content strategy and production trends. :contentReference[oaicite:1]{index=1}

---

## 📊 Dataset

The analysis uses the popular **Netflix Movies and TV Shows dataset**, commonly sourced from Kaggle and other open data repositories.

### Dataset Description

The dataset includes the following key columns:

| Column           | Description |
|------------------|-------------|
| `show_id`        | Unique ID for each show |
| `type`           | Type of content (Movie or TV Show) |
| `title`          | Title of the show or movie |
| `director`       | Director(s) associated |
| `cast`           | Cast members |
| `country`        | Country or countries of production |
| `date_added`     | Date added to Netflix library |
| `release_year`   | Original year of release |
| `rating`         | Content rating (e.g., TV-MA, PG-13) |
| `duration`       | Duration in minutes or seasons |
| `listed_in`      | Genre(s) categories |
| `description`    | Short description of the title |

This dataset allows for trend analysis over time, comparisons across countries, content type distributions, and genre-based insights. :contentReference[oaicite:2]{index=2}

---

## 🧰 Tools & Libraries

The analysis is performed using:

- Python  
- Jupyter Notebook  
- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  
- Data visualisation for trend and pattern identification

These tools help clean, transform, and visualise the dataset to uncover meaningful stories about Netflix’s content strategy.

---

## 🔍 Key Analyses & Insights

The notebook includes several analytical components, including:

### Data Cleaning & Preprocessing

- Handling missing values
- Formatting `date_added` and extracting relevant temporal features
- Converting lists within cells into usable columns for analysis

### Exploratory Analysis

The analysis explores:

- **Content growth over the years:** how many titles were added each year
- **Distribution of Movies vs TV Shows**
- **Genre prevalence trends**
- **Ratings distribution across countries**
- **Content length comparisons**
- **Country-level content production insights**

Each section contains visualisations and written summaries to explain key takeaways. :contentReference[oaicite:3]{index=3}

---

## 📈 Visualisation Examples

Some examples of visual outputs include:

- Bar charts showing year-wise content growth
- Stacked plots comparing genres across countries
- Heatmaps of genre vs rating distribution
- Pie charts for proportions of content types

Visual storytelling is used wherever possible to link numerical trends with strategic interpretations.

---
📌 Summary

This project presents a comprehensive exploratory analysis of Netflix’s content library with the goal of uncovering strategic insights into how content has evolved over time.

The notebook is structured to allow any user — from beginner to advanced — to follow the data cleaning process, visualise key trends, and understand how EDA reveals Netflix’s content strategy.

   git clone https://github.com/Kirthika-Srinivasan/In-Depth-EDA-Netflix--Content-Analysis.git
