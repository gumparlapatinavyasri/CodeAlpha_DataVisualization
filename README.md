#  Student Habits & Exam Performance Analysis

This project explores the relationship between student lifestyle behaviors and academic outcomes. Through detailed analysis and visual storytelling, we uncover patterns linking study time, sleep, screen habits, diet, and mental health to exam scores.

> "Students thrive not just on how much they study, but how well they balance sleep, attention, and digital habits."

---

##  Project Overview

Do better habits lead to better grades? This exploratory analysis investigates how a mix of behavioral metrics — including study routines, attendance, digital entertainment, and personal wellness — shape student success.

##  Dataset Used

- **Source:** Simulated survey-based dataset  
- **Records:** 1900+ students  
- **Fields:**  
  - Exam Score  
  - Study Hours / Sleep / Diet  
  - Screen Time (Netflix)  
  - Mental Health Score  
  - Attendance Rate  
  - Extracurricular Participation

---

###  Distribution of Exam Scores  
![image alt](https://github.com/gumparlapatinavyasri/CodeAlpha_DataVisualization/blob/4d770e985eb53dc9972ae2fb7d763d928a7464c1/1.png)

We start by understanding how students performed overall. This histogram reveals clustering of exam scores around 70 and 100. It sets the stage for deeper dives into contributing factors.  
**Why this image?** — It defines the baseline and helps identify outliers and performance modes. Crucial for any performance-based analysis.


---

##  Process & Methodology

1. **Cleaning & Encoding**  
2. **EDA (Exploratory Data Analysis)**  
   - Boxplots, scatterplots, heatmaps, regression curves  
3. **Visual Analytics**  
   - Used Seaborn, Matplotlib, Plotly  
   - Highlights performance drivers
4. **Dashboard Option**  
   - Streamlit / Tableau integration (if deployed)

---

##  Key Insights

###  Study Time vs Exam Score  
![image alt](https://github.com/gumparlapatinavyasri/CodeAlpha_DataVisualization/blob/77b1e7b799b81ee1ca272a0f0820c4a63a9e19d5/2.png)


This scatter plot shows scores improving with study time up to ~6 hours/day. Beyond that, performance plateaus.  
**Why this image?** — It provides clear evidence of diminishing returns and optimal effort zones. Essential insight for time management strategies.

###  Sleep vs Exam Score & Diet Quality  
![Sleep Hours vs Exam Score](plots/sleep_diet_score_scatter.png)  

Colored dots represent students with poor, fair, or good diet quality. The plot shows diet moderating the impact of sleep duration on performance.  
**Why this image?** — It connects physical wellness to performance. Adds depth to your behavioral model by showing that sleep’s effect isn't isolated — it's diet-dependent.

###  Sleep vs Exam Score & Mental Health  
![Sleep vs Exam Score with Mental Health Rating](plots/sleep_mental_score_scatter.png)  

Colored by mental health score (1–10 scale), this plot shows high mental wellness students tending to perform better across sleep ranges.  
**Why this image?** — Introduces psychological factors, revealing how inner well-being enhances academic results. Vital for modern education analytics.

---
##  Tools Used

- Python
  · Pandas
  · Seaborn
  · Matplotlib
  · Plotly  

---
##  Conclusion

Student success is multi-dimensional. While study hours matter, this project demonstrates that sleep, diet, and mental wellness are equally critical. The four visuals above helped guide this understanding — from performance distribution to behavioral contributors.

-  Histogram to frame performance  
-  Scatter plots to diagnose effort impact  
- Diet and  Mental health plots to reveal wellness-driven academic trends  

Together, they build a compelling narrative backed by visuals and logic.



