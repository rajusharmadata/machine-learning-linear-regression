# 🇨🇦 Canada Per Capita Income Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Linear%20Regression-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-Data%20Science-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 📌 Project Overview

This project predicts **Canada’s Per Capita Income** using **Linear Regression** based on historical yearly data.

The aim of this project is to:

- Analyze economic growth trends
- Apply supervised machine learning on real-world data
- Visualize the relationship between **Year** and **Income**

This project is suitable for **academic submission, GitHub portfolio, and interview discussion**.

---

## ✨ Key Features

- 📊 Exploratory Data Analysis (EDA)
- 🤖 Linear Regression Model
- 📈 Best-fit regression line visualization
- 🔮 Income prediction for future years
- 📓 Clean and well-structured Jupyter Notebook

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="60"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="80"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="60"/>
</p>

---

## 📂 Project Structure

Canada-Per-Capita-Income/
│
├── canada_income.csv
├── canada_per_capita_income.ipynb
└── README.md

---

## 📊 Dataset Description

| Column | Description             |
| ------ | ----------------------- |
| year   | Calendar year           |
| income | Per capita income (USD) |

- 📌 Dataset Type: Tabular
- 📌 Source: Public economic data
- 📌 Records: Year-wise income data

---

## 🧠 Machine Learning Approach

- **Algorithm:** Linear Regression
- **Learning Type:** Supervised Learning
- **Input Feature:** Year
- **Target Variable:** Per Capita Income

### 📐 Mathematical Model

Income = m × Year + b

Where:

- `m` = slope (growth rate)
- `b` = intercept (base income)

---

## 📈 Data Visualization

- Scatter plot showing actual income values
- Regression line representing income growth trend
- Clear visualization of long-term economic progress

---

## 🔮 Prediction Workflow

1. User inputs a year
2. Model applies the regression equation
3. Predicted per capita income is returned
4. Output is displayed numerically and visually

### 📌 Example

Enter year: 2025
Predicted Income: 45431.02

---

## ▶️ How to Run the Project

### 🔧 Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn
```

jupyter notebook
canada_per_capita_income.ipynb
