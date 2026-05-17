# 📊 ChatGPT Usage Patterns by Major (CS-215 Final Project)

## 📖 Overview

This project analyzes ChatGPT conversation logs collected from students across different majors, including Math/Engineering, Physics, Biology, Computer Science, and combined datasets. The goal is to understand how students from different academic backgrounds use ChatGPT, and to identify patterns in usage types through clustering and visualization techniques.

The analysis explores how prompt types differ by major and reveals trends in problem-solving, conceptual learning, coding help, and general assistance.

## 📂 Project Files
- math_engineering_user_df.csv – ChatGPT usage data for Math/Engineering students
- physics_user_df.csv – ChatGPT usage data for Physics students
- bio_user_df.csv – ChatGPT usage data for Biology students
- physics_math_user_df.csv – ChatGPT usage data for Physics & Math dataset
- physics_engineering_user_df.csv – ChatGPT usage data for Physics & Engineering dataset
- cs_user_df.csv – ChatGPT usage data for Computer Science students
- filtered_df.csv - cleaned and preprocessed dataset containing filtered ChatGPT conversation records used for analysis in this project.
- combine.ipynb – Main Colab notebook containing data processing, clustering, and visualizations
- CS-215 Final Project.ipynb - Colab notebook containing personal (Individual) data processing, clustering, and visualizations

## ⚙️ Methods & Tools Used
- Python (Pandas, NumPy)
- TF-IDF Vectorization (text feature extraction)
- KMeans Clustering (unsupervised learning)
- Data visualization using Plotly and Seaborn
- Crosstab analysis for normalized usage comparison

## 📊 Key Findings
- Different majors show distinct ChatGPT usage patterns (e.g., coding vs conceptual vs problem-solving queries).
- Clustering reveals clear groupings of usage types such as: Conceptual STEM Understanding, Applied Problem Solving & Lab Reports, Step-by-Step Learning & Clarification, Advanced equation solving, Strategy, Interpretation & Study Guidance. 
- Most majors rely heavily on Step-by-Step Learning & Clarification and Applied Problem Solving & Lab Reports, while advanced equation solving and strategy-based clusters are less common across all groups.
