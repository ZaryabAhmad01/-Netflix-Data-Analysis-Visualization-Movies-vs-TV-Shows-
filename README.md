
# 📊 Netflix-Data-Analysis-Visualization-Movies-vs-TV-Shows

## 📌 Project Overview
This project performs an **exploratory data analysis (EDA)** on the Netflix dataset to uncover insights about the distribution of **Movies vs TV Shows**, ratings, durations, release years, and country-wise content production.  
The analysis is presented through clear and professional **visualizations** using Python.

---

## 📂 Dataset
- **File**: `netflix_titles.csv`
- **Source**: Public dataset (Netflix Titles from Kaggle or similar)
- **Main Columns Used**:
  - `type` → Content type: *Movie* or *TV Show*
  - `country` → Country of origin
  - `release_year` → Year when content was released
  - `rating` → Audience rating (e.g., PG, R, TV-MA)
  - `duration` → Duration in minutes (Movies) or number of seasons (TV Shows)

---

## ⚙️ Technologies Used
- **Python 3**
- **Pandas** → Data cleaning & manipulation
- **Matplotlib** → Data visualization

---

## 📊 Visualizations Created
1. **Bar Chart** → Number of Movies vs TV Shows  
2. **Pie Chart** → Distribution of content ratings  
3. **Histogram** → Distribution of movie durations  
4. **Scatter Plot** → Release year vs number of shows  
5. **Horizontal Bar Chart** → Top 10 countries by number of shows  
6. **Line Plots (Subplots)** → Comparison of Movies vs TV Shows released per year  

Each visualization is also **saved as a PNG image** for easy sharing.

---

## ✅ Key Insights
- Netflix hosts **more Movies than TV Shows**.  
- Most content comes from a handful of countries (USA, India, UK, etc.).  
- **Movie durations** are mostly in the 90–120 minute range.  
- The **number of releases increased significantly after 2010**, especially TV Shows.  
- Ratings are dominated by a few categories (TV-MA, TV-14, PG, etc.).

---

## 🚀 Future Improvements
- Add **genre-level analysis** (using `listed_in` column).  
- Create **word clouds** for common keywords in movie/TV titles.  
- Build an **interactive dashboard** using Streamlit or Plotly.  
- Expand analysis to cover **actors, directors, and production companies**.  

---

## 🙌 Author
Developed by *[Zaryab Ahmad]* as part of a **Data Analysis and Visualization Project** in Python.
