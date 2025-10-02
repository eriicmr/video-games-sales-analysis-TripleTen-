# 🎮 Video Games Sales Analysis – Sprint 6 Integrated Project  

This project analyzes global video game sales data to identify **patterns of success, platform trends, and user preferences**.  
The study simulates a real business case for the online store **Ice**, which wants to plan its 2017 marketing campaign by predicting which games are likely to succeed.  

The dataset contains game sales by region, critic and user reviews, genres, platforms, and ESRB ratings.  
The analysis combines **exploratory data analysis, visualization, and hypothesis testing** to provide actionable insights.  

---

## 📌 Project Objectives  

1. **Data Preparation**  
   - Cleaned and standardized column names  
   - Handled missing values (including `TBD` scores)  
   - Created new features such as **total global sales**  

2. **Exploratory Data Analysis**  
   - Games released per year and platform lifecycle trends  
   - Global and regional sales patterns by platform and genre  
   - Impact of **critic scores and user scores** on sales  
   - Boxplots and scatterplots for cross-platform comparisons  

3. **Regional Profiling**  
   - Top 5 platforms and genres in **NA, EU, and JP**  
   - Differences in consumer behavior across markets  
   - Effect of ESRB ratings on regional sales  

4. **Hypothesis Testing**  
   - **H1:** Average user ratings are the same for Xbox One and PC  
   - **H2:** Average user ratings differ between Action and Sports genres  
   - Defined null and alternative hypotheses, applied t-tests, interpreted results  

5. **Conclusions**  
   - Identified profitable platforms and genres for 2017 marketing strategy  
   - Provided evidence-based recommendations  

---

## 🛠️ Tools & Technologies  
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy` (data manipulation & statistics)  
  - `matplotlib`, `seaborn` (visualizations)  
  - `scipy.stats` (hypothesis testing)  

---

## 📂 Dataset  

File: `games.csv`  

- `Name` — game title  
- `Platform` — platform (e.g., Xbox, PlayStation, PC)  
- `Year_of_Release` — release year  
- `Genre` — genre (Action, Sports, etc.)  
- `NA_sales`, `EU_sales`, `JP_sales`, `Other_sales` — regional sales in millions of USD  
- `Critic_Score` — critic rating (0–100)  
- `User_Score` — user rating (0–10)  
- `Rating` — ESRB classification (e.g., E, T, M)  

---

## 🎯 Key Learning Outcomes  
- Built an **end-to-end workflow**: from cleaning raw data → visualizing trends → hypothesis testing  
- Strengthened ability to **profile users and markets** with regional analysis  
- Applied **statistical testing** to validate insights, not just describe them  
- Improved communication of technical findings through **clear visualizations and business framing**  

---

## 🚀 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/eriicmr/video-games-sales-analysis.git
