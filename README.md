# 📊 Amazon Prime Video – Exploratory Data Analysis (EDA)

Welcome to my EDA project focused on analyzing content from **Amazon Prime Video** using Python and Jupyter Notebook. This project dives deep into content diversity, regional spread, viewer ratings, and trends over time.

---

## 🔍 Problem Statements

1. What genres and content types dominate Amazon Prime?
2. How is content distributed across different countries?
3. How has the content evolved over the years?
4. Which shows/movies are the most popular or highest rated?

---

## 🎯 Business Objectives

- Evaluate genre trends to enhance audience engagement.
- Identify strong regional content for licensing or production.
- Study year-wise growth for strategic content investment.
- Compare popularity vs. ratings to improve recommendation systems.

---

## 📁 Dataset Information

- `titles.csv` – Contains metadata like title, genres, scores, certification, runtime, etc.  
  → Shape: **9,871 rows × 15 columns**

- `credits.csv` – Contains cast and crew information such as actors, directors, and their roles.  
  → Shape: **124,235 rows × 5 columns**

The datasets were cleaned and merged to form a final structured dataset of **124,179 rows × 19 columns**.

---

## 🧹 Data Cleaning Highlights

- Removed 3 duplicate rows from `titles.csv` and 56 from `credits.csv`
- Handled missing values:
  - `seasons`: 8,514 missing
  - `age_certification`: 6,487 missing
  - `imdb_score`: 1,021 missing
  - `imdb_votes`: 1,031 missing
- Merged datasets using `id` column to build a unified base for analysis

---

## 📊 Key Visualizations

| Chart # | Description | Type |
|--------|-------------|------|
| Chart 1 | Genre distribution | Bar Chart |
| Chart 13 | Content by country | Horizontal Bar Chart |
| Chart 11 | Content trend by year | Line Chart |
| Chart 17 | Top-rated titles (IMDb) | Styled Table |
| Chart 19 | Most popular titles (TMDb) | Styled Table |
| Chart 20 | Genre vs Age Certification | Stacked Bar Chart |

---

## 🧠 Key Insights

- Drama, Comedy, and Thriller dominate in quantity; Sci-Fi and Biography excel in quality
- US leads in volume; Canada and France offer high-quality regional content
- Post-2015 surge in releases due to Amazon Originals
- Popularity and ratings don’t always align — both are crucial for personalization
- Age certification is genre-dependent but can be more balanced

---

## 💡 Business Recommendations

- Expand content in high-rating, low-frequency genres like Sci-Fi and War
- Strengthen regional content from countries with high average ratings
- Continue leveraging Action and Thriller genres post-2015
- Improve recommendation logic using both ratings and popularity
- Balance age-targeted content across more genres for wider appeal

---

## 🚀 How to Run the Project

1. Clone the repo or download the ZIP
2. Open `Amazon_Prime_EDA.ipynb` in Jupyter Notebook
3. Place datasets in the `Dataset/` folder
4. Run each cell sequentially

---

## 🛠️ Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🤝 Let’s Connect

📧 Email: sakshiks003@gmail.com
🔗 LinkedIn: www.linkedin.com/in/sakshi-sonawane-7867b3225




