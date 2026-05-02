# 📊 Gen-Z Social Media Addiction Analysis (Python Final Term Project)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0000,25:FF7F00,50:FFFF00,75:00FF00,100:0000FF&height=200&section=header&text=Gen-Z%20Social%20Media%20Analysis&fontSize=32&fontColor=ffffff&animation=fadeIn"/>
</p>

<p align="center"> <a href="https://github.com/iammrranik"> <img src="https://img.shields.io/badge/_Click_Here_to_Explore_My_GitHub_Profile-181717?style=for-the-badge&logo=github&logoColor=white"/> </a> </p>

---

## ✨ Status
🚧 **Completed**  
🧠 Built with Python, Pandas, NumPy, and Matplotlib[cite: 2, 3]  
📊 Analyzes a massive 1,000,000-row dataset[cite: 2, 3]  
🎯 Designed for Final Term Evaluation[cite: 3]  

---

## 📊 Project Overview

This project investigates the patterns of social media addiction among Gen-Z users (ages 18-25) using a large-scale dataset[cite: 2]. The primary goal is to identify how specific usage behaviors—such as daily hours, platform variety, and night usage—correlate with mental health and perceived addiction levels[cite: 2]. The project guarantees data integrity through rigorous cleaning and uses statistical modeling to determine how screen time habits impact overall well-being[cite: 2].

---

## 🔥 Key Insights & Methodology

- 🧹 **Robust Data Cleaning:** Filtered out nearly 490,000 invalid entries, including out-of-scope ages and impossible usage metrics[cite: 2]. Applied 5th and 95th percentile trimming to eliminate extreme statistical noise[cite: 2].
- ⚙️ **Feature Engineering:** Developed custom variables like `addiction_number` and `usage_intensity` to quantify qualitative labels[cite: 2]. Engineered a weighted `addiction_risk` score that heavily penalizes late-night usage[cite: 2, 3].
- 📉 **Statistical Analysis:** Conducted ANOVA and Chi-Square tests to validate findings[cite: 2, 3]. Proved that addiction level is a definitive driver of both digital habits and psychological distress[cite: 2].
- 🧠 **Mental Health Correlation:** Revealed a clear inverse relationship between digital habits and well-being, where users with high addiction levels reported significant drops in their mental health scores[cite: 2].
- 📊 **Visualizations:** Created comprehensive frequency histograms, correlation heatmaps, and bar charts to directly answer the core research questions[cite: 2].

---

## 📌 Tech Stack

- Python 3.x
- Pandas (Data Manipulation & Grouping)[cite: 2]
- NumPy (Custom Computations & Conditionals)[cite: 2]
- Matplotlib & Seaborn (Visualizations)[cite: 2]
- SciPy (Statistical Testing like ANOVA)[cite: 2]
- Kagglehub (Dataset Download)[cite: 3]
- Jupyter Notebook[cite: 3]

---

## 🗂️ Analysis Pipeline

1. **Data Loading:** Automatically downloads the `gen-z-social-media-usage-dataset` from Kaggle using `kagglehub`[cite: 3].
2. **Preprocessing:** Handles deduplication, dimension masking (filtering for valid 18-25 age ranges), and percentile-based outlier trimming[cite: 2, 3].
3. **Feature Generation:** Translates categorical addiction levels to numeric scores using dictionary mapping[cite: 2, 3]. Calculates risk weights conditionally based on night usage via `np.where`[cite: 2, 3].
4. **Statistical Testing:** Groups data by addiction increments to calculate average mental health and satisfaction metrics[cite: 2, 3].
5. **Visualization:** Generates dynamic plots to illustrate usage distribution and mental health correlations[cite: 2, 3].

---

## 🙏 Credits

Project analyzed and developed by **Md. Minhaj Rowfun Rabbi Anik** (ID: 23-54110-3)[cite: 2]. 
Submitted for the *Programming in Python [D]* course under instructor *MD. TANZEEM RAHAT*[cite: 2].

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF0000,20:FF7F00,40:FFFF00,60:00FF00,80:0000FF,100:8B00FF&height=4" width="80%"/> </p>
