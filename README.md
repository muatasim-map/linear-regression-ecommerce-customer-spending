# 🛍️ E-commerce Customer Spending Prediction (Linear Regression)

This project uses **Linear Regression** to predict the **yearly spending** of customers based on their interaction with an e-commerce website.

It's designed as a **foundational project** for understanding how to apply machine learning to real-world business problems using Python, pandas, seaborn, and scikit-learn.

---

## 🔍 Problem Statement

An e-commerce company wants to **optimize its marketing strategy**. Should it invest more in:

- improving the mobile app, or  
- enhancing the website experience?

To help with this, we build a model that predicts **how much a customer is likely to spend in a year** based on their usage patterns.

---

## 📊 Dataset Overview

The dataset contains:

| Feature                     | Description                                 |
|----------------------------|---------------------------------------------|
| `Avg. Session Length`      | Avg session duration on the website (minutes) |
| `Time on App`              | Time spent on mobile app (minutes)            |
| `Time on Website`          | Time spent on website (minutes)              |
| `Length of Membership`     | Years since user became a customer            |
| `Yearly Amount Spent`      | 🔥 **Target Variable** - amount spent ($)     |

---

## 🧪 Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation  
- **Seaborn** – visualization  
- **Scikit-learn** – model building and evaluation

---

## ✅ Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Visualized relationships using **pair plots**
- Checked for **correlations** between features and target
- Gained insights about which features most influence spending

### 2. Model Building
- Applied **Linear Regression** using scikit-learn
- Trained on features: session length, time on app/website, membership length

### 3. Model Evaluation
- Used metrics like:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
- Visualized **residuals** to check model assumptions

### 4. Business Recommendation
- Based on analysis, suggested whether the company should improve **app or website**

---

## 🧠 What I Learned

- How to approach a regression problem end-to-end
- Importance of EDA before modeling
- How to interpret regression coefficients
- Model evaluation beyond just accuracy

---


