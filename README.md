# 📺 Netflix Titles Data Analysis

This project performs an insightful analysis of the **Netflix Titles dataset**, using Python libraries like `pandas`, `seaborn`, and `matplotlib`. The dataset contains metadata for TV Shows and Movies available on Netflix — including genre, country, rating, and date added.

---

## 📌 Objectives

- Clean and preprocess the dataset
- Analyze trends in Netflix content over time
- Visualize:
  - Content types (Movies vs TV Shows)
  - Top countries producing content
  - Genre distributions
  - Ratings and durations

---

## 📂 Dataset Details

- **Source**: [Kaggle Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File**: `netflix_titles.csv`
- **Attributes**:
  - `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🧹 Data Cleaning

- Dropped rows with missing critical fields: `type`, `country`, `date_added`, `listed_in`
- Converted `date_added` to datetime and extracted the year
- Extracted:
  - First country (from multiple countries)
  - First genre (from multiple genres)
  - Duration in minutes (for movies only)

---

## 📊 Visualizations

The project generates and saves a dashboard image (`netflix_analysis_simple.png`) containing the following charts:

1. 📅 **Titles added per year**
2. 🎬 **Distribution of content type (Movie vs TV Show)**
3. 🌍 **Top 10 countries by number of titles**
4. 🎭 **Top 10 genres on Netflix**
5. 🔞 **Distribution of content ratings**
6. ⏱️ **Histogram of movie durations**

---

## 🛠️ Technologies Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- NumPy

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/manvitha2301cs29
