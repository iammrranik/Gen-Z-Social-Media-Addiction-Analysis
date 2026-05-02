# 📊 Gen-Z Social Media Addiction Analysis (Python Final Term Project)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0000,25:FF7F00,50:FFFF00,75:00FF00,100:0000FF&height=200&section=header&text=Gen-Z%20Social%20Media%20Analysis&fontSize=32&fontColor=ffffff&animation=fadeIn"/>
</p>

<p align="center"> <a href="https://github.com/iammrranik"> <img src="https://img.shields.io/badge/_Click_Here_to_Explore_My_GitHub_Profile-181717?style=for-the-badge&logo=github&logoColor=white"/> </a> </p>

---

## ✨ Status
🚧 **Completed**  
🧠 Built with Python, Pandas, NumPy, and Matplotlib  
📊 Analyzes a massive 1,000,000-row dataset  
🎯 Designed for Final Term Evaluation  

---

## 📊 Project Overview

This project investigates the patterns of social media addiction among Gen-Z users (ages 18-25) using a large-scale dataset. The primary goal is to identify how specific usage behaviors—such as daily hours, platform variety, and night usage—correlate with mental health and perceived addiction levels. The project guarantees data integrity through rigorous cleaning and uses statistical modeling to determine how screen time habits impact overall well-being.

---

## 🔥 Key Insights & Methodology

- 🧹 **Robust Data Cleaning:** Filtered out nearly 490,000 invalid entries, including out-of-scope ages and impossible usage metrics. Applied 5th and 95th percentile trimming to eliminate extreme statistical noise.
- ⚙️ **Feature Engineering:** Developed custom variables like `addiction_number` and `usage_intensity` to quantify qualitative labels. Engineered a weighted `addiction_risk` score that heavily penalizes late-night usage.
- 📉 **Statistical Analysis:** Conducted ANOVA and Chi-Square tests to validate findings. Proved that addiction level is a definitive driver of both digital habits and psychological distress.
- 🧠 **Mental Health Correlation:** Revealed a clear inverse relationship between digital habits and well-being, where users with high addiction levels reported significant drops in their mental health scores.
- 📊 **Visualizations:** Created comprehensive frequency histograms, correlation heatmaps, and bar charts to directly answer the core research questions.

---

## 📌 Tech Stack

- Python 3.x
- Pandas (Data Manipulation & Grouping)
- NumPy (Custom Computations & Conditionals)
- Matplotlib & Seaborn (Visualizations)
- SciPy (Statistical Testing like ANOVA)
- Kagglehub (Dataset Download)
- Jupyter Notebook

---

## 🗂️ Analysis Pipeline

1. **Data Loading:** Automatically downloads the `gen-z-social-media-usage-dataset` from Kaggle using `kagglehub`.
2. **Preprocessing:** Handles deduplication, dimension masking (filtering for valid 18-25 age ranges), and percentile-based outlier trimming.
3. **Feature Generation:** Translates categorical addiction levels to numeric scores using dictionary mapping. Calculates risk weights conditionally based on night usage via `np.where`.
4. **Statistical Testing:** Groups data by addiction increments to calculate average mental health and satisfaction metrics.
5. **Visualization:** Generates dynamic plots to illustrate usage distribution and mental health correlations.

---

## 🙏 Credits

Project analyzed and developed by **Md. Minhaj Rowfun Rabbi Anik**. 
Submitted for the *Programming in Python* Project.

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF0000,20:FF7F00,40:FFFF00,60:00FF00,80:0000FF,100:8B00FF&height=4" width="80%"/> </p>
