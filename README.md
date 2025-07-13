# 🎬 Movie Data Analysis with Python

This project explores a dataset of movies using Python and pandas in Jupyter Notebook. The goal was to understand which features (like budget, votes, or production company) have the strongest correlation with a movie's gross revenue.

---

## 🧰 Tools & Libraries Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## 📊 Key Analysis Performed

- Cleaned and converted data types (`budget`, `gross`, and `release year`)
- Created a new `yearcorrect` column from the `released` date
- Numerized categorical columns to perform correlation analysis
- Generated a correlation heatmap using **Pearson method**
- Identified that:
  - **Budget** and **Votes** have the highest positive correlation with **Gross**
  - **Company** has low correlation with gross earnings (initial assumption was incorrect)

---

## 🧪 Core Techniques

- Data type conversion
- Feature engineering
- Correlation analysis
- Seaborn heatmap visualization

---

## 🗃️ Data Source

- Movie dataset from [Kaggle](https://www.kaggle.com/)  
