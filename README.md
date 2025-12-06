# 📱 Google Play Store App & User Review Analysis (EDA)

A complete Exploratory Data Analysis (EDA) of Google Play Store apps and their user reviews.  
This project uncovers **what drives app success**, including installs, ratings, categories, pricing, and user sentiment — enabling data-driven decisions for developers and businesses.

🎥 **Project Walkthrough Video (15–20 min):**  
👉 *Watch the full explanation here:* **https://drive.google.com/file/d/1wPJIRWtEXfNQDusHQGm5AdKPi6QaPuMI/view?usp=sharing**

---

## ⭐ Overview

This project analyzes two datasets:
- **Play Store metadata** (~10k apps)
- **User reviews** (~60k reviews)

The goal is to understand:
- What factors influence **installs**
- How **ratings and reviews** shape app success
- How **sentiment** impacts user engagement
- Which categories offer **opportunities** or **heavy competition**
- Insights that help developers enhance product quality and visibility

---

## 📂 Dataset Description

### 1️⃣ Play Store Dataset – `play_store_data.csv`
Contains detailed metadata for each app:
- App name, Category, Rating, Reviews  
- Installs, Size, Type (Free/Paid), Price  
- Content Rating, Genres  
- Last Updated, Android Version  

### 2️⃣ User Reviews Dataset – `user_reviews.csv`
Includes translated user review text:
- Translated Review  
- Sentiment (Positive / Negative / Neutral)  
- Sentiment Polarity  
- Sentiment Subjectivity  

---

## 🧰 Tools & Technologies Used

- 🐍 **Python**
- 📊 **Pandas**, **NumPy**
- 📉 **Matplotlib**, **Seaborn**, **Plotly**
- 💬 **NLTK** (Sentiment Analysis)
- 📓 **Jupyter Notebook / Google Colab**
- 🗂️ **Git & GitHub**

---

## 🎯 Business Objectives

- Identify factors that influence **app success and installs**  
- Analyze **rating patterns, category trends, and pricing strategy**  
- Understand how **sentiment and reviews** impact app performance  
- Provide actionable recommendations for improving **app quality and engagement**  

---

## 🛠️ Project Workflow

### ✔ 1. Data Loading & Cleaning
- Handling missing values  
- Removing duplicates  
- Cleaning size, installs, and price formats  
- Converting app size uniformly to MB  

### ✔ 2. Exploratory Data Analysis (EDA)
- Category-wise distribution and insights  
- Free vs Paid app comparison  
- Rating vs Install trends  
- Genre visualization (Treemap)  
- Sentiment analysis on reviews  
- Wordcloud for negative feedback  
- Bubble chart (Reviews vs Rating vs Installs)

### ✔ 3. Insight Generation
- Patterns extracted from key metrics and visualizations  

---

## 📊 Key Insights

- **Free apps** dominate installs, but paid apps can thrive in niche markets.  
- Apps with **4.0–4.5 ratings** + high review counts gain maximum traction.  
- Highly competitive categories: **Games, Family, Tools**.  
- Low-competition, high-opportunity categories: **Beauty, Parenting, Comics**.  
- Frequent negative review themes: **crashes, bugs, slow performance, update issues**.  
- App size doesn’t strongly reduce installs when value is high.

---

## 💼 Business Recommendations

- Start with a **free pricing strategy** to boost reach.  
- Target **low-competition categories** for early traction.  
- Fix stability issues promptly — they heavily affect ratings.  
- Encourage user engagement (reviews, feedback).  
- Keep app size optimized for smoother performance.  

---

## 📁 Project Structure

```
Play-Store-App-Review-Analysis-EDA/
│
├── notebooks/
│   └── playstore_eda.ipynb
│
├── data/
│   ├── play_store_data.csv
│   └── user_reviews.csv
│
├── visuals/
│   └── (exported graphs)
│
├── requirements.txt
│
└── README.md
```


## 📦 Installation

```bash
pip install -r requirements.txt
