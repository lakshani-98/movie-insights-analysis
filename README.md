# 🎬 ReelAnalytics: A Deep Dive into Cinema (1986–2016)

This repository contains an exploratory data analysis (EDA) of a movie dataset covering the years 1986 to 2016. The dataset includes 6,820 movies, each with 15 metadata attributes. Using Python and visualization libraries, I explored correlations and relationships between different movie features such as runtime, budget, genre, and country.

---

## 📁 Dataset Overview

The dataset includes 15 attributes for each movie:

- `budget`
- `company`
- `country`
- `director`
- `gross`
- `name`
- `rating`
- `released`
- `runtime`
- `score`
- `votes`
- `star`
- `writer`
- `year`
- `genre`

## 🔍 Objectives

The primary goals of this notebook are to:

- Visualize overall trends and distributions using scatter plots and heatmaps.
- Generate a correlation matrix to uncover statistically significant relationships.
- Examine specific relationships:
  - Genre vs. Runtime
  - Budget vs. Runtime
  - Genre vs. Country

---

## 📊 Visualizations and Analysis

### ✅ Scatter Plots
- Used to examine relationships such as budget vs. runtime and score vs. gross revenue.

### ✅ Heatmap
- Highlights correlation between numerical variables like budget, gross, votes, runtime, and score.

### ✅ Correlation Matrix
- Helps identify which movie features are strongly correlated (positively or negatively).

### ✅ Relationship Comments
- **Genre & Runtime**: Commentary on how runtime varies by genre.
- **Budget & Runtime**: Commentary on whether higher-budget films tend to be longer.
- **Genre & Country**: Observations on genre popularity by country.

---

## 🛠️ Tools Used

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- NumPy

---
