# TikTok Video Analytics - Dataset Preparation

## Description
This project is part of the Machine Learning CIE 2 Activity 1. It focuses on inspecting, cleaning, analyzing, and preparing TikTok video analytics data for future machine learning workflows. The dataset includes engagement metrics like views, likes, and shares.

## Dataset / Source
- **Source:** Hugging Face (datahiveai)
- **Dataset URL:** [TikTok Videos Dataset](https://huggingface.co/datasets/datahiveai/Tiktok-Videos/resolve/main/train.csv)

## Work Completed
1. **Data Inspection:** Analyzed data types, missing values, and dataset shape.
2. **Data Cleaning:** Handled missing values (dropped 3 invalid rows, imputed missing text fields) and removed constant columns (e.g., `repost_count`).
3. **Exploratory Data Analysis (EDA):** Visualized video duration distributions and geographic locations using matplotlib and seaborn.
4. **Data Transformation:** Applied One-Hot Encoding to categorical location data and Min-Max Scaling to numerical engagement metrics.

## Key Results
- **Video Duration:** The majority of the TikTok videos in this dataset are short, mostly clustering around the 15 to 60-second mark.
- **Location:** Video creation is heavily concentrated geographically, with the vast majority originating from Indonesia ('ID') and the United States ('US').

## Acknowledgement
This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: [https://github.com/Princy2129](https://github.com/Princy2129)
