# 🎬 Netflix Movies & TV Shows Data Analysis

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the Netflix dataset to uncover patterns in content delivery, genre popularity, and production trends over the years. 

This analysis is designed to showcase data storytelling and technical proficiency in Python, making it an ideal portfolio piece for Data Analyst roles at MNCs and tech-driven firms.

---

## 🎯 Business & Analytical Objectives
- **Content Distribution**: Analyze the ratio between Movies and TV Shows.
- **Trend Analysis**: Identify how Netflix content production has evolved over the decades.
- **Geographical Insights**: Determine which countries are the top contributors to Netflix’s library.
- **Rating & Maturity**: Understand the target audience distribution through content ratings.
- **Genre Exploration**: Identify the most popular genres and sub-categories.

---

## 🗂️ Dataset Overview
- **Domain**: Entertainment & Streaming Media
- **Source**: Kaggle (Netflix Movies and TV Shows)
- **Data Type**: Structured (CSV)

**Key Attributes:**
- `show_id`: Unique ID for every movie/show
- `type`: Identifier (Movie or TV Show)
- `title`: Title of the content
- `director`: Director of the movie/show
- `cast`: Actors involved
- `country`: Country of production
- `date_added`: Date it was added to Netflix
- `release_year`: Actual release year
- `rating`: TV Rating (PG-13, R, etc.)
- `duration`: Total duration (Minutes or Seasons)
- `listed_in`: Genre/Categories

---

## 🛠️ Tools & Technologies

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-316192?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-44484C?style=for-the-badge&logo=python&logoColor=white" />
</p>

- **Language**: Python
- **Libraries**: Pandas (Data Manipulation), NumPy (Numerical Analysis), Matplotlib/Seaborn (Visualization)
- **Environment**: Jupyter Notebook / Google Colab
- **Version Control**: Git & GitHub

---

## 🔍 Data Analysis Process

### 1. Data Cleaning & Preprocessing
- Handling null values in `director`, `cast`, and `country` columns.
- Converting `date_added` to datetime format for time-series analysis.
- Standardizing the `duration` column (splitting seasons vs. minutes).
- Filtering out duplicates to ensure data integrity.

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Analyzing single variables like ratings and release years.
- **Bivariate Analysis**: Comparing Movies vs. TV Shows across different metrics.
- **Text Analysis**: Processing the `listed_in` column to identify top genres.

### 3. Visual Insights
- Growth of Netflix content over the years (Line Charts).
- Top 10 countries producing content (Bar Charts).
- Distribution of content types (Pie Charts).
- Heatmaps to show correlation between release months and content uploads.

---

## 📊 Key Insights (Sample)
- **Content Shift**: A significant pivot towards TV Shows has been observed in recent years compared to standalone Movies.
- **Top Genre**: International Movies and Dramas dominate the platform's library.
- **Global Leader**: The United States remains the largest content producer, followed closely by India for movies.
- **Content Rating**: Most content on Netflix is rated `TV-MA`, indicating a focus on adult audiences.

---

## 📁 Project Structure
```text
Netflix-Data-Analysis/
├── data/               # Raw and cleaned CSV files
├── notebooks/          # Jupyter Notebooks with step-by-step code
├── visuals/            # Exported charts (PNG/JPG)
├── README.md           # Project documentation

---

🚀 How to Run the Project
1. Clone the repository:
git clone https://github.com/your-username/Netflix-Data-Analysis.git

2. Install dependencies:
pip install pandas numpy matplotlib seaborn

3.Run the analysis:
Open notebooks/netflix_analysis.ipynb in Jupyter Notebook and execute the cells.

---

👩‍💻 Author
Budiga Pavani
Data Analyst | Python & SQL Enthusiast
🔗 (LinkedIn) https://www.linkedin.com/in/pavani-budiga
🔗 (GitHub) https://github.com/budigepavani3/

⭐ If you find this project helpful, please consider giving it a star!
---

### 💡 Pro-Tips for your Netflix Project:
1.  **Missing Data**: Don't just drop missing values. In your code, explain *why* you filled them (e.g., filling missing countries with "Unknown" or the mode).
2.  **Word Clouds**: Since Netflix has a "Description" column, adding a **Word Cloud** visualization to this project looks very impressive for a portfolio.
3.  **The "Why"**: In your README, under "Key Insights," make sure to explain the *business* impact. For example: *"Understanding that TV-MA is the most common rating helps content creators know the platform's primary demographic."*
