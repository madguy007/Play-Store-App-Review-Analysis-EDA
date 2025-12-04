# 📱 Google Play Store App & User Review Analysis (EDA)

Exploratory Data Analysis (EDA) performed on Google Play Store app metadata and user reviews to uncover key factors influencing app success, downloads, and user engagement.

---

## ⭐ Project Overview  
This project analyzes two datasets — **Play Store app data** and **user review data** — to identify patterns in installs, ratings, categories, pricing, and sentiment. The objective is to help app developers and businesses understand what drives app performance on the Play Store and make data-driven decisions.

---

## 📂 Dataset Description

### **1️⃣ Play Store Dataset (play_store_data.csv)**
Includes metadata of ~10,000 apps:
- App, Category, Rating, Reviews  
- Installs, Size, Type (Free/Paid), Price  
- Content Rating, Genres  
- Last Updated, Android Version  

### **2️⃣ User Reviews Dataset (user_reviews.csv)**
Contains ~60,000 translated reviews:
- Translated Review  
- Sentiment (Positive / Negative / Neutral)  
- Sentiment Polarity  
- Sentiment Subjectivity  

---

## 🎯 Business Objective
- Identify the key factors influencing app installs and success  
- Analyze rating behavior, app categories, pricing strategy, and size  
- Understand the impact of user sentiment on app performance  
- Provide insights to help improve app quality, marketing, and user engagement  

---

## 🛠️ Project Workflow
1. Data loading and inspection  
2. Data cleaning  
   - Handling missing values  
   - Fixing inconsistent formats  
   - Removing duplicates  
   - Converting app size to MB  
3. Exploratory Data Analysis  
   - Category distribution  
   - Free vs Paid installs  
   - Rating vs Installs trend  
   - Treemap of Category → Genre  
   - Sentiment distribution  
   - Word cloud for negative reviews  
   - Bubble plot: Reviews vs Rating vs Installs  
4. Insights & business recommendations  
5. Final conclusion  

---

## 📊 Key Insights
- **Free apps attract far more installs** than paid apps.  
- Apps with **moderate ratings (4.0–4.5)** and **high review counts** are more successful than apps with perfect ratings but low engagement.  
- Categories such as **Games** and **Family** dominate the Play Store, while categories like **Beauty**, **Parenting**, and **Comics** show low competition — offering new opportunities.  
- Negative user reviews frequently mention **crashes, bugs, slow speed, and update issues**, indicating areas that developers must prioritize.  
- Larger app size does **not** significantly reduce installs if the app provides strong value.  

---

## 💼 Business Recommendations
- Adopt a **free pricing model** initially to increase reach.  
- Target **low-competition categories** for faster visibility and growth.  
- Improve stability by addressing issues found in negative reviews.  
- Encourage user engagement (reviews) — a strong predictor of success.  
- Optimize app performance and size to enhance user experience.  

---

## 📦 Installation
Install required libraries:

```bash
pip install -r requirements.txt

--- 

## 📦 Project Structure
Play-Store-App-Review-Analysis-EDA/
├── notebooks/
│   └── playstore_eda.ipynb
├── data/
│   ├── play_store_data.csv
│   └── user_reviews.csv
├── visuals/
│   └── (exported graphs)
├── README.md
