# 🎬 Netflix Age Rating Prediction

## 📌 Project Overview

This project predicts the **age classification** (e.g., `TV-MA`, `PG-13`, etc.) of Netflix titles using supervised machine learning. It applies the CRISP-DM framework and uses the Netflix public dataset from Kaggle.

## 🧠 Objective

The goal is to help streaming platforms automate content classification for regulatory compliance and recommendation engines.

## 🧩 Dataset

- **Name:** Netflix Movies and TV Shows
- **Source:** [Kaggle - Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size:** ~8,800 rows, 12 columns

The dataset contains metadata for Netflix shows including type, duration, genres, release year, country, etc.

## ⚙️ Project Structure

```bash
netflix-age-rating-prediction/
│
├── data/
│ └── netflix_titles.csv
├── notebooks/
│ ├── 1_data_preprocessing.ipynb
│ ├── 2_model_training.ipynb
│ └── 3_model_evaluation.ipynb
├── report.pdf
├── requirements.txt 
└── README.md

