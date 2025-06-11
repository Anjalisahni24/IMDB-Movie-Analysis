# 🎬 IMDB Movies Analysis

## 📌 Project Overview

This project explores a dataset of IMDB-listed movies to identify the **factors influencing movie success**, where success is defined by **higher IMDB ratings**. The analysis helps producers, directors, and investors understand what makes a movie well-received, aiding data-driven decisions in future film projects.

---

## 🎯 Problem Statement

> **What factors influence the success of a movie on IMDB?**

The project answers this through in-depth analysis of variables such as:
- Genre
- Movie Duration
- Language
- Director
- Budget vs Profit

---

## 🧭 Approach & Methodology

1. **Data Cleaning & Preparation**
   - Removed irrelevant columns (e.g., Facebook likes, color)
   - Split genre lists into separate columns
   - Removed duplicates, handled missing values

2. **Data Analysis in Excel**
   - Used functions like `AVERAGEIF`, `COUNTIF`, `PERCENTILE`, `CORREL`
   - Generated scatter plots, pie charts, and bar graphs
   - Applied **descriptive statistics** and **correlation analysis**

3. **Data Storytelling**
   - Combined insights with graphs in a clean, visual presentation
   - Designed final report using Canva for clear communication

---

## 📁 Folder Structure

IMDB-Movies-Analysis/
─ dataset_IMBD_movie/ # Excel file used in analysis
─ visuals/ # Images of charts and graphs
 ├── genre_chart.png
 ├── director_avg_scores.png
- IMBD final.xlsx #   Solution of the dataset
─ IMDB Movies.pdf # Final presentation/report
─ README.md # Project documentation
─ requirements.txt # Environment and tools

---

## 🧪 Analysis Tasks

### A. Genre vs IMDB Score

- **Most common genres:** Comedy, Action, Drama, Adventure, Crime
- **Techniques used:**
  - `=COUNTIF()`, `=AVERAGEIF()`, `=VAR.S()`, `=STDEV.S()`
- **Key Finding:**  
  - 🎬 *Documentary* had the highest average rating (7.18)  
  - 🎭 *Family* had the lowest (5.71) and most unpredictable ratings (highest variance)

---

### B. Duration vs IMDB Score

- **Avg Duration:** 108 minutes  
- **Standard Deviation:** ~22.5 minutes  
- **Tools Used:** Scatter Plot with Trendline  
- **Insight:**  
  - No strong correlation found, but movies between **90–120 minutes** tend to perform better

---

### C. Language vs IMDB Score

- **Top Languages:** English, French, Spanish  
- **Notable Findings:**
  - 🈶 *Hebrew* has the highest mean score (7.58), most consistent (SD = 0.35)  
  - 🀄 *Chinese* is lowest-rated (avg = 3.67)  
  - 🇬🇧 *English* is most frequent but mixed (mean = 6.37, high SD)

---

### D. Director vs IMDB Score

- **Method:**
  - `=AVERAGEIF()` to calculate mean ratings
  - `=PERCENTILE.INC()` to identify top 10% directors
- **Finding:**  
  - Directors above the **90th percentile** had significantly stronger IMDB averages  
  - Indicates strong **directional influence on ratings**

---

### E. Budget vs Profit

- **Profit Formula:** `=Gross - Budget`  
- **Correlation:** `=CORREL(Budget, Gross)` → ~0.11 (very weak positive correlation)  
- **Top Profit Movie:** 🎥 *Avatar* ($523M+ net profit)

---

## 📊 Key Insights

- High-budget movies ≠ high ratings. **Content > money**
- **Directors** and **genre choice** are stronger indicators of success
- **Language and cultural factors** may influence critical reception
- The ideal movie **duration range is 90–120 minutes**
- Statistical + visual analysis enables **data-driven production decisions**

---

## 🛠 Tech Stack

| Tool              | Purpose                                 |
|-------------------|------------------------------------------|
| Microsoft Excel 2022 | Data cleaning, analysis, and charting |
| Canva              | Designing the final PDF report          |
| Git + GitHub       | Project hosting & version control       |


---

## 🚀 How to Use This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/IMDB-Movies-Analysis.git
   cd IMDB-Movies-Analysis
2. Open the Excel file in /dataset/imdb_movies.xlsx
3. View insights in /IMDB_Movies_Report.pdf or open individual visuals in /visuals

---

## 📬 Contact
📧 24anjalisahni@gmail.com
🔗 https://www.linkedin.com/in/anjali-sahni-481b44238/
🌐 GitHub: https://github.com/Anjalisahni24
