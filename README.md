# 🌍 Poverty Analysis & Prediction Web Application

## 📌 Overview

This project is a comprehensive **poverty prediction and analysis web application** designed to forecast two major global poverty indicators:

### 🔹 **1. Poverty Gap**

Represents how far individuals fall below the poverty line — essentially showing the _depth_ of poverty in a country.

### 🔹 **2. International Poverty Line Shortfall**

Estimates the **total resources needed** to bring everyone below the **$2.15/day (2017 PPP)** poverty threshold up to that standard.

These metrics play a critical role for **governments, NGOs, and global development planners** in identifying vulnerable populations and creating informed, data-driven policies.

---

## 🎯 Why This Project Matters

Accurate forecasting helps in:

- Planning poverty alleviation budgets
- Identifying future high-risk regions
- Evaluating past policies and interventions
- Supporting UN SDG-1 (No Poverty)
- Making resource allocation efficient and targeted

---

# 🚀 Key Features

### ⭐ **1. Advanced ANN-Based Poverty Prediction**

Uses custom-trained **Artificial Neural Networks** to model poverty headcount patterns and forecast:

- Future poverty gaps
- International poverty shortfall requirements

### ⭐ **2. Streamlit Web Application**

A modern, lightweight, interactive UI built using **Streamlit**, enabling:

- Country-wise visualization
- Future poverty prediction
- Interactive graph exploration

### ⭐ **3. Interactive Visualizations**

Includes a wide variety of plots for:

- Poverty gap over time
- Aggregated poverty trends
- Country-wise comparative analysis
- International shortfall projections

### ⭐ **4. Custom Preprocessing & Feature Engineering**

The data goes through:

- Cleaning
- Filtering
- Missing value handling
- Feature generation

All optimized for ANN performance.

### ⭐ **5. Real-World Dataset**

The dataset is sourced from:
**Our World in Data — Poverty & Inequality Database (World Bank PIP)**
Filtered and engineered for accurate modeling.

---

# 🧰 Installation Guide

### ✅ **Prerequisites**

- Python **3.8+**
- Git installed

---

## 📥 Step 1: Clone This Repository

```bash
git clone https://github.com/SparshXD-bot/poverty_project.git
cd poverty_project
```

---

## 📦 Step 2: Install Required Packages

### Option A — Using requirements.txt

```bash
pip install -r requirements.txt
```

### Option B — Install manually

```bash
pip install pandas numpy tensorflow matplotlib seaborn plotly streamlit
```

---

## ▶️ Step 3: Run the Web App

```bash
streamlit run app.py
```

Your browser will open the app at:
👉 **[http://localhost:8501](http://localhost:8501)**

---

# 💻 Usage

### To run the web app at any time:

```bash
streamlit run app.py
```

---

# 🔍 Application Modules & Features

## **1. Data Upload & Preprocessing**

- Upload your own dataset
- Automatic preprocessing
- Quick statistical breakdown
- Clean and structured data for modeling

---

## **2. Visualization**

- Interactive charts
- Historical poverty trends
- Country-level comparative maps
- Statistical distribution plots

---

## **3. Analysis**

- Compute poverty metrics
- Trend analysis
- Predictive modeling using ANN
- Exportable insights (optional)

---

# 🖼️ Screenshots

(These are from the original project; ensure they exist in your repo.)

![Screenshot 1](Screenshots/1.png)
![Screenshot 2](Screenshots/2.png)
![Screenshot 3](Screenshots/3.png)
![Screenshot 4](Screenshots/4.png)
![Screenshot 5](Screenshots/5.png)
![Screenshot 6](Screenshots/6.png)

---

# 🐞 Troubleshooting

### ❗ Port Already in Use

```bash
streamlit run app.py --port 8888
```

### ❗ Package Versions Conflicting

```bash
pip install -r requirements.txt --upgrade
```

---

# 👥 Authors

- **Sparsh Mittal**
- **Rudra Dixit**
- **Lavanya Dharmadhikari**
- **Parth Enkhiya**
- **Ankit Jangid**
