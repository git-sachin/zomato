# 🍽️ Zomato Exploratory Data Analysis (EDA) Case Study  

## 📌 Project Overview  
This project applies **Exploratory Data Analysis (EDA)** techniques on Zomato restaurant datasets to uncover patterns, customer preferences, and market insights. Using **Python (Pandas, Matplotlib, Seaborn, NumPy)**, the analysis focuses on restaurant types, online vs. offline orders, ratings, and approximate costs for couples.  

The study demonstrates how **data cleaning, visualization, and statistical exploration** can support decision-making in the food & beverage industry.  

---

## 🎯 Objectives  
- Perform EDA to understand Zomato restaurant data.  
- Clean and transform datasets for reliable analysis.  
- Visualize trends in ratings, votes, and restaurant types.  
- Compare online vs. offline order preferences.  
- Analyze cost patterns for couples.  

---

## 📂 Dataset Details  
The dataset contains information such as:  
- **Restaurant Name**  
- **Type of Restaurant** (`listed_in(type)`)  
- **Online Order Availability** (`online_order`)  
- **Ratings** (`rate`)  
- **Votes** (`votes`)  
- **Approximate Cost for Two** (`approx_cost(for two people)`)  

---

## ⚙️ Tools & Libraries  
- **Python**  
- **Pandas** → Data manipulation & cleaning  
- **Matplotlib & Seaborn** → Data visualization  
- **NumPy** → Numerical computations  

---

## 🧹 Key Steps in Analysis  

1. **Data Loading & Cleaning**  
   - Handle missing values and clean `rate` column.  

2. **Restaurant Type Analysis**  
   - Distribution of different restaurant types.  

3. **Votes & Popularity**  
   - Identify restaurants with maximum votes.  

4. **Online vs. Offline Orders**  
   - Compare number of restaurants providing each option.  

5. **Ratings Distribution**  
   - Analyze customer rating patterns.  

6. **Cost Analysis**  
   - Study cost range for couples.  

7. **Comparative Analysis**  
   - Ratings: Online vs. Offline orders.  
   - Heatmap of order mode by restaurant type.  

---

## 📊 Sample Visualizations  
- Countplot of restaurant types.  
- Histogram of ratings.  
- Online vs. Offline orders distribution.  
- Cost for two distribution.  
- Boxplot of ratings by order type.  
- Heatmap of restaurant type vs. order mode.  

---

## 📝 Conclusions  
- Dining restaurants dominate in both number and votes.  
- Most restaurants don’t provide online delivery, but cafes are more likely to.  
- Ratings are concentrated between **3.5–4.0**.  
- Couples prefer restaurants with ~**₹300 cost for two**.  
- Online orders receive higher ratings compared to offline.  

---
