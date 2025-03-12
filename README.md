# NHL Player Performance Prediction

## 📌 Project Overview
This project develops a **machine learning-based projection system** that predicts how a hockey player will perform in their **first three NHL seasons** based on their **pre-NHL statistics**. The model processes **historical player data**, scrapes additional statistics from **HockeyDB**, and applies **Random Forest Regression** to generate performance forecasts.

---

## 🏒 Why This Project Matters
Unlike the NFL or NBA, where players primarily come from the **NCAA**, NHL players come from **various leagues worldwide** (AHL, KHL, SHL, OHL, NCAA, etc.), making performance comparisons difficult.  
Our model accounts for **league difficulty and player development paths** to make **accurate NHL projections**.

---

## 🔥 What Makes Our Model Unique?

✔ **Adjusts for League Difficulty** – Accounts for variations in scoring difficulty across different leagues.  
✔ **Incorporates Global Data** – Analyzes stats from players across **all major pre-NHL leagues**.  
✔ **Built by Hockey Players, for Hockey Players** – As UCSB hockey players, we understand player development beyond just numbers.

---

## 🛠 Project Steps

### **1️⃣ Data Collection & Processing**
- Extracted **NHL player stats** from an original dataset and filtered relevant player information.  
- Scraped **additional player career stats** from **HockeyDB** for a more complete dataset.

### **2️⃣ Data Cleaning & Standardization**
- Removed **unnecessary data** and duplicates.  
- Eliminated **unqualified players** (those with less than three NHL seasons) to ensure unbiased predictions.  
- Structured the dataset to include **pre-NHL and NHL career stats**.

### **3️⃣ Machine Learning Model**
Built a **Random Forest Regression model** to predict:  
- **Games Played (GP)**  
- **Goals (G)**  
- **Assists (A)**  
- **Points (PTS)**  
- **Penalty Minutes (PIM)**  
- **Plus/Minus (+/-)**  

Our model outperformed **Multiple Linear Regression**, as **Random Forest captures non-linear trends and league differences** more effectively.

### **4️⃣ Developing an Interactive Website**
- A **Flask-based web platform** is in development to allow users to input player data and get NHL performance predictions.
- Features include:  
  ✔ **Player Analysis & Projections** – View projected NHL performance.  
  ✔ **League Difficulty Comparison** – Analyze performance trends across leagues.  
  ✔ **Player Comparison** – Compare predictions with actual NHL players.

---

## 🚀 Future Enhancements
🔹 **Integrate advanced deep learning models for improved accuracy.**  
🔹 **Refine league difficulty adjustments for better projections.**  
🔹 **Expand web platform features for enhanced user interaction.**

---

### **📢 Contributors**
🛠 **Team Lewandowski**  
- **Elvin Kim**  
- **Jay Leung**  
- **Adian Murzagaliyev**  
- **Sou Hamura**  
