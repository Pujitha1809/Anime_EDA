# 📊 Anime Dataset — Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) performed on the **Anime Dataset (`anime.csv`)** using **Google Colab**.

The goal of this analysis was to understand the structure of the dataset, examine key patterns, and visualize relationships between important variables such as ratings, popularity, and episode count.

---

## 📌 **Dataset Overview**

The dataset contains information about 10,000 anime titles with the following key attributes:

- **anime_id** – Unique identifier  
- **title** – Name of the anime  
- **score** – Average user rating  
- **rank** – Rank based on score  
- **popularity** – Popularity ranking  
- **members** – Number of users who added the anime  
- **synopsis** – Short description  
- **start_date / end_date** – Airing period  
- **type** – TV, Movie, OVA, Special, etc.  
- **episodes** – Number of episodes  

---

## 🔍 **What I Did (EDA Steps)**

### ✔ Data Inspection
- Checked shape, columns, and data types  
- Examined first few rows of the dataset  

### ✔ Missing Value Analysis
- Identified columns with missing values  
- Visualized missing value percentages  

### ✔ Statistical Analysis
- Used `describe()` to summarize numeric features  
- Analyzed mean, median, min, max, and variability  

### ✔ Visualizations
I created the following plots:
- 📈 Distribution of anime scores  
- 📊 Distribution of members (log scale)  
- 📺 Distribution of number of episodes  
- 📋 Count of anime by type  
- 🔵 Score vs Members (scatter plot)  
- 🔵 Score vs Episodes (scatter plot)  
- 📦 Boxplot of Score by Anime Type  
- 🔥 Correlation heatmap of numeric features  

---

## 🛠️ **Technologies Used**
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📂 **Dataset**
The dataset is taken from Kaggle:  
🔗 https://www.kaggle.com/ (search for “anime.csv” dataset)

*(If you upload the dataset to this repo, remove this note.)*

---

## ▶️ **How to View the Analysis**
Open the notebook in Google Colab or Jupyter:

```bash
anime_eda.ipynb


Pujitha Mamidishetty
